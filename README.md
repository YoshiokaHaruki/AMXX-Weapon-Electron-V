# AMXX Weapon Electron-V
Weapon Electron-V from Counter-Strike: Online for Counter-Strike 1.6 (based on AMX Mod X)

About this weapon: [Link](https://cso.fandom.com/wiki/Electron-V)

---
### Demo Video
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/PPGSPTbuCkI/0.jpg)](https://youtu.be/PPGSPTbuCkI)

---
### Requirements
ReAPI version:
- ReHLDS, ReGameDLL, Metamod-R (or Metamod-P), AMX Mod X, ReAPI.

Non-ReAPI version:
- HLDS, Metamod (or Metamod-P), AMX Mod X

❗ Tip: Recommend using the latest versions.

---
### Install
- Pull all resources from the `extra` folder and move them to your server folder `cstrike`
- Pull all files from the `source` folder and move them to the `scripting` folder
- Open the file `zp_weapon_lightningar.sma` and configure it
  * **NB!** If your server does not support Re modules, find the line #include <reapi> and you should delete it or turn it off (using //)
  ```Pawn
  // #include <reapi>
  ```
- Compile `zp_weapon_lightningar.sma` file
- Compiled plugin, put it in the `plugins` folder on your server

---
### For using custom MuzzleFlash, Smoke WallPuff and Player Weapon Model (p_ submodel)
- Download [API MuzzleFlash](https://github.com/YoshiokaHaruki/AMXX-API-Muzzle-Flash)
- Download [API Smoke WallPuff](https://github.com/YoshiokaHaruki/AMXX-API-Smoke-WallPuff)
- Download [API Weapon Player Model](https://github.com/YoshiokaHaruki/AMXX-API-Weapon-Player-Model/)

**If you don't want to use the API, just find these lines:**
```Pawn
#include <api_muzzleflash>
#include <api_smokewallpuff>
#include <api_weapon_player_model>
```
**and delete or comment this lines, like this:**
```Pawn
// #include <api_muzzleflash>
// #include <api_smokewallpuff>
// #include <api_weapon_player_model>
```
