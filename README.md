# Multi1v1 Custom Health

[Allied modders thread](https://forums.alliedmods.net/showthread.php?t=315618)

Features:
  - Adds Multi1v1 round type which sets clients HP to the convar 'sm_1v1_hp_health'

ConVars:
  - sm_1v1_hp_enabled - [0 or 1] Enable / disable the round
  - sm_1v1_hp_health - [1 to 100] Health to set clients playing round to

Admin commands:
  - sm_1v1_hp_test - Set admins health to value of convar 'sm_1v1_hp_health'

Notes:
  - Requires multi1v1 plugin [Allied Modders](https://forums.alliedmods.net/showthread.php?t=241056) [Github](https://github.com/splewis/csgo-multi-1v1/)
  - After changing convar 'sm_1v1_hp_health' the name of the round will not update until both this plugin and multi1v1 plugin are reloaded

TODO:
  - Add variable health rounds (e.g. random health, multiple health settings)
  - Add proper config handling
  - Allow different weapons for round
