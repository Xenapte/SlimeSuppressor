# SlimeSuppressor

A plugin that suppresses/disables slime spawning in slime chunks. Potentially very useful in superflat worlds.

Note: other slime spawns (those spawning in swamps or splitting from previously killed ones) will not be affected.

## Requirement

This plugin requires **1.16.4/1.16.5 Spigot** servers (forks such as Paper are fine). 

## Configuration

***WIP***. For plugin configuration, see [**config.yml**](src/main/resources/config.yml).

Note: "slime-spawning-enabled" will override "slime-spawn-chance". If the former is set to false then slimes will not spawn at all no matter how the latter is set.

## Commands

- `/slime`: get current status.
- `/slime <enable|disable>`: pretty self-explanatory.
- `/slime set <chance>`: set the slime spawn chance.
