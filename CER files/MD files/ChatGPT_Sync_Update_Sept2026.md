# C.E.R. — Sync Update for ChatGPT (Sept 2026)

Following the "lab notes, not changelog" standard you two settled on — this covers everything since the last sync, including locked decisions, open questions, half-formed ideas, and reasoning, not just finalized stuff. Marked with the same tags you proposed.

---

## 🔒 CONFIRMED (settled, built into the archive)

- **Ball system naming resolved.** "Resonance Ball" is now the true top-level umbrella for the entire ball technology family — not a specific tier, the name of the whole thing. Both sub-families sit under it: Affinity Balls (Attunement Core) and Anomaly Balls (Anomaly Core). All of it is produced by one named R&D institution, the **Modular Ball Program**.
- **Core crafting mechanism resolved**: universal blank Cores, attuned afterward in a separate step — for BOTH the Resonance/Attunement Core and the Anomaly Core. Not pre-typed items you go shopping for; you craft a blank, then attune it. Reasoning: matches "Attunement" as a process verb, matches the pack's multi-stage-crafting house style, better serves "No Best Ball" (decide what to attune in the moment rather than predicting needs at the bench).
- **Anomaly Core origin resolved**: it's not a separate raw material — it's a *distorted/unstable version of a Resonance Core itself*. A Resonance Core exposed to enough instability (low-Affinity conditions, proximity to a real anomaly) becomes an Anomaly Core. Reuses the exact "Distorted Ecosystem" terminology already locked for the low end of the World Affinity scale, rather than inventing new vocabulary. Gives Anomaly Balls real narrative logic too: they're built from material that's already been through the same instability as what they're containing.
- **Vanilla/mod ball absorption strategy locked**: standout mechanics from vanilla and mod balls (Quick Ball, Timer Ball, Dusk Ball, etc.) get folded into the Resonance Ball system as Treatments or unique perks, then the original separate items retire. Explicit application of "No Best Ball" at the *pool* level, not just individual ball design — kills the "which of 20 overlapping balls do I even carry" problem.
- **Master Ball keeps its place**, recontextualized: it's the *Masterwork* tier of the Resonance Ball system specifically (reusing the exact top tier already named in the Resonant Transformation ladder — "Masterwork: Endgame hybrid technology"). Its guaranteed catch is earned as a literal amalgamation of every Core, Attunement, Treatment, and Anomaly tech at once, not an arbitrary stat. Poké/Great/Ultra stay a fixed, unmodified control group.
- **Beast Ball becomes a shared baseline for THREE branches**, not a straight merge into one ball: **Dimensional Ball** (Ultra Beasts, spatial displacement), **Temporal Ball** (Paradox, temporal displacement), and a new **Titan Ball** (Titanization specifically).
- **Titan Ball's first appearance is a discovery hook**: the player's very first Titan encounter hands them a single Titan Ball *before* anything about Titans or Titan Balls has been explained — they have to work out through play that it's the one thing that can actually catch what they're facing. Motivates the whole Titan research arc organically.
- **Field Journal boundary rule extended to cover advancements.** Confirmed NOT a conflict: the Journal's existing rule already separates "casual in-game notifications" from its own formal entries. Advancement-style flavor-text popups (à la the Levitated series — "It has been discovered that Eevee thrive on personal interaction..." instead of "Pet an Eevee") are exactly that casual layer. An advancement firing can be *one of the ways* a Journal entry gets triggered; the Journal still owns the actual record.
- **World Affinity threshold-gated machines** — a new, separate mechanic from Resonance Machines/Drives. Certain machines need a minimum *local* World Affinity level, in specific types, just to function — not a drain, a pure threshold check. Design rule: pick the type(s) matching the machine's real thematic identity, scale the threshold to its tier (or its Resonant Transformation stage if it's on that ladder).
- **The Sundering is dead as a name.** Three names now, one event, three civilizational eras: the ancients' *Ruin of Echoes* (originally misattributed to Echo/Memory phenomena, corrected once the real cause — Affinity dissipation — was understood, kept the old name anyway), the modern *Great Resonance Divergence*, and a future era's *Unison Break*.
- **Player-origin backstory fully resolved and connected to several previously-separate systems**: the player fell through an accidental breach in Space (not a functioning system — a crack in an imperfect seal), which is *also* the event that stripped 7 of their 8 Resonance Hearts, *and* the same event that explains Trainer Affinity's origin (exposure to all 18 Affinities during transit, balanced not corrupted, hence receptive rather than Shadow). "Get home" is the narrative spine; restoration is the gameplay spine; they converge because restoration turns out to be a requirement for passage, not just parallel to it.
- **Research Station** (the physical crafting/power/archive multiblock) is fully designed and locked, including real three-position interaction logic pulled from the actual submitted 3D model file — left block = crafting GUI, center block (where the laptop terminal sits) = Replication Terminal GUI, right block = Archive GUI.

## 🟡 CANDIDATE (strong direction, not fully locked)

- Exact Resonance-vs-Attunement Core naming — mechanism is locked, final name isn't.
- Which specific vanilla/mod ball mechanics map to which Treatments — a first pass exists (Quick Ball → Rapid Deployment, Repeat Ball → Species Recognition, Beast Ball fully retiring into the new three-way split) but it's not exhaustive.
- **A real gap found, not yet resolved**: every existing Treatment governs the *capture moment*. Nothing covers *post-capture* effects (Friend Ball, Luxury Ball, Heal Ball have no home at all). This isn't a missing Treatment, it's a missing *category* of Treatment.

## 🔵 CURRENT PROPOSAL (genuinely live, not decided)

- Whether the Capture Phase should visually restrict/highlight which balls are usable, versus just letting invalid ones silently fail (the fail-fallback stays either way — this is about *also* giving a "here's what's available" read). Technically doable since the phase already needs custom validity logic.
- The escaped-Titan-on-capture-failure mechanic (Titan flees rather than resetting, becomes a real rediscoverable entity) — direction is strong, exact behavior (relocates? same area? warier?) undecided.
- A "Space Time" joint Palkia+Dialga recognition event for unlocking Tempad (the Time-themed real mod behind StoneBlock 4's teleport network) — player may only recognize one Legendary on a first attempt, the second becomes a re-huntable encounter using the same escape pattern as Titans.

## 🧩 CONNECTIONS DISCOVERED (systems that turned out to already relate)

- Storage-mod unification (Tom's Simple Storage → AE2/RS → QIO Dashboard) maps cleanly onto the already-existing Resonant Transformation ladder's Integration rung without needing a new framework.
- The Titan Capture Phase now uses real existing infrastructure (Cobblemon Raid Dens Addon) as its actual second-stage encounter chamber, rather than an invented mechanic.
- Waystones and Tempad resolved as two honest *tiers* of the same teleportation arc (Waystones = early/limited, tied to a first small Palkia recognition; Tempad = full endgame, requiring both Palkia AND Dialga) rather than two mods competing for the same job.

## 🔬 RESEARCH COMPLETED

- Deep-dived the actual top Cobblemon modpacks/servers ecosystem (Cobbleverse, Academy 2.0, Delta, Diosesmon, Elysium, Islands, TalonMC, and others) — the standout finding: top server-anchored packs ship *deliberately minimal* client mods, with all their signature content (gyms, raids, Mega Evolution, economy) living server-side, not in the download. Diosesmon's PokePad (a single hub item unifying GTS, hunts, missions, player-scanning) is a genuinely strong single-item design worth studying further.
- QIO Integrations verified as a real mod bridging AE2 + Refined Storage + Tom's Simple Storage through Mekanism's QIO Dashboard — real code exists for NeoForge 1.21.1, but the project is small-scale (3 commits, 1 star) and only documents 1.20.1 Forge as actually implemented. Logged as watch-and-recheck, not locked.
- Tempad confirmed as the real mod behind StoneBlock 4's teleport network (not TelePads, which is genuinely abandoned on old Forge).

## ❓ OPEN QUESTIONS FOR YOU TO CHASE OR ANALYZE

- The "catch window / special balls at specific times" mechanic Wesley half-remembered turned out to already be locked (the Titan Capture Phase rule) — but if there's a *separate* memory of something else along those lines, it's still not accounted for.
- The post-capture Treatment category gap above — worth thinking through what that family should actually contain.
- Whether Elysium's survival-coequal approach (Pokémon as one activity among several, not the whole loop) is something C.E.R. should adopt or deliberately reject.

---

*Compiled by Claude, Sept 2026. Formatted to be pasted directly into your next ChatGPT session.*
