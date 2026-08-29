# BUKHORIY — CS2 CONFIG

Portable Counter-Strike 2 configuration for quickly restoring my setup on any PC or gaming club computer.

## Quick Setup

Download:

```text
bukhoriy.cfg
```

Put it here:

```text
...\Counter-Strike Global Offensive\game\csgo\cfg\
```

Launch CS2, open console with `~`, then run:

```text
exec bukhoriy
```

Done.

---

## My CS2 Settings

### Mouse

```text
Sensitivity: 0.90
```

> Mouse DPI must be set manually because DPI is controlled by the mouse/software, not CS2.

### Resolution

```text
1280 × 1024
```

### Video

```text
V-Sync: OFF
Low Latency: ON
```

### Viewmodel

```text
viewmodel_fov 68
```

The config also contains my:

* Crosshair
* Viewmodel
* Radar settings
* HUD settings
* Mouse sensitivity
* Keybinds
* Movement binds
* Audio settings
* FPS/gameplay settings

---

# Installation

## Method 1 — Gaming Club / New PC

### Step 1

Open Steam.

Go to:

```text
Library
→ Counter-Strike 2
→ Properties
→ Installed Files
→ Browse
```

### Step 2

Open:

```text
game
→ csgo
→ cfg
```

Usually:

```text
C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg
```

### Step 3

Download `bukhoriy.cfg` from this repository.

Move it into:

```text
game\csgo\cfg
```

### Step 4

Launch CS2.

Make sure Developer Console is enabled:

```text
Settings
→ Game
→ Enable Developer Console (~)
→ YES
```

### Step 5

Press:

```text
~
```

and enter:

```text
exec bukhoriy
```

The config should load immediately.

---

# Fastest Setup

For gaming clubs:

```text
Download bukhoriy.cfg
↓
Put in game\csgo\cfg
↓
Launch CS2
↓
Open console
↓
exec bukhoriy
```

---

# Repository Files

```text
bukhoriy-cs2-config/
│
├── bukhoriy.cfg
├── README.md
│
└── backup/
    ├── cs2_user_convars_0_slot0.vcfg
    ├── cs2_user_keys_0_slot0.vcfg
    ├── cs2_user_keys_0_slot1.vcfg
    ├── cs2_machine_convars.vcfg
    └── cs2_video.txt
```

## `bukhoriy.cfg`

This is the main portable config.

This is normally the only file I need when playing on another PC.

Run:

```text
exec bukhoriy
```

## `backup/`

Contains my original CS2 configuration files.

These are kept mainly for restoring settings if something gets lost or changed.

---

# What the CFG Restores

The portable config is intended to restore things such as:

```text
✓ Sensitivity
✓ Crosshair
✓ Viewmodel
✓ Radar
✓ HUD
✓ Keybinds
✓ Movement binds
✓ Audio settings
✓ Gameplay console variables
✓ FPS-related settings
```

---

# What Must Be Set Manually

Some settings are outside CS2 and therefore cannot reliably be restored through `bukhoriy.cfg`.

Check these when using a new gaming PC:

### Mouse

```text
DPI
Polling Rate
Windows mouse sensitivity
Enhance Pointer Precision
```

### Monitor

```text
Refresh Rate
Resolution / Scaling
```

### GPU

```text
NVIDIA Control Panel
AMD Adrenalin
Display scaling
Digital Vibrance
```

### Audio

```text
Headphones
Microphone
Windows volume
Audio device
```

---

# If The Config Doesn't Load

Make sure the filename is exactly:

```text
bukhoriy.cfg
```

Not:

```text
bukhoriy.cfg.txt
```

Windows can hide file extensions.

Then check that the file is inside:

```text
Counter-Strike Global Offensive\game\csgo\cfg
```

and run:

```text
exec bukhoriy
```

---

# If Console Is Disabled

Go to:

```text
Settings
→ Game
→ Enable Developer Console (~)
→ YES
```

Then press:

```text
~
```

---

# Full Restore

If I ever need to restore more than the portable CFG, the original CS2 files are stored inside the `backup` folder.

CS2 account configuration files are normally found under:

```text
Steam\userdata\STEAM_ID\730\local\cfg
```

Backup files can include:

```text
cs2_user_convars_0_slot0.vcfg
cs2_user_keys_0_slot0.vcfg
cs2_machine_convars.vcfg
cs2_video.txt
```

The portable `bukhoriy.cfg` is still preferred when using public or gaming-club PCs.

---

# Security

This repository contains **configuration files only**.

Never upload:

```text
Steam password
Steam Guard codes
API keys
Login cookies
Authentication tokens
Personal information
```

Since this repository is public, everything inside it can be viewed by anyone.

---

# One Command

```text
exec bukhoriy
```

---

## BUKHORIY

Personal CS2 setup.

Built for quickly getting my setup back on any PC.
