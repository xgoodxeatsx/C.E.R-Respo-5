# C.E.R. — External Source Manifest

This manifest preserves external links that were discussed in the C.E.R. work. Some are current technical references; others are historical/version-specific research. **A link being present does not mean the mod is approved for the pack.**

## Directly discussed references

### GitHub / project source
- C.E.R. update repository supplied during project work: https://github.com/xgoodxeatsx/C.E.R--update-4
  - Use as a project/code reference when available.
  - The migration search did not produce a reliable indexed result for this exact repository, so this entry is retained from the project context rather than represented as independently verified web metadata.

### Cobblemon Counter
- https://modrinth.com/mod/cobblemon-counter
- Current checked compatibility includes Minecraft 1.21.1, 1.20.1, and 1.19.2; tracks captures, knockouts, resurrections, fish-ups, egg hatchings, Pokémon eating nearby snacks, counts/streaks, and exposes commands. This is relevant to quest/event/condition architecture research. Source checked 2026-09-23.

### Cobbledex × Field Guide Compat Scan
- https://modrinth.com/mod/cobbledex-x-field-guide-compat-scan
- Historical compatibility bridge: Minecraft 1.20.1 Forge; Cobblemon 1.5.2; Cobbledex 1.1.0; Field Guide 1.8.3. It demonstrates a thin bridge pattern for dual registration and scan interoperability. Do not treat it as a 1.21.1 dependency.

### Cobbleworkers
- https://modrinth.com/mod/cobbleworkers
- Current checked compatibility: Minecraft 1.21.1; Fabric/NeoForge; server-side/singleplayer. Supports datapack-defined jobs. Relevant to Pokémon-as-workers/utility systems.
- Example 1.7-era release/source page: https://modrinth.com/mod/cobbleworkers/version/bbTUCGY1

### Cobblemon Fossil Deposits
- https://modrinth.com/mod/cobblemon-fossil-deposits
- Current checked compatibility: Minecraft 1.21.1–1.21.11, Fabric. Adds fossil deposits and exposes `FossilExcavationEvents.FOSSIL_EXCAVATED`, useful as a compatibility/event hook.

### Attuned
- https://modrinth.com/mod/attuned-mod
- Current checked source spans several Minecraft versions including 1.21.1. Relevant conceptually to affinity/attunement/loadout architecture, but compatibility with C.E.R.'s final stack must be independently tested.

### Stained Lenses
- https://modrinth.com/mod/stained-lenses
- Checked source currently lists Minecraft 1.20.1–1.20.6, Fabric. Useful as a design reference for spyglass/lens/module mechanics but not a current 1.21.1 assumption.

### KyuremBoss
- https://www.curseforge.com/minecraft/mc-mods/kyuremboss
- Checked source lists a 1.21.1 NeoForge release and describes replacement of the Ender Dragon with a Gigamax Kyurem boss. Relevant to the boss-replacement research thread.

## Other references discussed in project context
These should be searched/verified again before implementation because their version/support state can change:
- Mega Showdown / AllTheMons compatibility and datapack references
- Complete Galar Fossilmon
- Cobbledex / Field Guide
- Ars Nouveau and its Starbuncles
- Productive Metalworks
- Silent Gear
- Apotheosis-style affix concepts
- Ars Affinity / Affinity Jar source/code discussions
- Kyogre/Guzzlord/Wither/Elder Guardian replacement concepts
- Conduits / custom conduit concepts
- XMind project map

## Version rule
Every external mod reference must be recorded with the exact Minecraft version, loader, Cobblemon version, and relevant mod version when the project moves from research into implementation. Never infer compatibility from a project's existence alone.
