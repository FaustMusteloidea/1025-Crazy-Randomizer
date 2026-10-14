# 1025Dex Crazy Randomizer

**Created by Faust with assistance from ChatGPT**

A feature-rich Pokémon randomizer mod for Gen1Recomp, designed to expand encounter variety, trainer battles and replayability across supported Generation III Pokémon games.

> **Development status:** Experimental. Some features require additional testing, and known gameplay issues remain unresolved.

## Features

### Wild Pokémon randomization

* Randomizes wild Pokémon encounter tables.
* Supports ecological and chaotic randomization approaches.
* Supports multiple encounter methods, including walking, surfing and fishing.
* Designed to integrate with 1025Dex and DexNav.
* Supports compatibility with WildFollowers.
* Includes encounter-table options for special environments and map conditions.

### Trainer randomization

* Vanilla, Medium and Full Pokémon trainer modes.
* Configurable party-size behavior depending on trainer type and mode.
* Special handling intended for first rival battles and important trainers.
* Randomized trainer teams and battle encounters.
* Battle Frontier species randomization is implemented, but Frontier battles are currently affected by a critical freeze bug.

### Starters and special Pokémon

* Starter Pokémon randomization.
* Gift, NPC and event Pokémon randomization.
* Support for static encounters, trades and egg-related encounters.
* Special tutorial and scripted encounters are being expanded.

### Abilities and progression

* Randomized ability options for Pokémon, with Shedinja excluded from the standard two-option rule.
* Gym leader-based level caps and champion progression are implemented in the project but still require broader testing.
* Additional gameplay quality-of-life features are planned.

### Compatibility and configuration

* Designed primarily for Gen1Recomp and 1025Dex.
* Untamed Advanced compatibility is optional, not a required dependency.
* Compatibility work targets DexNav and WildFollowers integration.
* Per-playthrough randomization seeds and trainer seed controls are under development and testing.

## Known Issues

* **Battle Frontier — critical:** Battles in the Battle Frontier can freeze or become stuck. Avoid Battle Frontier battles until this issue is fixed.
* **Trainer party-size inconsistencies:** Some important trainers may display a different number of Poké Balls from the Pokémon they actually use, or may not follow the configured party-size rules correctly.
* **Trainer randomization rules:** Important-trainer team sizes and type assignments still need further verification across supported games.
* **Random seed behavior:** New playthroughs and manual seed regeneration require additional testing to ensure independent, persistent results.
* **Ruby and Sapphire:** Starter randomization requires further verification.
* **Scripted encounters:** Some special encounters, including certain tutorial and NPC events, still need implementation or compatibility fixes.
* **Compatibility:** Interactions with other mods may vary depending on their versions and load order.

## Planned Work

### Step 1 — Stabilize randomization seeds and trainer rules

* Ensure each new playthrough receives its own independent randomization seed.
* Ensure existing saves remain stable unless the player explicitly requests a new seed.
* Fix trainer party sizes and displayed Poké Ball counts.
* Enforce the intended rules for important trainers and first rival battles.
* Verify trainer randomization across FireRed, LeafGreen, Emerald, Ruby and Sapphire.

### Step 2 — Complete special encounters

* Randomize remaining scripted encounters.
* Fix the Old Man Weedle encounter in FireRed and LeafGreen.
* Complete special handling for Wally's tutorial encounter.
* Randomize Birch's chase encounters in Ruby, Sapphire and Emerald.
* Preserve the distinction between scripted encounters that use similar Pokémon.

### Step 3 — Quality-of-life improvements

* Add the option to use HMs without teaching the moves to a Pokémon, while preserving badge and story progression requirements.

### Step 4 — Additional tools and options

* Expand the in-game randomizer menu.
* Improve seed regeneration and configuration controls.
* Expand supported utility features and encounter controls.

### Step 5 — Compatibility, testing and release preparation

* Fix the Battle Frontier freeze.
* Improve compatibility with 1025Dex, DexNav, WildFollowers and optional Untamed Advanced integration.
* Test encounter methods, abilities, trainer modes and special events across supported games.
* Remove development-only diagnostic options from release builds.
* Validate the release package and document any remaining limitations.

## Supported Games

The project targets Pokémon FireRed, LeafGreen, Emerald, Ruby and Sapphire through Gen1Recomp and 1025Dex. Individual features may not yet work consistently across every game.

## Installation

1. Install a compatible version of Gen1Recomp.
2. Install and configure the required 1025Dex dependency.
3. Download the installable ZIP from the project's **GitHub Releases** page.
4. Import the ZIP using Gen1Recomp's mod manager.
5. Enable the mod for the intended game.

Back up your saves before installing or updating experimental builds.

## Credits

* **Faust** — Project creator and maintainer.
* **ChatGPT by OpenAI** — AI assistance with development, debugging, documentation and implementation.
* **Gen1Recomp** — Modding engine and framework.
* **1025Dex** — Core Pokémon data dependency.
* **Optional integrations:** DexNav and WildFollowers.

This is an independent community mod and is not an official Pokémon, Nintendo, Game Freak or Gen1Recomp product.

## Disclaimer

This project is under active development. Features and compatibility may change between releases. Known issues are documented above; please report reproducible bugs with the game, mod versions and steps needed to reproduce them.
