# Doki-Doki-Literature-Club-Vita
Vita Specific Patches and Application for Doki Doki Literature Club (Steam Version) using Ren'Py PSVita

## Contains:
- Modified Singleton.py for the Vita
- Performance patch for Act 3 (Just Monika)

# Installation Instructions
pre-req: rePatch-reLoaded (Tested) or FDFix (Not Tested)
1. Download the VPK and install
2. Install Doki Doki Literature Club on Steam (It's free)"
3. Right Click DDLC in your Steam Library and navigate to `Manage -> Browse Local Files`
4. Copy the `characters` Folder to `ux0:app/RNPYDDLC1`
5. Copy `firstrun`, `audio.rpa`, `fonts.rpa`, and `images.rpa` to `ux0:app/RNPYDDLC1/game`<br>(DO NOT JUST COPY THE GAME FOLDER. This will work for other games, but DDLC is different)<br>(DO NOT copy `scripts.rpa` if you want the performance patch)
6. Run Doki Doki Literature Club on the Vita (Initial load can take up to a minute)

## How to Delete Characters
Well, uh, you copied the folder. Just delete the characters, dummy. It's just like the PC version ;)

## Restarting after completion
The game will still remain in an "unplayable" state when you beat it (just like on PC). All you have to do to reset it is delete the `firstrun` file, then restart.<br>The game will prompt you to delete savedata, then it should reset and start fresh.

## Modding
Installing mods (that don't include extra python modules) with this is as simple as dragging and dropping, just like on desktop versions of DDLC. It's running the same version of Ren'Py.

## Cool Quirk
Ren'Py directory scanning is also included (again, just like on PC).<br>So if you have an always on background FTP plugin like Vitacompanion or Ftpeverywhere, you can delete some files and watch the game react accordingly (hint hint, Just Monika).

## Known Issues
The game WILL hitch when loading new assets that aren't in Cache. This isn't something I can fix and is sadly a hardware limitation.<br>The Vita's IO is too slow to handle loading most assets on a whim. Some games use preloading to get around this. DDLC does not.

## Want to build it yourself?
Use these files and then use the [Ren'Py PSVita Distribution Tool](https://github.com/SonicMastr/Renpy-PSVita-Distribution-Tool) to create your own VPK (Can even be used to distribute your own Ren'Py Projects!)

## Ren'Py Vita
This port uses Ren'Py Vita. If you would like to contribute to this project, you can do so [at my github repo](https://github.com/SonicMastr/renpy-vita)
