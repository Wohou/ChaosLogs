# Chaos Tome Logs (MEGABONK)

**Summry:** A BepInEx mod that add to the *Shrine Logs* menu the chaos tome buff to keep a better track of the random but powerfull *Chaos Tome*

## Install
1. Copy `MegabonkChaosMods.dll` to `BepInEx/plugins/`.
2. Launch the game.

## How it works (in a nutshell)
- We keep track of the stats of the player.
- When "Chaos Tome" is detected we watch what values is changed and in which stat.
- We make the differnce (to get the value displayed at the end in the log).
- We watch the id of the stat (its name) in the Enum of all the stat.
- We put in in the "Shrine Logs".

Note : Some stat are a percentage (%) and some are juste addition (+), for that I've had no choice but hardcoding it by checking all the stat one by one and see if it's a additionnal value or a percentage given.
