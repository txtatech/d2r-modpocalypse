# d2r-modpocalypse

A repository for Diablo II: Resurrected modding information.

**Preamble:**

This repository is not intended to be a comprehensive modding guide and is more a collection of notes and useful information.

If you are looking for comprehensive guides and/or examples check out the following sites:

HighTechLowIQ D2R Modding:
https://github.com/HighTechLowIQ/ModdingDiablo2Resurrected

Bonesy D2R Modding Video Guides:
https://www.youtube.com/@locbones1

D2R Modding Resource Site:
https://www.d2rmodding.com/

The Phrozen Keep (D2R Discussion Thread)
https://d2mods.info/forum/viewforum.php?f=217

Nexusmods (D2R Section):
https://www.nexusmods.com/diablo2resurrected

## **GETTING STARTED**

There are several ways to mod but my prefered method is with .mpq files so I will focus on that method alone.

**Step: 1:** Get a copy of CascView and extract the game files. [Guide](https://www.reddit.com/r/Diablo/comments/pv8pot/d2r_modding_guide/) [Video Guide](https://www.youtube.com/watch?v=lZTTq7MXZ5w) At time 1 minute 55 seconds.

http://www.zezula.net/en/casc/main.html

**Step 2:** Get a copy of Ladik's MPQ Editor.

There are a few versions of it and some are much better than others.

Version 4.0.0.871 (Unicode Build) that uses StormLib v 9.23 works well for me.

http://zezula.net/en/mpq/download.html

**Step 3:** Open a .json file in a text editor and start modding!

## **References & File Locations:**

**The official Diablo II Data File Guide:** (Note this is mainly for making excel edits.)

data/global/excel/_diabloiidatafileguide.mht

**HD & SD user interface data:**

data/global/ui/layouts

Copyrights
Diablo II and Diablo II: Resurrected are copyrighted by Blizzard Entertainment, Inc. All rights reserved. Diablo II, Diablo II: Resurrected and Blizzard Entertainment are trademarks or registered trademarks of Blizzard Entertainment, Inc. in the U.S. and/or other countries.
All trademarks referenced here are the properties of their respective owners.

Note: For the sake of convenience some text files and dc6 image files that gomule requires are provided in the resources directory. These files are part of the Diablo II game series and are copyrighted by Blizzard Entertainment. They are provided only to save you the trouble of extracting them from the Diablo II game files. If you did not purchase a copy of Diablo II and Diablo II: Resurrected be advised that you may not have perimission to use these files.

This project and its maintainers are not associated with or endorsed by Blizzard Entertainment, Inc.
**HD graphics:**

data/global/hd

**SD graphics:**

data/global

**HD & SD Excel data:**

data/global/excel

**Localized data, utilized by HD & SD:**

data/local/lng

**The following example is from one of the .json files:**

"filename": "FrontEnd\\HD\\Final\\FrontEnd_ButtonMed",

*The above location would resolve to the following location:*

"C:\data\hd\global\ui\frontend\hd\final\frontend_buttonmed.sprite" (Note: the 'data' folder is located wherever you extract the game files to.)

**Misc:**

Online character editor:

https://d2s.dschu012.dev/


More to be added...
