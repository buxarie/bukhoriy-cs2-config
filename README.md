# BUKHORIY CS2 CONFIG

My personal Counter-Strike 2 config for quickly restoring my settings on different PCs and gaming clubs.

## Main Settings

* Sensitivity: `0.90`
* Resolution: `1280x1024`
* V-Sync: `Off`
* Low Latency: `On`
* Viewmodel FOV: `68`
* Custom crosshair
* Custom radar/HUD
* Custom keybinds
* Custom audio settings

## Installation

### 1. Download

Download:

```text
bukhoriy.cfg
```

### 2. Open the CS2 folder

Steam:

```text
CS2 → Properties → Installed Files → Browse
```

Then go to:

```text
game\csgo\cfg
```

Full default location:

```text
C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg
```

### 3. Put the config there

Copy:

```text
bukhoriy.cfg
```

into the `cfg` folder.

### 4. Launch CS2

Enable Developer Console if needed:

```text
Settings → Game → Enable Developer Console → Yes
```

Open the console with:

```text
~
```

Then type:

```text
exec bukhoriy
```

If successfully loaded, the console should show:

```text
BUKHORIY PORTABLE CONFIG LOADED
```

## Gaming Club Setup

When using a new PC:

```text
1. Download bukhoriy.cfg
2. Put it inside game\csgo\cfg
3. Launch CS2
4. Open console
5. exec bukhoriy
6. Set mouse DPI manually
```

## Important

The config restores CS2 settings, but some hardware settings still need to be configured manually.

For example:

* Mouse DPI
* Monitor refresh rate
* NVIDIA/AMD settings
* Windows mouse settings
* Audio device
* Microphone device

## Backup Files

This repository may also contain my original CS2 configuration files:

```text
cs2_user_convars_0_slot0.vcfg
cs2_user_keys_0_slot0.vcfg
cs2_machine_convars.vcfg
cs2_video.txt
```

These are kept as backups.

For normal use, only this file is required:

```text
bukhoriy.cfg
```

## Quick Command

```text
exec bukhoriy
```

---

BUKHORIY CS2 CONFIG
