---
title: Redshift
---

# Redshift

A tiny, native macOS menu-bar app that warms, dims, and color-balances your display so your screen is easier on your eyes — especially in the evening.

Redshift lives quietly in the menu bar, uses a thin SwiftUI interface, and stays out of your way.

---

## Download

**[Download Redshift 0.1.0 (beta) — Redshift.dmg](https://github.com/movezig/releases/releases/download/redshift-v0.1.0-beta/Redshift.dmg)**

For other versions, see [all Redshift releases](https://github.com/movezig/releases/releases?q=redshift&expanded=true).

---

## What it does

- **Red Shift** — overlay a warm red tint to cut blue light.
- **Brightness** — dim the display below the system minimum if you want it even dimmer at night.
- **Channel Balancing** — fine-tune red, green, blue, and contrast individually.
- **Profiles** — save your favorite setups and recall them in one click.
- **Scheduler** — automatically fade between a Daytime and Evening profile at the times you choose.

Five built-in presets ship with the app: **Daytime**, **Afternoon**, **Sunset**, **Amber**, and **Campfire**.

## Requirements

- macOS 14 (Sonoma) or newer
- Apple Silicon Mac (M1/M2/M3/M4)
- **Screen Recording** permission — required to composite the overlay across all your displays. Redshift never records, stores, or transmits any screen content; the permission is used only to draw the tint locally.

## Installing

1. Click the download link above to get `Redshift.dmg`.
2. Open the DMG and drag **Redshift** to your Applications folder.
3. The first time you launch, macOS will say it can't verify the developer. **Right-click the app → Open**, then click **Open** in the dialog. (This is a one-time step — Redshift is not yet notarized during beta.)
4. macOS will ask for **Screen Recording** permission. Approve it in **System Settings → Privacy & Security → Screen Recording**, then relaunch the app.

Redshift has no Dock icon — look for its red/white circle in the **menu bar** at the top of the screen.

## Using it

Click the menu-bar icon to open the control panel.

- Drag **Red Shift** right to warm the screen.
- Drag **Brightness** left to dim further than the system allows.
- Open **Channel Balancing** for per-channel control.
- Tap any preset or saved profile to apply it instantly. Hit **Save as new profile** to store your current settings.
- Open the **Scheduler**, pick a Daytime and Evening profile, set the fade times, and flip the switch. Redshift will crossfade between them on its own — your sliders become read-only while the scheduler is active so nothing drifts by accident.
- Click the **×** in the top-left of the panel to quit.

## Privacy

Redshift is fully local. It does not phone home, collect analytics, or send any data anywhere. The Screen Recording permission is required by macOS for any app that draws over other apps' windows, but nothing about your screen ever leaves your Mac.

## Feedback

This is a beta. Bug reports and feature requests are welcome — email [benjamin.p.phillips@gmail.com](mailto:benjamin.p.phillips@gmail.com).

---

Copyright © 2026 Ben Phillips. All rights reserved.
