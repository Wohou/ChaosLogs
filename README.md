# Chaos Tome Logs (MEGABONK)

**Summary:** A BepInEx mod that adds the Chaos Tome buff to the *Shrine Logs* menu so you can better track the random but powerful *Chaos Tome*.

## Install
1. Copy `ChaosLogs` folder to `BepInEx/plugins/`.
2. Launch the game.

## How it works (in a nutshell)
- We track the player's stats.
- When a "Chaos Tome" is detected, we monitor which values changed and which stat was affected.
- We calculate the difference so the change can be shown in the log.
- We look up the stat's ID (its name) in the enum of all stats.
- We add the result to the "Shrine Logs".

Note: Some stats are percentages (%) while others are simple additions (+). To handle this, I hardcoded checks for each stat to determine whether the change is additive or a percentage.

```
I'm working on a way to add "(Chaos)" next to the stat name in the Shrine Logs for better clarity.
```

## Contact
*Discord id* : 199987125859516416

Thanks you !
