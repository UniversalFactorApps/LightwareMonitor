wait# Lightware Monitor

# Lightware Monitor

A lightweight, always-on-top hardware monitoring overlay for Windows gamers.

Displays real-time **CPU usage**, **GPU temperature**, and **FPS** directly on your screen — even inside fullscreen games.

---

## Features

### Free (no license required)

| Feature | Description |
|---|---|
| **Real-time telemetry** | CPU usage (%) and GPU temperature (°C) updated every second via a native C++ engine |
| **FPS overlay** | Uses Windows ETW (PresentMon) to display in-game FPS when a known game is in the foreground |
| **Game detection** | Automatically detects 100+ popular games and shows the game name above the metrics |
| **Always-on-top** | Overlay stays above fullscreen games and applications |
| **Click-through mode** | Overlay ignores mouse input so it never steals focus from your game |
| **Mini mode** | Compact 340×45 bar that shows just FPS; toggle with double-click or tray menu |
| **Auto-hide when idle** | Overlay fades out when you're not in a game — no clutter on the desktop |
| **Unlock shortcut** | Hold `Left Ctrl` + `Left Shift` to unlock the overlay for dragging, resizing, or closing |
| **Touch-and-hold (handheld)** | Press and hold the overlay for 1.5s to unlock — perfect for Steam Deck and handhelds |
| **4 color themes** | Cyberpunk Neon, Stealth White, Crimson Fury, Aurora Green |
| **4 font sizes** | Small (16px), Medium (22px), Large (28px), Extra Large (34px) |
| **Multi-monitor** | Choose which monitor the overlay appears on |
| **Persisted settings** | Position, size, theme, and mode survive restarts |
| **Launch on star

---

### Premium (license key required)

Unlock premium features at **[lightwaremonitor.com/premium](https://lightwaremonitor.com)**.

> **License key activation** — Enter your key from the tray menu to unlock premium. The activation is tied to your machine and validated online against Keygen.sh with a 7-day offline grace period.

| Feature | Description |
|---|---|
| **4 additional color themes** | Dark, Cold, Neon, Pastel |

---

![Lightware Monitor demo](demo.gif)

_Lightware Monitor running over a game — real-time CPU, GPU temperature, FPS, and game name._

### Built-in themes

![Cyberpunk Neon](theme-cyberpunk-neon.png)
![Stealth White](theme-stealth-white.png)
![Crimson Fury](theme-crimson-fury.png)
![Aurora Green](theme-aurora-green.png)

---

## Installation

### Option 1: Installer (Recommended)
Download the latest `LightwareMonitor-Setup-x.x.x.exe` from the [Releases](https://github.com/UniversalFactorApps/LightwareMonitor/releases) page and run it.

### Option 2: Portable
Download `LightwareMonitor-Portable-x.x.x.zip`, extract anywhere, and run `LightwareMonitor.UI.exe`.

### Option 3: winget
winget install UniversalFactorApps.LightwareMonitor


Quick Start

1. Launch Lightware Monitor
2. The overlay appears at the top-left of your primary monitor
3. Play your game — the overlay stays on top and shows CPU, GPU temp, and FPS
4. Hold Left Ctrl + Left Shift simultaneously to unlock the overlay (enables dragging, resizing, and the close button)
5. Right-click the tray icon to switch themes, toggle mini mode, manage your license, or reset settings

---

Keyboard Shortcuts

┌───────────────────────────┬──────────────────────────────────────────┐
│          Action           │                   How                    │
├───────────────────────────┼──────────────────────────────────────────┤
│ Unlock overlay            │ Hold Left Ctrl + Left Shift              │
├───────────────────────────┼──────────────────────────────────────────┤
│ Toggle mini mode          │ Double-click the overlay (when unlocked) │
├───────────────────────────┼──────────────────────────────────────────┤
│ Touch-and-hold (handheld) │ Press and hold overlay for 1.5s          │
└───────────────────────────┴──────────────────────────────────────────┘

---

System Requirements

┌──────────────┬──────────────────────────────────┐
│              │                                  │
├──────────────┼──────────────────────────────────┤
│ OS           │ Windows 10 (1809+) or Windows 11 │
├──────────────┼──────────────────────────────────┤
│ Architecture │ x64                              │
├──────────────┼──────────────────────────────────┤
│ Dependencies │ None (self-contained)            │
├──────────────┼──────────────────────────────────┤
│ Admin rights │ Not required                     │
└──────────────┴──────────────────────────────────┘

---

Privacy

Lightware Monitor does not collect any data. telemetry, no analytics, no network requests — except for license activation and verification via Keygen.sh (https://keygen.sh) when a premium license key is entered.

---

License

This is a proprietary, closed-source application. See LICENSE for the full end user license agreement (EULA). The
premium features are licensed separately und PREMIUM.md.

---

Support

For issues or questions, open an issue on this repository.
