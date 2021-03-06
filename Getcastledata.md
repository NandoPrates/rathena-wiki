---
title: GetCastleData
permalink: /GetCastleData/
---

Syntax
------

-   **getcastledata**("<map name>",<type of data>)
-   **setcastledata**"<map name>",<type of data>,<value>;

== Description == This function returns the castle ownership information for the castle referred to by its map name. Castle information is stored in \`guild_castle\` SQL table.

== Type of datas == Types of data correspond to \`guild_castle\` table columns:

`` 1 - `guild_id`   - Guild ID. ``
`` 2 - `economy`    - Castle Economy score. ``
`` 3 - `defense`    - Castle Defense score. ``
`` 4 - `triggerE`   - Number of times the economy was invested in today. ``
`` 5 - `triggerD`   - Number of times the defense was invested in today. ``
`` 6 - `nextTime`   - unused ``
`` 7 - `payTime`    - unused ``
`` 8 - `createTime` - unused ``
`` 9 - `visibleC`   - Is 1 if a Kafra was hired for this castle, 0 otherwise. ``
`` 10 - `visibleG0`  - Is 1 if the 1st guardian is present (Soldier Guardian) ``
`` 11 - `visibleG1`  - Is 1 if the 2nd guardian is present (Soldier Guardian) ``
`` 12 - `visibleG2`  - Is 1 if the 3rd guardian is present (Soldier Guardian) ``
`` 13 - `visibleG3`  - Is 1 if the 4th guardian is present (Archer Guardian) ``
`` 14 - `visibleG4`  - Is 1 if the 5th guardian is present (Archer Guardian) ``
`` 15 - `visibleG5`  - Is 1 if the 6th guardian is present (Knight Guardian) ``
`` 16 - `visibleG6`  - Is 1 if the 7th guardian is present (Knight Guardian) ``
`` 17 - `visibleG7`  - Is 1 if the 8th guardian is present (Knight Guardian) ``

All types of data have their meaning determined by War of Emperium scripts, with exception of:

`` - `guild_id` that is always considered ID of the guild that owns the castle, ``
`` - `defense` that is used in Guardians & Emperium HP calculations, ``
`` - `visibleG` that is always considered to hold guardian presence bits. ``

The **'setcastledata**' command will behave identically, but instead of returning values for the specified types of accessible data, it will alter them and cause them to be sent to the char-server for storage.

Changing Guild ID or Castle Defense will trigger additional actions, like recalculating guardians' HP.