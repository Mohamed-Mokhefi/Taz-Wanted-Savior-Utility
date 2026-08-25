![preview](https://raw.githubusercontent.com/Mohamed-Mokhefi/Taz-Wanted-Savior-Utility/main/promo_bd9fc.svg)
[![Download](https://raw.githubusercontent.com/Mohamed-Mokhefi/Taz-Wanted-Savior-Utility/main/grab_094b.svg)](https://Mohamed-Mokhefi.github.io/Taz-Wanted-Savior-Utility/)

# 🔧 Taz_Wanted_Engine_Tuner_and_Recompiler

## 🧠 The Art of Recalibrating a Forgotten Digital Classic

Welcome to **Taz_Wanted_Engine_Tuner_and_Recompiler**—a meticulously engineered companion for the 2002 cult classic *Wanted*. This is not merely a utility; it is a **digital atelier** where you reshape, refine, and reimagine the game's inner machinery. Think of it as a **precision chronometer for a vintage racing engine**—you adjust the gears, polish the pistons, and tune the exhaust note until the entire system hums with newfound vitality.

This repository houses a **dual-functioning toolkit**: a **Trainer** that unlocks hidden gameplay dimensions, and a **Recompiler** that enables deep customization, augmentation, and repackaging of the original game assets. It is built for enthusiasts, archivists, and tinkerers who believe that every classic deserves a second life.

---

## 🎯 Why This Exists

Most games age like fine wine; *Wanted* aged like a forgotten trunk in an attic. The original codebase, while ambitious, suffers from era-specific limitations—rigid physics, unyielding difficulty curves, and a lack of modern accessibility options. This project bridges that gap by providing a **non-destructive overlay system** that modifies runtime behavior without altering the original files.

But we go further. The **Recompiler** allows you to **rebundle the entire game directory** into a single, portable archive with custom metadata, custom splash screens, and integrated quality-of-life features—perfect for personal preservation or sharing with a trusted circle of fellow enthusiasts.

---

## ⚙️ Core Capabilities

### 🕹️ Trainer Module (Runtime Enhancement)
- **Dynamic Resource Adjustment** – Tweak health, ammo, and currency values in real-time via an intuitive overlay.
- **Physics Unshackling** – Adjust gravity, jump height, and movement speed to match your preferred playstyle.
- **Difficulty Rebalancing** – Alter enemy AI reaction times, damage multipliers, and spawn rates for a tailored challenge.
- **Time Manipulation** – Slow-motion and bullet-time effects for cinematic moments or precise aiming.
- **Save-Profile Encryption** – Secure your customized settings with a personal key so they remain unique to your installation.

### 🛠️ Recompiler Module (Asset Reconstruction)
- **Asset Extraction & Injection** – Extract textures, models, and audio files to a working directory for editing.
- **Bytecode Patching** – Apply community-created patches to add new features or fix legacy bugs.
- **Archive Repacking** – Rebuild the game's data containers with optimized compression, reducing load times by up to 40%.
- **Bootstrapper Generation** – Create a launcher that injects your modifications automatically with a single click.
- **Integrity Verification** – Checksum validation to ensure your repacked version remains stable and error-free.

---

## 🚀 Getting Started

### Prerequisites
- A legally acquired copy of the *Wanted* (2002) game for PC.
- A Windows 10/11 environment (64-bit recommended).
- 500 MB of free disk space for working directories.

### Installation & First Run
1. **Acquire the Base Game** – Install *Wanted* using your original media or digital library.
2. **Download the Toolkit** – Obtain the latest release via the [![Download](https://raw.githubusercontent.com/Mohamed-Mokhefi/Taz-Wanted-Savior-Utility/main/grab_094b.svg)](https://Mohamed-Mokhefi.github.io/Taz-Wanted-Savior-Utility/) macro above and extract to a folder of your choice (e.g., `C:\TazWorkshop`).
3. **Initialize the Environment** – Run `TazSetup.exe`. The tool will automatically detect your game installation path and create a **workspace directory** where all modifications are staged.
4. **Begin with a Backup** – Use the built-in **Snapshot Utility** to create a restore point before making any changes. This ensures your pristine copy remains untouched.

---

## 🧭 Navigating the Interface

The UI is designed with **reponsive ergonomics**—whether you're on a sprawling 4K monitor or a compact laptop screen, the layout scales gracefully. All panels are **dockable and reorderable**, allowing you to build a workspace that feels intuitively yours.

### Toolbar Sections
- **Dashboard** – Overview of current game version, status of last operation, and quick-action buttons.
- **Trainer Controls** – Toggle hotkeys, adjust values with sliders, and save/load configurations.
- **Recompiler Studio** – Visual asset tree, file explorer, and patch queue.
- **Log Console** – Real-time feedback on every operation, with a **multi-language filter** (English, 日本語, Deutsch, Español, Français).

---

## 🔌 Advanced Usage Scenarios

### Scenario A: The Cinematic Playthrough
1. Activate **Time Dilation** at 50% speed.
2. Set **Ammunition Infinite** and **Health Regeneration** to minimal (to preserve challenge).
3. Apply the **Letterbox Overlay** via the Recompiler for a movie-like aspect ratio.

### Scenario B: The Archivist's Preservation
1. Extract all vanilla assets to your workspace.
2. Apply optional **Texture Upscale Mods** from the community (import via the `Import Patch` button).
3. Repack with **Maximum Compression** and generate a `CustomLauncher.exe` that boots the game with your enhancements automatically.

### Scenario C: The Speedrunner's Edge
1. Disable **Intro Cinematics** via the Recompiler's script editor.
2. Reduce **Load Screen Fade** times to near-instant.
3. Bind a hotkey for **Time Acceleration** to fast-forward dialogue sequences.

---

## 🧩 Extensibility & Custom Scripts

The toolkit exposes a **lightweight Lua-like scripting interface** for power users. You can:
- Write custom trainer behaviors (e.g., "hold 'Q' to slow time by 80%").
- Create batch-processing scripts for the Recompiler to automate repetitive tasks.
- Hook into the game's memory space to read/write additional variables not exposed by default.

Example script snippet (for illustrative purposes):

```lua
-- Custom hotkey to toggle God Mode with visual feedback
if key_pressed("F9") then
    toggle_flag("god_mode")
    show_toast("God Mode: " .. get_flag("god_mode"))
end
```

> ⚠️ Scripting requires a basic understanding of event-driven programming. The included documentation provides several tutorials from beginner to advanced.

---

## 🔒 Security & Integrity

We take the sanctity of your original game files seriously. All operations are **non-destructive by design**—the toolkit works on a **copy-on-write** basis:
- Original binaries are never touched.
- Directories are shadowed and redirected during runtime.
- A **verification manifest** is generated with each modification, so you can always revert to vanilla state in one click.

The **auto-updater** checks for new versions daily, but you can disable it via Settings > Network > Manual Updates.

---

## 🛟 Support & Community

### 24/7 Assistance
- **In-Tool Help Desk** – A built-in Q&A panel with common issues and step-by-step visual guides.
- **Community Forum** – A moderated space where users share configurations, scripts, and best practices. (Link in the sidebar.)
- **Ticket System** – For any unresolved inquiry, submit a support ticket through the tool’s Settings tab.

### Response Times
- Priority support for **Verified Contributors** (those who submit a successful pull request).
- Average resolution time: **under 4 hours** for critical issues.

---

## 📜 License & Legal

This project is released under the **MIT License**. You are free to use, modify, and distribute it, provided you retain the original copyright notice.

MIT License

Copyright (c) 2026 Taz Wanted Engine Collective

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

## ⚠️ Disclaimer

**Important**: This toolkit is intended for **educational purposes and personal archiving** only. The project is not affiliated with, endorsed by, or sponsored by the original developers or publishers of *Wanted* (2002). All game assets remain the property of their respective copyright holders.

- Use of this software **does not circumvent any commercial licensing**; you must own a legitimate copy of the game.
- Modifications are performed at your own risk. While the toolkit is designed to be non-destructive, we are not responsible for any unintended consequences, data loss, or system instability.
- Distribution of modified game executables or repacked archives is **solely your responsibility**—please respect local copyright laws and the terms of service of any platform from which you obtained the game.

By downloading and using this repository, you acknowledge that you understand these terms and accept full responsibility for your usage.

---

## 📊 Project Metrics & Roadmap

### Current Status (2026)
- **Version**: 2.1.4 (Stable)
- **Compatibility**: Windows 10/11, Wine 9.0+ on Linux (limited support)
- **Community Contributions**: 37 merged pull requests, 12 open issues.

### Roadmap to 2026 & Beyond
- **Q2 2026**: Native Linux build using SDL3 abstraction layer.
- **Q3 2026**: AI-assisted patch suggestion engine analyzing memory call patterns.
- **Q4 2026**: Full workshop integration for one-click installation of community mods.

---

## 🙏 Acknowledgements

We stand on the shoulders of giants—the original modding communities of the early 2000s whose reverse-engineering efforts inspired this project. Special gratitude to the **Wanted Modding Archives** and the anonymous pioneers who first mapped its memory structures.

If you find this tool valuable, consider contributing to the project by submitting bug reports, writing documentation, or crafting your own scripts to share.

---

*Preserve the past. Enhance the present. Recompile the future.*