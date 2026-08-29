BUKHORIY CS2 PORTABLE PACK
==========================

FASTEST GAME-CLUB METHOD

1. Keep this ZIP in Telegram Saved Messages, Google Drive, Dropbox, or GitHub.
2. On the gaming-club PC, unzip it.
3. In Steam: CS2 -> Properties -> Installed Files -> Browse.
4. Open:
   game\csgo\cfg
5. Copy bukhoriy.cfg into that folder.
6. Launch CS2.
7. Enable Developer Console if needed.
8. Open console and type:

   exec bukhoriy

9. Look for:
   BUKHORIY PORTABLE CONFIG LOADED

10. Set your mouse DPI manually. A CS2 cfg cannot set the physical mouse DPI.
11. Set the video options using VIDEO_REFERENCE.txt.

OPTIONAL
Add this Steam launch option if you want the file to execute automatically:

   +exec bukhoriy.cfg

WHAT I FIXED / CLEANED
- Fixed the broken D bind from the old bukhriy.cfg (it had an extra |).
- Added sensitivity 0.9.
- Added the full crosshair values from your user convars.
- Added radar, HUD, telemetry, audio, FPS/network and gameplay values.
- Removed the old cl_interp_ratio tweak instead of forcing an obsolete-style
  CS:GO networking setting in CS2.
- Did NOT copy the hardware-specific microphone device override.
- Did NOT force GPU VendorID/DeviceID from your current computer.
- Did NOT preserve the undefined MOUSE4 command "jbn" because no matching
  alias/command was present in the uploaded config.
- Did NOT carry over ENTER/BACKSPACE/DEL workshop/practice-map ent_fire binds,
  because they can interfere on normal PCs/maps.

FULL_RAW_BACKUP
The FULL_RAW_BACKUP folder contains the exact files you uploaded. Keep these
for archival purposes. For gaming-club use, bukhoriy.cfg is the recommended
portable file.
