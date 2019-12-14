# weplaydays-livonia
WePlayDayZ on Livonia's Server Files

# server-loot-root folder
These are the server files that get updated when DayZ releases a new update. 
Verify the information in the following files to ensure they are still to our hardcore standards.

- init.c
This file may change, so check the items a character gets when they spawn in under the StartingEquipSetup method

- cfgspawnabletypes.xml
This file controls what types of loot can spawn in each type. 
REMOVE ALL FOOD FROM ZOMBIE TYPES

- cfgrandompresets.xml
This file can also control the amount of loot that spawns. I stopped edited this one as much but it can be used if certain types of loot are spawning too much or not enough.

- db/types.xml
This file is the most important file in the loot economy. Controls how much of each type of loot will spawn, how many, how long they stay on the map, etc.

- db/globals.xml
Can use this file to edit some global variables. Check this file too just to make sure nothing looks different.

- db/events.xml
This file controls the number, min, max, and frequency of certain events, like domestic animals, xombies, etc. 
CHECK THIS FILE


