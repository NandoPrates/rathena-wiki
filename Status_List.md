---
title: Status List
permalink: /Status_List/
---

Status effects can affect a character through an item's effect, a skill's effect, or called from an NPC. Below is the list of all the possible status effects a character can have (taken from .

Status can be started by the [sc_start](/sc_start "wikilink") function.

Status Effects
==============

    List of all Status:
    SC_ALL -1
    SC_STONE    0
    SC_FREEZE   1
    SC_STUN 2
    SC_SLEEP    3
    SC_POISON   4
    SC_CURSE    5
    SC_SILENCE  6
    SC_CONFUSION    7
    SC_BLIND    8
    SC_BLEEDING 9
    SC_DPOISON  10
    SC_PROVOKE  20
    SC_ENDURE   21
    SC_TWOHANDQUICKEN   22
    SC_CONCENTRATE  23
    SC_HIDING   24
    SC_CLOAKING 25
    SC_ENCPOISON    26
    SC_POISONREACT  27
    SC_QUAGMIRE 28
    SC_ANGELUS  29
    SC_BLESSING 30
    SC_SIGNUMCRUCIS 31
    SC_INCREASEAGI  32
    SC_DECREASEAGI  33
    SC_SLOWPOISON   34
    SC_IMPOSITIO    35
    SC_SUFFRAGIUM   36
    SC_ASPERSIO 37
    SC_BENEDICTIO   38
    SC_KYRIE    39
    SC_MAGNIFICAT   40
    SC_GLORIA   41
    SC_AETERNA  42
    SC_ADRENALINE   43
    SC_WEAPONPERFECTION 44
    SC_OVERTHRUST   45
    SC_MAXIMIZEPOWER    46
    SC_TRICKDEAD    47
    SC_LOUD 48
    SC_ENERGYCOAT   49
    SC_BROKENARMOR  50
    SC_BROKENWEAPON 51
    SC_HALLUCINATION    52
    SC_WEIGHT50 53
    SC_WEIGHT90 54
    SC_ASPDPOTION0  55
    SC_ASPDPOTION1  56
    SC_ASPDPOTION2  57
    SC_ASPDPOTION3  58
    SC_SPEEDUP0 59
    SC_SPEEDUP1 60
    SC_ATKPOTION    61
    SC_MATKPOTION   62
    SC_WEDDING  63
    SC_SLOWDOWN 64
    SC_ANKLE    65
    SC_KEEPING  66
    SC_BARRIER  67
    SC_STRIPWEAPON  68
    SC_STRIPSHIELD  69
    SC_STRIPARMOR   70
    SC_STRIPHELM    71
    SC_CP_WEAPON    72
    SC_CP_SHIELD    73
    SC_CP_ARMOR 74
    SC_CP_HELM  75
    SC_AUTOGUARD    76
    SC_REFLECTSHIELD    77
    SC_SPLASHER 78
    SC_PROVIDENCE   79
    SC_DEFENDER 80
    SC_MAGICROD 81
    SC_SPELLBREAKER 82
    SC_AUTOSPELL    83
    SC_SIGHTTRASHER 84
    SC_AUTOBERSERK  85
    SC_SPEARQUICKEN 86
    SC_AUTOCOUNTER  87
    SC_SIGHT    88
    SC_SAFETYWALL   89
    SC_RUWACH   90
    SC_EXTREMITYFIST    91
    SC_EXPLOSIONSPIRITS 92
    SC_COMBO    93
    SC_BLADESTOP_WAIT   94
    SC_BLADESTOP    95
    SC_FIREWEAPON   96
    SC_WATERWEAPON  97
    SC_WINDWEAPON   98
    SC_EARTHWEAPON  99
    SC_VOLCANO  100
    SC_DELUGE   101
    SC_VIOLENTGALE  102
    SC_WATK_ELEMENT 103
    SC_ARMOR    104
    SC_ARMOR_ELEMENT    105
    SC_NOCHAT   106
    SC_BABY 107
    SC_AURABLADE    108
    SC_PARRYING 109
    SC_CONCENTRATION    110
    SC_TENSIONRELAX 111
    SC_BERSERK  112
    SC_FURY 113
    SC_GOSPEL   114
    SC_ASSUMPTIO    115
    SC_BASILICA 116
    SC_GUILDAURA    117
    SC_MAGICPOWER   118
    SC_EDP  119
    SC_TRUESIGHT    120
    SC_WINDWALK 121
    SC_MELTDOWN 122
    SC_CARTBOOST    123
    SC_CHASEWALK    124
    SC_REJECTSWORD  125
    SC_MARIONETTE   126
    SC_MARIONETTE2  127
    SC_CHANGEUNDEAD 128
    SC_JOINTBEAT    129
    SC_MINDBREAKER  130
    SC_MEMORIZE 131
    SC_FOGWALL  132
    SC_SPIDERWEB    133
    SC_DEVOTION 134
    SC_SACRIFICE    135
    SC_STEELBODY    136
    SC_ORCISH   137
    SC_READYSTORM   138
    SC_READYDOWN    139
    SC_READYTURN    140
    SC_READYCOUNTER 141
    SC_DODGE    142
    SC_RUN  143
    SC_SHADOWWEAPON 144
    SC_ADRENALINE2  145
    SC_GHOSTWEAPON  146
    SC_KAIZEL   147
    SC_KAAHI    148
    SC_KAUPE    149
    SC_ONEHAND  150
    SC_PRESERVE 151
    SC_BATTLEORDERS 152
    SC_REGENERATION 153
    SC_DOUBLECAST   154
    SC_GRAVITATION  155
    SC_MAXOVERTHRUST    156
    SC_LONGING  157
    SC_HERMODE  158
    SC_SHRINK   159
    SC_SIGHTBLASTER 160
    SC_WINKCHARM    161
    SC_CLOSECONFINE 162
    SC_CLOSECONFINE2    163
    SC_DANCING  164
    SC_ELEMENTALCHANGE  165
    SC_RICHMANKIM   166
    SC_ETERNALCHAOS 167
    SC_DRUMBATTLE   168
    SC_NIBELUNGEN   169
    SC_ROKISWEIL    170
    SC_INTOABYSS    171
    SC_SIEGFRIED    172
    SC_WHISTLE  173
    SC_ASSNCROS 174
    SC_POEMBRAGI    175
    SC_APPLEIDUN    176
    SC_MODECHANGE   177
    SC_HUMMING  178
    SC_DONTFORGETME 179
    SC_FORTUNE  180
    SC_SERVICE4U    181
    SC_STOP 182
    SC_SPURT    183
    SC_SPIRIT   184
    SC_COMA 185
    SC_INTRAVISION  186
    SC_INCALLSTATUS 187
    SC_INCSTR   188
    SC_INCAGI   189
    SC_INCVIT   190
    SC_INCINT   191
    SC_INCDEX   192
    SC_INCLUK   193
    SC_INCHIT   194
    SC_INCHITRATE   195
    SC_INCFLEE  196
    SC_INCFLEERATE  197
    SC_INCMHPRATE   198
    SC_INCMSPRATE   199
    SC_INCATKRATE   200
    SC_INCMATKRATE  201
    SC_INCDEFRATE   202
    SC_STRFOOD  203
    SC_AGIFOOD  204
    SC_VITFOOD  205
    SC_INTFOOD  206
    SC_DEXFOOD  207
    SC_LUKFOOD  208
    SC_HITFOOD  209
    SC_FLEEFOOD 210
    SC_BATKFOOD 211
    SC_WATKFOOD 212
    SC_MATKFOOD 213
    SC_SCRESIST 214
    SC_XMAS 215
    SC_WARM 216
    SC_SUN_COMFORT  217
    SC_MOON_COMFORT 218
    SC_STAR_COMFORT 219
    SC_FUSION   220
    SC_SKILLRATE_UP 221
    SC_SKE  222
    SC_KAITE    223
    SC_SWOO 224
    SC_SKA  225
    SC_TKREST   226
    SC_MIRACLE  227
    SC_MADNESSCANCEL    228
    SC_ADJUSTMENT   229
    SC_INCREASING   230
    SC_GATLINGFEVER 231
    SC_TATAMIGAESHI 232
    SC_UTSUSEMI 233
    SC_BUNSINJYUTSU 234
    SC_KAENSIN  235
    SC_SUITON   236
    SC_NEN  237
    SC_KNOWLEDGE    238
    SC_SMA  239
    SC_FLING    240
    SC_AVOID    241
    SC_CHANGE   242
    SC_BLOODLUST    243
    SC_FLEET    244
    SC_SPEED    245
    SC_DEFENCE  246
    SC_INCASPDRATE  247
    SC_INCFLEE2 248
    SC_JAILED   249
    SC_ENCHANTARMS  250
    SC_MAGICALATTACK    251
    SC_SUMMER   256
    SC_EXPBOOST 257
    SC_ITEMBOOST    258
    SC_BOSSMAPINFO  259
    SC_LIFEINSURANCE    260
    SC_INCCRI   261
    SC_INCDEF   262
    SC_INCBASEATK   263
    SC_FASTCAST 264
    SC_MDEF_RATE    265
    SC_HPREGEN  266
    SC_INCHEALRATE  267
    SC_PNEUMA   268
    SC_AUTOTRADE    269
    SC_KSPROTECTED  270
    SC_ARMOR_RESIST 271
    SC_SPCOST_RATE  272
    SC_COMMONSC_RESIST  273
    SC_SEVENWIND    274
    SC_DEF_RATE 275
    SC_SPREGEN  276
    SC_WALKSPEED    277
    SC_REBIRTH  284
    SC_SKILLCASTRATE    285
    SC_DEFRATIOATK  286
    SC_HPDRAIN  287
    SC_SKILLATKBONUS    288
    SC_ITEMSCRIPT   289
    SC_S_LIFEPOTION 290
    SC_L_LIFEPOTION 291
    SC_JEXPBOOST    292
    //SC_IGNOREDEF  293
    SC_HELLPOWER    294
    SC_INVINCIBLE   295
    SC_INVINCIBLEOFF    296
    SC_MANU_ATK 297
    SC_MANU_DEF 298
    SC_SPL_ATK  299
    SC_SPL_DEF  300
    SC_MANU_MATK    301
    SC_SPL_MATK 302
    SC_FOOD_STR_CASH    303
    SC_FOOD_AGI_CASH    304
    SC_FOOD_VIT_CASH    305
    SC_FOOD_DEX_CASH    306
    SC_FOOD_INT_CASH    307
    SC_FOOD_LUK_CASH    308
    SC_FEAR 309
    SC_BURNING  310
    SC_FREEZING 311
    SC_ENCHANTBLADE 312
    SC_DEATHBOUND   313
    SC_MILLENNIUMSHIELD 314
    SC_CRUSHSTRIKE  315
    SC_REFRESH  316
    SC_REUSE_REFRESH    317
    SC_GIANTGROWTH  318
    SC_STONEHARDSKIN    319
    SC_VITALITYACTIVATION   320
    SC_STORMBLAST   321
    SC_FIGHTINGSPIRIT   322
    SC_ABUNDANCE    323
    SC_ADORAMUS 324
    SC_EPICLESIS    325
    SC_ORATIO   326
    SC_LAUDAAGNUS   327
    SC_LAUDARAMUS   328
    SC_RENOVATIO    329
    SC_EXPIATIO 330
    SC_DUPLELIGHT   331
    SC_SECRAMENT    332
    SC_WHITEIMPRISON    333
    SC_MARSHOFABYSS 334
    SC_RECOGNIZEDSPELL  335
    SC_STASIS   336
    SC_SPHERE_1 337
    SC_SPHERE_2 338
    SC_SPHERE_3 339
    SC_SPHERE_4 340
    SC_SPHERE_5 341
    SC_READING_SB   342
    SC_FREEZINGSPELL    343
    SC_FEARBREEZE   344
    SC_ELECTRICSHOCKER  345
    SC_WUGDASH  346
    SC_BITE 347
    SC_CAMOUFLAGE   348
    SC_ACCELERATION 349
    SC_HOVERING 350
    SC_SHAPESHIFT   351
    SC_INFRAREDSCAN 352
    SC_ANALYZE  353
    SC_MAGNETICFIELD    354
    SC_NEUTRALBARRIER   355
    SC_NEUTRALBARRIER_MASTER    356
    SC_STEALTHFIELD 357
    SC_STEALTHFIELD_MASTER  358
    SC_OVERHEAT 359
    SC_OVERHEAT_LIMITPOINT  360
    SC_VENOMIMPRESS 361
    SC_POISONINGWEAPON  362
    SC_WEAPONBLOCKING   363
    SC_CLOAKINGEXCEED   364
    SC_HALLUCINATIONWALK    365
    SC_HALLUCINATIONWALK_POSTDELAY  366
    SC_ROLLINGCUTTER    367
    SC_TOXIN    368
    SC_PARALYSE 369
    SC_VENOMBLEED   370
    SC_MAGICMUSHROOM    371
    SC_DEATHHURT    372
    SC_PYREXIA  373
    SC_OBLIVIONCURSE    374
    SC_LEECHESEND   375
    SC_REFLECTDAMAGE    376
    SC_FORCEOFVANGUARD  377
    SC_SHIELDSPELL_DEF  378
    SC_SHIELDSPELL_MDEF 379
    SC_SHIELDSPELL_REF  380
    SC_EXEEDBREAK   381
    SC_PRESTIGE 382
    SC_BANDING  383
    SC_BANDING_DEFENCE  384
    SC_EARTHDRIVE   385
    SC_INSPIRATION  386
    SC_SPELLFIST    387
    SC_CRYSTALIZE   388
    SC_STRIKING 389
    SC_WARMER   390
    SC_VACUUM_EXTREME   391
    SC_PROPERTYWALK 392
    SC_SWINGDANCE   393
    SC_SYMPHONYOFLOVER  394
    SC_MOONLITSERENADE  395
    SC_RUSHWINDMILL 396
    SC_ECHOSONG 397
    SC_HARMONIZE    398
    SC_VOICEOFSIREN 399
    SC_DEEPSLEEP    400
    SC_SIRCLEOFNATURE   401
    SC_GLOOMYDAY    402
    SC_GLOOMYDAY_SK 403
    SC_SONGOFMANA   404
    SC_DANCEWITHWUG 405
    SC_SATURDAYNIGHTFEVER   406
    SC_LERADSDEW    407
    SC_MELODYOFSINK 408
    SC_BEYONDOFWARCRY   409
    SC_UNLIMITEDHUMMINGVOICE    410
    SC_SITDOWN_FORCE    411
    SC_NETHERWORLD  412
    SC_CRESCENTELBOW    413
    SC_CURSEDCIRCLE_ATKER   414
    SC_CURSEDCIRCLE_TARGET  415
    SC_LIGHTNINGWALK    416
    SC_RAISINGDRAGON    417
    SC_GT_ENERGYGAIN    418
    SC_GT_CHANGE    419
    SC_GT_REVITALIZE    420
    SC_GN_CARTBOOST 421
    SC_THORNSTRAP   422
    SC_BLOODSUCKER  423
    SC_SMOKEPOWDER  424
    SC_TEARGAS  425
    SC_MANDRAGORA   426
    SC_STOMACHACHE  427
    SC_MYSTERIOUS_POWDER    428
    SC_MELON_BOMB   429
    SC_BANANA_BOMB  430
    SC_BANANA_BOMB_SITDOWN  431
    SC_SAVAGE_STEAK 432
    SC_COCKTAIL_WARG_BLOOD  433
    SC_MINOR_BBQ    434
    SC_SIROMA_ICE_TEA   435
    SC_DROCERA_HERB_STEAMED 436
    SC_PUTTI_TAILS_NOODLES  437
    SC_BOOST500 438
    SC_FULL_SWING_K 439
    SC_MANA_PLUS    440
    SC_MUSTLE_M 441
    SC_LIFE_FORCE_F 442
    SC_EXTRACT_WHITE_POTION_Z   443
    SC_VITATA_500   444
    SC_EXTRACT_SALAMINE_JUICE   445
    SC__REPRODUCE   446
    SC__AUTOSHADOWSPELL 447
    SC__SHADOWFORM  448
    SC__BODYPAINT   449
    SC__INVISIBILITY    450
    SC__DEADLYINFECT    451
    SC__ENERVATION  452
    SC__GROOMY  453
    SC__IGNORANCE   454
    SC__LAZINESS    455
    SC__UNLUCKY 456
    SC__WEAKNESS    457
    SC__STRIPACCESSORY  458
    SC__MANHOLE 459
    SC__BLOODYLUST  460
    SC_CIRCLE_OF_FIRE   461
    SC_CIRCLE_OF_FIRE_OPTION    462
    SC_FIRE_CLOAK   463
    SC_FIRE_CLOAK_OPTION    464
    SC_WATER_SCREEN 465
    SC_WATER_SCREEN_OPTION  466
    SC_WATER_DROP   467
    SC_WATER_DROP_OPTION    468
    SC_WATER_BARRIER    469
    SC_WIND_STEP    470
    SC_WIND_STEP_OPTION 471
    SC_WIND_CURTAIN 472
    SC_WIND_CURTAIN_OPTION  473
    SC_ZEPHYR   474
    SC_SOLID_SKIN   475
    SC_SOLID_SKIN_OPTION    476
    SC_STONE_SHIELD 477
    SC_STONE_SHIELD_OPTION  478
    SC_POWER_OF_GAIA    479
    SC_PYROTECHNIC  480
    SC_PYROTECHNIC_OPTION   481
    SC_HEATER   482
    SC_HEATER_OPTION    483
    SC_TROPIC   484
    SC_TROPIC_OPTION    485
    SC_AQUAPLAY 486
    SC_AQUAPLAY_OPTION  487
    SC_COOLER   488
    SC_COOLER_OPTION    489
    SC_CHILLY_AIR   490
    SC_CHILLY_AIR_OPTION    491
    SC_GUST 492
    SC_GUST_OPTION  493
    SC_BLAST    494
    SC_BLAST_OPTION 495
    SC_WILD_STORM   496
    SC_WILD_STORM_OPTION    497
    SC_PETROLOGY    498
    SC_PETROLOGY_OPTION 499
    SC_CURSED_SOIL  450
    SC_CURSED_SOIL_OPTION   501
    SC_UPHEAVAL 502
    SC_UPHEAVAL_OPTION  503
    SC_TIDAL_WEAPON 504
    SC_TIDAL_WEAPON_OPTION  505
    SC_ROCK_CRUSHER 506
    SC_ROCK_CRUSHER_ATK 507
    SC_INCMHP   529
    SC_INCMSP   530
    SC_PARTYFLEE    531