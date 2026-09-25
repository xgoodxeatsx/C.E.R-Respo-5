# C.E.R. — Project Memory Migration Layer

**Migration date:** 2026-09-23
**Source:** ChatGPT C.E.R. project archive + current project context + external references checked during migration

## Project identity
**Cobblemon: Ecological Resonance (C.E.R.)** is a long-running Minecraft/Cobblemon modpack and systems-design project centered on making the Pokémon world feel ecological, reactive, discoverable, and interconnected rather than treating mods as isolated feature buckets.

The project is not merely a mod list. It has a formal governance/archive system, a large accumulated design history, and explicit rules for preserving old ideas while distinguishing them from current decisions.

## Why this migration layer exists
This file is deliberately a **navigation layer**, not a replacement for the archive. It tells a receiving AI what the archive contains, how to interpret it, and which current technical/reference points were checked during the transfer.

## Archive map
- `Project_Governance_Protocol.docx` — reusable process/governance framework.
- `Authorities_Archive.docx` — project-specific authority, permissions, terminology, principles, sweep/audit rules, and F.R.M.
- `Master_Archive_Part1.docx` … `Master_Archive_Part17.docx` — main project/design archive.
- `Master_Mod_Index.docx` — mod and compatibility index.
- `Cobblemon_Deep_Dive.docx` — detailed Cobblemon system analysis.
- `CER_Open_Questions_and_Loose_Ends.docx` — explicit unresolved questions and loose ends.
- `Missed_Questions.docx` — questions/prompts that were previously missed or needed follow-up.
- `CER_Reintegration_Sweep_Findings.docx` — reintegration audit of old/shelved concepts.
- `Change_Log_Archive.docx` — historical changes and decisions.
- `Interaction_Archive.docx` — collaboration/process history.
- `Supplemental_Archive.docx` — preserved material without a better canonical home.
- `EcoRe_Open_Questions_and_Gaps.md` — additional open questions/gaps.
- `EcoRe_Full_Sweep_Findings_UNINTEGRATED.md` — sweep findings not yet fully integrated.
- `EcoRe_Landmark_Build_Guide.md` and `EcoRe_Landmark_Build_Guide_AllSixZones.md` — landmark/world-building implementation material.

## Core design philosophy surfaced by the archive
These are navigation anchors, not permission to override the detailed archive:
- **Creation Over Crafting (C.O.C.)**
- **Discovery Over Prescription (D.O.P.)**
- **Anti-Pay-to-Win Principle**
- **Justified Complexity Rule**
- **Consequence-Based Teaching Principle**
- **Meaningful Integration Principle**
- Magic should interact with the world rather than become “Ars Nouveau: The Modpack.”
- Systems should preferably make the player discover, observe, restore, investigate, or meaningfully interact with the world rather than simply hand the player a menu of prescribed rewards.

## Major system families that must survive migration
The archive contains substantial design work around:
- Affinity / Resonance / ecological state
- Pokémon Shadow/Affinity aura concepts and their relationship to trainer/world systems
- regional restoration and living-world events
- Legendary/Mythical recognition, domains, attunement, and conduit/observatory concepts
- Resonance Expeditions and instability events
- positive resonance phenomena as a counterpart to instability
- ecological Apex / Alpha / Noble distinctions
- Pokémon fusion concepts, including the distinction between curated and generic fallback fusions
- quests and progression architecture
- research/scanning/registration systems
- Cobblemon Field Guide/Cobbledex interoperability ideas
- Poké Ball/tool modularity and potential affix systems
- Pokémon as workers/utility entities, including Cobbleworkers and the Starbuncles-to-Pokémon concept
- fossils and fossil deposits
- boss replacements and legendary-scale encounters
- themed/purpose-driven teams
- Paradox/Ultra Beast domain gating concepts
- landmark restoration and six-zone world-building
- integration of magic with the existing Affinity system
- extensive mod compatibility and version planning

## Important current technical context
The project has been actively discussing moving beyond an older Cobblemon 1.7.3 baseline. Several earlier compatibility ideas were version-specific and should **not** be assumed compatible with the eventual target.

Examples verified during migration:
- Cobbledex × Field Guide Compat Scan is a 1.20.1 Forge bridge targeting Cobblemon 1.5.2 / Cobbledex 1.1.0 / Field Guide 1.8.3. It is therefore a historical compatibility reference, not a current 1.21.1 assumption.
- Cobbleworkers currently has 1.21.1 releases and datapack-defined jobs; this makes it materially relevant to the current architecture.
- Cobblemon Fossil Deposits currently supports 1.21.1 and exposes a fossil-excavation event that other mods can react to.
- Stained Lenses remains a 1.20.1–1.20.6 Fabric project in the checked source, so it should be treated as an idea/reference rather than assumed available for 1.21.1.
- Attuned currently spans multiple Minecraft versions including 1.21.1, but its current feature set should still be evaluated against C.E.R.'s actual target loader/version before adoption.
- KyuremBoss currently has a 1.21.1 NeoForge release and replaces the Ender Dragon with a Kyurem boss; this is relevant to the boss-replacement research thread.

## Open-question handling
The archive itself identifies unresolved questions. Notable examples include:
- Noble Pokémon → Legendary Domain absorption/relationship
- exact Apex vs Noble boundary
- Legendary Attunement Core relationship to the general Attunement Core family
- Affinity Observatory vs Restoration Observatory naming/identity
- Affinity Essence ↔ Catalyst relationship
- two-Pokémon Affinity Catalyst behavior
- exact philosophies for purpose-driven teams
- Resonance Synthesizer vs Resonance Synthesis Chamber naming/role
- dynamic-generation fallback for non-curated Pokémon fusions
- whether the formal implementation milestone should be created
- the proposed full feature-by-feature Cobblemon Integration Bible

Do not resolve these by inference. Preserve them as questions until the archive or a new decision resolves them.

## Reintegration finding worth preserving
The reintegration sweep identified **Positive Resonance Phenomena** as a genuine gap rather than a dead/superseded idea. The concept is that successful sustained restoration can itself produce a detectable positive event — unusual resonance signature, rare Pokémon, Resonance Fossil, Affinity Fragment cluster, research discovery, temporary ecological buff, or an early Legendary-recognition thread. The exact mechanics remain open.

The sweep also introduced **🟣 Reintegration Candidate** as a status tag for historically superseded/rejected/banked concepts that become newly viable because surrounding architecture materially changed.

## Governance snapshot
The project uses **Free Reign Mode (F.R.M.)** / delegated authority. The detailed Authorities Archive is authoritative. Broadly, the framework permits proactive design/research/organization under standing permissions while requiring logging and respecting locked decisions. “Does this make E.R. better?” is the stated standard for delegated action; locked decisions are not silently overridden.

## Migration instruction to Claude
Read the full archive before attempting to compress it. Build a memory system that references the archive and keeps provenance/status distinctions. If a later Claude memory contradicts this package, preserve both records until the conflict is resolved.
