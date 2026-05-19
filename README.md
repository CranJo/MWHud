# 🎨 MWHud — Customizable HUD for Minecraft

A feature-rich, highly customizable HUD mod for Fabric that brings your server's essential stats right onto your screen — in real-time, beautifully styled, and fully draggable.

---

## 📖 About

**MWHud** is a Fabric client-side mod that pairs with the **MWHud Plugin** (Paper/Spigot) to push real-time server statistics directly to your HUD — no commands, no menus, no scoreboard clutter.

The plugin collects data through PlaceholderAPI and sends it to connected clients over a custom network channel. The mod receives it and renders it as a fully customizable overlay: drag it anywhere, style it your way, and save your layout as a preset.

Whether you're tracking your balance, watching your fly timer count down, or keeping an eye on the Envoy cooldown, it's all right there on your screen.

---

## ✨ Features

### 🖥️ HUD Display Elements

| Element | Description | Requires Plugin |
|---------|-------------|:---:|
| 💰 **Money** | Your current balance | ✅ |
| 🪙 **Mobcoins** | Your mobcoin balance | ✅ |
| 🕊️ **Fly Time** | Remaining flight duration countdown | ✅ |
| 🧱 **Claim Blocks** | Remaining GriefPrevention claim blocks | ✅ |
| ⚔️ **PvP Status** | Whether PvP is enabled or disabled | ✅ |
| 📦 **Envoy Timer** | Countdown to the next Envoy event | ✅ |
| 🔑 **Key-for-all Timer** | Countdown to the next Key-for-all drop | ✅ |
| 🎉 **Party Key** | Current / required votes for a Vote Party | ✅ |
| 📶 **Ping** | Your live connection latency | ❌ |
| 👥 **Online Players** | Current server player count | ✅ |
| 🏷️ **Server Title** | A custom server name shown on-screen | ✅ |

> **Ping** is read directly from the Minecraft client — no plugin needed.

---

### 🎨 Customization

| Option | Details |
|--------|---------|
| **16 Box Shapes** | Plain Box, Pill, Accent Bar, Text Only, Bottom Line, Corner Brackets, Tag/Flag, Outline Text — plus 8 split variants with ghost/pill modes |
| **15 Colors** | White, Light Grey, Grey, Black, Green, Dark Green, Gold, Yellow, Cyan, Blue, Light Blue, Purple, Red, Orange, Pink |
| **Server Color Sync** | Auto-matches box colors to whatever the server sends; one-click reset |
| **Per-box Control** | Cycle value color, box shape, and label color independently per element |
| **Drag & Drop** | Freely reposition any box; smart snapping to edges, alignments, and midpoints |
| **Group Drag** | Hold Shift and drag to move a cluster of nearby boxes together |
| **Hide Boxes** | Toggle individual boxes off without losing their position |
| **Preset System** | 3 built-in presets + save unlimited custom layouts (positions, colors, shapes, visibility) |

#### Edit Mode Controls

| Control | Action |
|---------|--------|
| **Left-click** (Drag Mode) | Drag a single box |
| **Shift + Left-click** (Drag Mode) | Group-drag nearby boxes |
| **Left-click** (Edit Mode) | Cycle value color |
| **Right-click** (Edit Mode) | Cycle box shape |
| **Shift + Right-click** (Edit Mode) | Cycle label color *(split shapes only)* |
| **Left-click** (Hide Mode) | Toggle box visibility |

---

## ⌨️ Hotkeys

| Key | Action |
|-----|--------|
| **F6** | Toggle the entire HUD on / off |
| **F7** | Toggle the scoreboard on / off |
| **F8** | Open HUD Configuration |
| **F9** | Open Password Manager |
| **Esc** | Exit the current edit mode |

---

## 🔐 Password Manager *(bonus feature)*

MWHud includes a built-in **per-server password manager**, independent of the HUD itself.

| Feature | Details |
|---------|---------|
| **Auto-login** | Automatically runs `/login <password>` when you join a saved server |
| **Per-account storage** | Passwords are stored per server + player name pair |
| **Encrypted storage** | Passwords are AES-encrypted before being written to disk |
| **In-game UI** | Add, view (masked), and delete saved entries from the F9 screen |

> This is entirely optional and unrelated to the HUD data system.

---

## 📦 Installation

1. Install [Fabric Loader](https://fabricmc.net/use/) for Minecraft **1.21.x**
2. Download the latest `mwhud-*.jar` from the releases page
3. Drop it into `.minecraft/mods/`
4. Launch Minecraft with the Fabric profile

The mod works standalone — ping shows immediately with a default layout. Full HUD data (money, fly time, etc.) requires the **MWHud Plugin** installed on the server side.

> 🔌 Server admins: see the **[MWHud Plugin](https://github.com/Cranjo/mwhud)** page for setup instructions.

---

## 🎮 Explorer's Mugiwara SMP

Join **[Mugiwara SMP](https://your_server_link_here/)** — our thriving Minecraft Survival Multiplayer server! 🌊

Embark on an epic adventure in a friendly community-driven world featuring:

- 🏝️ **Custom Terrain** — Explore unique biomes and hand-crafted landscapes
- 💰 **Player Economy** — Trade, build shops, and become the richest pirate on the seas
- ⚔️ **PvP Arena** — Test your skills against fellow players in balanced combat
- 🎯 **Weekly Events** — Envoy crates, Key-for-all drops, and boss battles
- 🛡️ **Grief Protection** — Claim your land and build with peace of mind
- 🤝 **Active Community** — Join events, make friends, and sail the seas together!

*Set sail for adventure — the Grand Line awaits!* 🏴‍☠️

---

[![Modrinth](https://img.shields.io/badge/Modrinth-00AF5C?style=for-the-badge&logo=modrinth&logoColor=white)](https://modrinth.com/mod/mwhud)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Cranjo/mwhud)
[![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/YOUR_INVITE)
