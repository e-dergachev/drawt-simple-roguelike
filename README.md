It's a simple roguelike that I have made a few years ago. I leave its source code here as it was originally written, it's written in C, and even despite all the source code was put into a single file, I hope the code composition should be pretty clear to read, the code was also richly commented.

The game has no dependencies and should work on every 80x24 terminal which supports ANSI color codes. In order to compile the game for Linux, you can use the following command: 'gcc drawt.c -o drawt -std=c99'. In order to compile the game for Windows, you should use cygwin with the same command as above. Windows binary (when it's used outside of cygwin) needs cygwin1.dll to be placed into the game folder to be able to work. The game is licensed under GNU GPL.

The goal of the game is to slay the dragon which awaits you on the deepest level. Your character has no natural health regeneration and your only means to survive is healing potions which you can find everywhere. As any roguelike this game has random level layouts, permadeath, randomized weapon, many kinds of monsters, several kinds of consumables and traps. It also has a basic save & load feature. The turn system is quite simple - every your action takes one turn and then your enemy gets its turn, all the turns are considered to take the same time. The sight system is basic, every room is considered to be fully lit, the monster's pathfinding is basic as well - they simply beeline to you. Since it's alpha it is not really balanced that well too.

Here are some game screenshots:

The game intro:

[placehgolder for intro]

Game controls and other instructions:

[placehgolder for controls]

A battle in the dungeon:

[placeholder for battle]

A menu to pick items from the ground:

[placeholder for picking items]

A log of events:

[placeholder for events log]
