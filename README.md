# TLD Revival

**Smooth multiplayer, bug fixes and a working mod browser for The Long Drive (public build v2023.05.02d).**

The Long Drive's public build has multiplayer, but it is held back by rubber-banding, desync and bugs, and many community mods stopped working on this version. TLD Revival fixes the multiplayer, fixes bugs in the game itself, and lets you browse and install the community mods from inside the game. Old mods are repaired automatically so they run on this version.

---

## Features

### Multiplayer that actually works
- **Steam invites.** Press Esc → **Invite friends** and pick them in Steam's invite window. Friends accept the invite, or right-click you in their Steam friends list → **Join Game**. No lobby screens needed.
- **Everyone on the same version, automatically.** A friend who joins with an older TLD Revival gets yours from your game. Releases also download by themselves at the main menu, and every file is checked against the release signature.
- **Everyone on the same mods.** If a friend's mods differ, **Join & match** sends them your exact mods from your game and switches off theirs that you don't use. Nothing is deleted, and **Restore my mods** brings theirs back.
- **No more rubber-banding.** Whoever drives a vehicle controls it, and everyone else sees it move smoothly. In testing, remote cars stayed within about 5–30 cm of their real position, with no teleporting, even on a simulated bad connection.
- **Several drivers at once.** Every player can drive their own car at the same time without things falling apart.
- **Creatures that match on every screen.** Each animal and enemy is simulated by the nearest player, and everyone else sees the same animal in the same place.
- **No more launches.** Fixes players and cars being thrown into the air when someone gets in, gets out or hands an item over.
- **Pausing and sleeping don't freeze everyone.** The world keeps running while one player is in the menu.
- **Joining fixes.** Guests no longer get duplicate loot, drop through the world, or watch cars vanish when someone leaves.
- **Hoarders welcome.** Tested with hundreds of loose parts in the world: everyone sees every item where it really is.
- **Same world for everyone.** Roadside and road pieces look the same on every screen, and if a mod makes a friend's roads differ from yours, they're told how to fix it.
- **Guests use fuel too.** In the base game a guest's car never used fuel.

### Quality of life
- **Names above your friends**, with their distance when they're far away.
- **Arrows at the edge of the screen** pointing to friends who are out of sight.
- **Player list** (hold F1) with ping, distance, and whether each player is on foot or in a vehicle.
- **"Go to"**: jump next to a friend when you've driven apart. The host can switch this off.
- **Join and leave notes** in the corner of the screen.
- **Automatic save backups**: every save is copied (the last 10 of each), and you can restore one from the menu.
- **Mods on and off** from the Mods tab, without deleting anything.
- **Menus that fit the game.** Everything uses The Long Drive's own buttons, paper and sounds.
- **Automatic updates.** New versions download themselves and are used after a restart. Every update is digitally signed, and the mod refuses anything that isn't a genuine release.

### Mod browser
- **198 community mods** listed in-game, with pictures, descriptions and compatibility for this version.
- **195 of them run** on this version without errors. Each one was tested in the real game.
- **Old mods are repaired on install.** Mods made for other game versions are rewritten so they run here.
- **Dependencies install automatically**, and mods that conflict with each other are flagged.
- **Malware check.** Every listed mod was scanned. A download that differs from the scanned version asks before installing. Scanning lowers the risk but can't guarantee a mod is safe, because mods run with the same rights as the game.
- **Mods in sessions.** When you join a game, your mods are compared with the host's, and you can install whatever you're missing.

### Bug fixes for the game itself
- **Falling through the map** after loading a save.
- **Errors on every world unload**, and errors when joining.
- **Car parts exploding off** after crashes.
- **Radio errors** with mod-added songs.
- **Fuel calculation bug** that could make cars weigh 1 kg.
- **…and more**, plus runtime fixes for 11 popular mods.

---

## Installation

1. **Set the branch.** In Steam, make sure The Long Drive is on the normal (public) branch: Properties → Betas → None.
2. **Run the installer.** Run **TLD Revival Setup.exe** and click **Install**. It finds the game automatically, backs up the one game file it changes, and installs the TLDLoader mod loader along with TLD Revival.
3. **Play.** Start the game from Steam as usual. You'll see a **Mods** button on the main menu.

**Uninstalling:** run the setup again and click **Uninstall**. Your saves and other mods are not touched. You can also restore the original game files with Steam's "Verify integrity of game files".

**Playing together:** everyone needs TLD Revival installed once. After that, versions and mods sync by themselves. The host starts or loads a game, presses Esc and clicks **Invite friends**. Friends accept the Steam invite or use **Join Game** from the Steam friends list. The game's own lobby screen (Esc → Multiplayer) still works too.

---

## Keys
| Key | Action |
|---|---|
| Ctrl+Shift+M | TLD Revival menu (or the Mods button) |
| Esc → Invite friends | Open your game to friends (Steam invite) |
| F1 (hold) | Player list (multiplayer) |
| Ctrl+Shift+D | Network/debug overlay |

## Compatibility and requirements
- The Long Drive **v2023.05.02d** (Steam public branch), Windows.
- Uses the community mod loader **TLDLoader 3.0.2** (included; GPL-3.0, by KolbenLP).
- Other TLDLoader mods keep working. The newer beta builds of the game are not supported.

## Known limitations
- Mods that spawn their own traffic or vehicles (for example AI Traffic) run separately on each player's game, so friends can see different AI cars.
- Some antivirus programs and Windows SmartScreen warn about unsigned installers that modify game files. TLD Revival only changes Assembly-CSharp.dll, and it keeps a backup.

## Reporting problems
Open **Mods → About → Create problem report** in the game. It makes a zip of the session logs to attach to your report. Your Windows user name, Steam IDs and player names are replaced with placeholders before anything is zipped.

## Credits
- **TLDLoader** by KolbenLP and contributors.
- **Harmony** by Andreas Pardeike (MIT).
- **Mono.Cecil** by Jb Evain (MIT).
- **Community mod authors.** Their mods are downloaded from their original links; TLD Revival doesn't re-host them.
- **The Long Drive** by Genesz. TLD Revival is an unofficial fan mod and is not affiliated with or endorsed by the developer.


---
**Download:** grab `TLDRevivalSetup.exe` from the [latest release](https://github.com/BLUNT-Chief/TLD-Revival/releases/latest) and run it.
