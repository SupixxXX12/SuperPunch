<div align="center">
  <img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/1174180/header.jpg?t=1759502961" alt="SuperPunch header" width="100%">
  <br>
  <a href="https://github.com/SupixxXX12/SuperPunch/releases"><img src="https://img.shields.io/badge/Download-Releases-c9783f?style=for-the-badge&logo=github&logoColor=white" alt="Get SuperPunch from Releases"></a>
  <a href="https://www.nexusmods.com/reddeadredemption2/mods/56"><img src="https://img.shields.io/badge/Required-ScriptHookRDR2-8b5a36?style=for-the-badge" alt="ScriptHookRDR2 requirement"></a>
  <br><br>
  <strong>A Story Mode-only RDR2 ASI mod for over-the-top punches, cinematic follow cam, custom effects, and more.</strong>
  <br><br>
  <a href="#features">Features</a> · <a href="#requirements">Requirements</a> · <a href="#installation-guide">Installation guide</a> · <a href="#important-notes">Important notes</a>
</div>

---

## The experience

SuperPunch gives fistfights a bigger, more cinematic feel in Red Dead Redemption 2 Story Mode. It combines exaggerated punch action, a cinematic follow camera, and custom effects to make each encounter feel larger than life.

> [!WARNING]
> Story Mode only. Do not use SuperPunch in Red Dead Online. The mod automatically disables itself when you connect to Online, but it is not an Online mod. Do not rely on that behavior as a substitute for keeping mods out of Online.

## Mod menu preview

A look at the in-game SuperPunch menu. The preview shows the available adjustments and toggles. Experimental options are labeled in the menu.

<div align="center">
  <img src="https://i.postimg.cc/HsPsDz3t/Screenshot-(87).png" alt="SuperPunch in-game mod menu preview" width="100%">
</div>

## Features

| Feature | What it adds |
| --- | --- |
| **Over-the-top punches** | Turns fistfights into exaggerated, high-impact brawling moments. |
| **Cinematic follow cam** | Adds a dramatic camera feel that follows the action during fights. |
| **Custom effects** | Brings extra visual flair to the mod's punch moments. |
| **Adjustable launch distance** | Lets you adjust how far a punch sends an opponent. |
| **Upward lift ratio** | Adjusts the upward lift during a punch. |
| **Extra damage** | Lets you tune the impact of punches. |
| **Ragdoll duration** | Adjusts how long an opponent remains in a ragdoll state. |
| **Custom VFX toggle** | Enables or disables the custom visual effects. |
| **Yeet Camera toggle** | Enables or disables the cinematic follow camera. |
| **Experimental options** | Includes experimental features marked as such in the menu. Use them at your discretion. |
| **Reset defaults** | Restores the menu's default values for the current session. |

SuperPunch's implementation is private. This page describes the player-facing experience and does not document internal code or implementation details.

## Requirements

Install these before adding SuperPunch:

1. Red Dead Redemption 2 for PC, with access to the game's main folder, the folder containing `RDR2.exe`.
2. One ScriptHookRDR2 option:
   - [ScriptHookRDR2 by Alexander Blade](http://www.dev-c.com/rdr2/scripthookrdr2/). The normal package includes the ASI loader, `dinput8.dll`.
   - [ScriptHookRDR2 V2 on Nexus Mods](https://www.nexusmods.com/reddeadredemption2/mods/1472). V2 does not include the ASI loader. If you choose V2, you still need a compatible `dinput8.dll` ASI loader.
3. `dinput8.dll` ASI loader. This is required to load ASI mods. The normal ScriptHookRDR2 package includes it. If using V2, obtain the loader separately. Do not replace one ScriptHook version's files with another version's files unless their instructions require it.
4. The latest `SuperPunch.asi` file, downloaded from the [SuperPunch Releases page](https://github.com/SupixxXX12/SuperPunch/releases).

> [!IMPORTANT]
> The `dinput8.dll` ASI loader is included with the normal ScriptHookRDR2 package, but not with ScriptHookRDR2 V2. `dinput8.dll` is required either way. Check the ScriptHook instructions and release notes for compatibility with your game version.

## Installation guide

1. Back up your game folder or note which mod files are already installed. This makes it easier to undo changes if something does not work.
2. Install one ScriptHook option. Follow the instructions included with the version you chose and place its required files in the game's main folder, beside `RDR2.exe`.
3. Confirm the ASI loader is present. Make sure `dinput8.dll` is in the game's main folder. With normal ScriptHookRDR2, use the loader included in its package. With V2, install a compatible loader separately.
4. Download the latest SuperPunch release. Get `SuperPunch.asi` from the [Releases page](https://github.com/SupixxXX12/SuperPunch/releases). If no downloadable release is listed, a build has not been published on this page yet.
5. Install SuperPunch. Copy `SuperPunch.asi` into the game's main folder, beside `RDR2.exe` and `dinput8.dll`.
6. Launch Story Mode and test. If the game does not start or the mod does not load, remove `SuperPunch.asi` first, then check that the ScriptHook files and loader match their own installation instructions and your game version.
7. Keep the setup Story Mode-only. Before starting Online, make sure your mod setup is not active. SuperPunch disables itself when you connect to Online, but other mods are not managed by SuperPunch.

### Quick folder check

Your game folder should contain the required ScriptHook files, the ASI loader, and `SuperPunch.asi`. The exact ScriptHook files depend on the version you chose.

```text
Red Dead Redemption 2 game folder/
├── RDR2.exe
├── ScriptHookRDR2.dll        (from your chosen ScriptHook package)
├── dinput8.dll               (ASI loader, required)
└── SuperPunch.asi            (latest release)
```

Do not install both ScriptHook versions on top of each other. Follow the documentation supplied with the ScriptHook package you selected.

## Releases

Download the newest `SuperPunch.asi` from [GitHub Releases](https://github.com/SupixxXX12/SuperPunch/releases). Always read the release notes and use the most recent version. If the Releases page does not show a downloadable build, please check back later.

## Important notes

- Story Mode only. SuperPunch automatically disables itself when you connect to Online. This is not a guarantee of Online compatibility, so do not use it there.
- Other mods are unaffected. SuperPunch does not remove or manage other mods. You may need to manually move other mod files out of the game's folder when troubleshooting or preparing a clean setup.
- Settings are not saved yet. SuperPunch currently has no save-settings system. You need to adjust your settings manually each session. A save-settings feature is planned for a future update when development time allows.
- Closed-source project. The SuperPunch source code and `.cpp` files are not included or documented here. Only the released mod file is distributed through Releases.
- Back up your files. Mod compatibility can vary with game updates and other installed mods. Keep a clean backup of the game's original files.

## Troubleshooting

- The mod does not load: verify that `dinput8.dll` is in the same folder as `RDR2.exe`, and that `SuperPunch.asi` is the latest release.
- You installed ScriptHookRDR2 V2: remember that V2 does not include the ASI loader. Install a compatible `dinput8.dll` separately.
- The game has problems after installing: temporarily remove `SuperPunch.asi` and test the game. If needed, also review other installed mods and the ScriptHook instructions.
- A game update broke compatibility: check the ScriptHook page and the SuperPunch Releases page for updated compatibility information.

## Credits and links

- [ScriptHookRDR2 by Alexander Blade](http://www.dev-c.com/rdr2/scripthookrdr2/)
- [ScriptHookRDR2 V2 on Nexus Mods](https://www.nexusmods.com/reddeadredemption2/mods/1472)
- [SuperPunch Releases](https://github.com/SupixxXX12/SuperPunch/releases)

---

<div align="center">
  <sub>Made for cinematic chaos in the frontier. Story Mode only.</sub>
</div>
