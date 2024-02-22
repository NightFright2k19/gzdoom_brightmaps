==================================================================================
Advanced engine needed  : Limit-removing (GZDoom)
==================================================================================
Title                   : Brightmaps Collection for GZDoom v1.93
Filenames               : bmplus_spritefix.pk3
Release date            : ??/??/????
Author                  : NightFright

Description             : Sprites brightmaps for Doom, Doom II, Final Doom,
                          Heretic, Hexen and Strife. To be used with GZDoom only. 
                          Features additional brightmaps for Revenant100's spritefixes.

                          Notes:
                          - This file completely replaces brightmaps.pk3 that 
                            comes with GZDoom. You don't need to load both files
                            at the same time.
                          - It is assumed you use the spritefixes for Doom and 
                            Heretic made by Revenant100 (d1spfx20.wad, d2spfx20.wad, 
                            hrspfx10.wad). 
                          - Avoid loading these brightmaps with Doom/Heretic addons
                            that come with customized sprites.

Credits                 : Based on original graphics by
                          - id Software (Doom/Doom II)
                          - Raven Software (Heretic/Hexen)
                          - Rogue Entertainment (Strife)
                          - TeamTNT (Final Doom)

                          Brightmaps provided by
                          - Acidhoes (Hexen)
                          - DrVenom8 (Doom/Heretic)
                          - NightFright (Doom spritefixes)
                          - Virtue (Doom/Hexen/Strife)
 			  - Warden (some Mancubus sprites)

==================================================================================
* What is included *

New levels              : None
Sounds                  : No
Music                   : No
Graphics                : Yes
Dehacked/BEX Patch      : No
Demos                   : No
Other                   : No
Other files required    : d1spfx20.wad, d2spfx20.wad, hrspfx10.wad (can be changed)


* Play Information *

Game                    : Doom I/II, Final Doom, Heretic, Hexen, Strife
Map #                   : None
Single Player           : No
Cooperative 2-4 Player  : No
Deathmatch 2-4 Player   : No
Other game styles       : No
Difficulty Settings     : Not implemented


* Construction *

Base                    : Original id/Raven graphics
Build Time              : 24 hours
Editor(s) used          : XWE, paint.net
Known Bugs              : None (hopefully)
May Not Run With        : Vanilla doom.exe, doom2.exe, heretic.exe, 
                          hexen.exe, strife.exe (not compatible)
Tested With             : GZDoom


* Changelog *

Version 1.93 (??? ??, ????)
---------------------------
[DOOM] Converted colored brightmaps to greyscale (CANDA, CBRAA, CEYEA-C, CHGFA, SMBTA-D,
       SMGTA-D, SMRTA-D)
[DOOM2] Converted colored brightmaps to greyscale (FATBA, FATBA2A8, FATBA3A7, FATBB1,
        FATBB2B8, FATBB3B7, FATBB4B6)

Version 1.92 (Nov 29, 2022)
---------------------------
[DOOM2] Support for Sprite Fixes v2.0 (updated: BOS2A6C4, BOS2A7C3, BOS2A8C2, BOS2B6D4,
        BOS2B7D3, BOS2B8D2)

Version 1.91 (Nov 22, 2021)
---------------------------
[DOOM/DOOM2/PLUTONIA/TNT] Wadsmoosh support

Version 1.9 (Jul 26, 2021)
--------------------------
[DOOM2] Improved brightmaps for firing Mancubus (FATTH1, FATTH2H8, FATTH3H7, FATTH4H6, FATTH5) by Warden
[HERETIC/HEXEN] Added support for additional widescreen weapon sprites from GZDoom v4.6.1
[HEXEN] Corrected brightmap names for Falcon Shield (AR_2), Amulet of Warding (AR_4), 
        Icon of the Defender (DEFN), Blue Candle (BCAN)

Version 1.8 (May 25, 2021)
--------------------------
[HERETIC/HEXEN] Added support for Nash's GZDoom v4.6.0 widescreen weapon sprites
                (activated by default - edit heretic/gldefs.bm or hexen/gldefs.bm to turn off)

Version 1.7 (Feb 6, 2020)
-------------------------
[GENERAL] Split pack into three parts: bmplus_vanilla.pk3, bmplus_spritefix.pk3, bmplus_textures.pk3

Version 1.64 (Jun 8, 2019)
--------------------------
[DOOM] Added missing spritefix brightmap for Demon (SARGA2C8)

Version 1.63 (Jun 4, 2019)
--------------------------
[GENERAL] Brightmaps dir restructured into "sprites" and "textures" branches
[DOOM] Separate folders for Doom 1 and Doom 2 content
[DOOM] Burning barrel (FCAN) moved from Doom 2 to Doom 1 definitions  
[DOOM/HERETIC/HEXEN] Moved "flats" folders to textures subdirs
[PLUTONIA] Moved "plutonia" folder to textures\doom
[TNT] Moved "tnt" folder to textures\doom

Version 1.62 (May 1, 2019)
--------------------------
[DOOM] Adjusted lump filtering for DOOM 1+2 according to latest GZDoom 4.1.0 syntax

Version 1.61 (Apr 17, 2019)
---------------------------
[HERETIC] Improved: Quiver of Ethereal Arrows (AMC2 B/C), Crystal Vial (PTN1), Quartz Flask (PTN2)
[HERETIC] Fixed: Iron Lich (HEAD/LICH)

Version 1.6 (Apr 8, 2019)
-------------------------
[DOOM/HERETIC] All colored brightmaps converted to greyscale graphics to preserve 
               original sprite colors
[DOOM] Imported better brightmaps from brightmaps.pk3 for:
       - Archvile (all 80 available frames)
       - Burning barrel (FCAN)
       - Chaingunner firing (CPOS E/F)
       - Cyberdemon firing/exploding (CYBR F/J-O)
       - Player firing (PLAY F)
       - Sergeant firing (SPOS E/F)
       - Spider Mastermind exploding (SPID M-R)
       - Zombie firing (POSS E/F)
[DOOM] Improved brightmaps for Cacodemon (HEAD)
[DOOM] New brightmaps for Health Bonus (BON1)

Version 1.51 (Apr 4, 2019)
--------------------------
[GENERAL] PNG compression applied to all brightmaps (file size reduced by 50%)
[DOOM] Improved: Armor Bonus (BON2B/C), Evil Eye (CEYE), Powerup spheres (MEGA/PINS/PINV/SOUL), 
                 Computer Area Map (PMAPA/B), Light Amp Visor (PVISB)
[DOOM] Removed: Armors (ARM1/ARM2), Health Bonus (BON1), Keycards (BKEY/RKEY/YKEY), 
                Skull Keys (BSKU/RSKU/YSKU)

Version 1.5 (Apr 27, 2018)
--------------------------
[DOOM] Removed orange/yellow tints from all Lost Soul frames
[DOOM] Replaced Hellknight/Baron of Hell frames with those from brightmaps.pk3

Version 1.42 (Apr 4, 2018)
---------------------------
[DOOM] Removed glowing teeth from demon face in dem1_3 and dem1_4

Version 1.41 (Oct 27, 2017)
---------------------------
[DOOM] Fixed texture brightmap for SW2STARG in Doom/Doom II

Version 1.4 (Jul 26, 2017)
--------------------------
[GENERAL] Updated for compatibility with Doom Minor Sprite Fixing Project v1.9 (weapon firing frames)

Version 1.3 (May 5, 2017)
-------------------------
[GENERAL] Uses GZDoom's new lump filtering (makes editing of definitions for Plutonia/TNT needless)

Version 1.2 (Nov 16, 2016)
--------------------------
[GENERAL] Updated for compatibility with Doom Minor Sprite Fixing Project v1.8
[DOOM] Added brightmap for SSWVG5 (Wolfenstein SS firing/rear view)
[DOOM] Made spritefix versions of SKULA1 and SKULB1 (Lost Soul/front view) brighter

Version 1.01 (Jan 31, 2016)
---------------------------
[DOOM] Dead Cacodemon now without glowing eyes (brightmap for HEADK0 darker, HEADL0 removed)
[DOOM] Dead Mancubus now without glowing eyes (brightmap for FATTS0 darker, FATTT0 removed)

Version 1.0 (Jan 29, 2016)
--------------------------
[GENERAL] Initial release