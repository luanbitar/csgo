## Scripts

| Config file          | Description                          |
| -------------------- | ------------------------------------ |
| `main.cfg`           | Loads all default binds and configs  |
| `grenades.cfg`       | Used when I need to train grenades   |
| `demo.cfg`           | Binds to control replay in demo play |
| `crosshair[...].cfg` | Different types of crosshair         |

## Video config to improve visibility

| Config option         | Value     |
| --------------------- | --------- |
| global shadow quality | `MEDIUM`  |
| effect detai          | `HIGH`    |
| shader detail         | `HIGH`    |
| boost player contrast | `ENABLED` |
| multisampling         | `2x`      |

## Startup options

```
-freq 240 -refresh 240 -novid -tickrate 128 -high -maxplayers_override 50 +exec config/main -console +mat_disable_fancy_blending 1 +cl_show_team_equipment +mat_queue_mode 2 +cl_forcepreload 1 -softparticlesdefaultoff
```

## Add config folder

- cd C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg\
- git clone git@github.com:luanbitar/csgo.git
