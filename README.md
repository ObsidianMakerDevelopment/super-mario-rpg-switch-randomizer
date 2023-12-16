# super-mario-rpg-switch-randomizer
Randomizer for the Super Mario RPG on switch

# Getting started

How To Install

Step 1: Download
Download from the GitHub repository <a href="https://github.com/ObsidianMakerDevelopment/super-mario-rpg-switch-randomizer" target="_blank">here</a>. Could also download precompiled exe in the Release section

Step 2: Extract Assets
The randomizer requires some assets from the game's RomFS to work. 
The root folder is the folder that contains the randomizer.exe
Put the dumped romfs next to the randomizer.exe file

Step 3: Done!
You should now be able to start randomizing if there are no errors in the randomizer app

Step 4:
Run Randomizer.exe 

Step 5:
Copy the romfs in the output directory to your emulator or modded switch.

# Video

Coming soon

# Thanks

Thanks github.com/bbowyersmyth/BinaryFormatDataStructure for the MS-NRBF reader.
We added writer support in their code.

# Support

You can support the creators via their twitch
[Takstijn](https://twitch.tv/takstijn) [ObsidianMaker](https://twitch.tv/ObsidianMaker)

# Modules
| Module | Description |
| ------ | ----------- |
| INITIALIZE | Change the default stats of characters when unlocked (Can be combined with SPECIALS to randomize specials moves) |
| SPECIALS | Change the characters SPECIALS moves, need LEVELUP or INITIALIZE to work |
| EQUIP | Change who can wear/equip weapons/armor/amulets |
| ITEMS | Change items stats, attack/defense |
| ITEMS_PRICE | Change item price in shops |
| TREASURE | Change the content of treasure chests |
| LEVELUP | Change the stats character gets after leveling up |
| ENCOUNTER | Change enemies encounters except story battles |
| SHOP | Change which items are in shops |
| CUTSCENES_R | Randomize cutscenes order |
| CUTSCENES_S | Changes all cutscenes to the shortest one |
| SHORT_TEXT | Change all character text to 'Tak' to have shorter text *Currently bugs out some part of the game |