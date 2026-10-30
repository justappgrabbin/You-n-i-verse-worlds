# Worlds — verified source catalog

Catalog date: 2026-10-29. These are source-code findings, NOT proof of installed worlds, APK functionality or multiplayer. Every item has a source and a known gap. Original files are retained in Drive and Github; source is NOT replaced or overwritten. [Worlds model](WORLD_MODEL.md) · [Registry JSON](REGISTRY.json).

## World runtimes and spaces

### SynthWorld Godot 321

- **Platform:** Godot 4 / Android. **Audience / role:** Human + agent scene.
- **Contains:** Cynthia and generator agent, world/props, sentence service, Godot export; separate branch has HumanBody and local AI scene/theme director.
- **Missing or unverified:** World scene sparse; Morph donor rigs and full discovery game not integrated; APK not tested.
- **Inspection:** Source and branch inspected. **[Original source](https://github.com/justappgrabbin/SYNTHWORLD-)**.

### Synthia World with MCPs

- **Platform:** Python. **Audience / role:** Human avatar + MCP/NPC agents.
- **Contains:** synthia_world.py, mcp_npc_system.py; avatars, locations, relationships, Hall of Gates, Resonance Garden, Learning Temple, Creation Workshop, Collective Heart.
- **Missing or unverified:** SYNTHIA archive, probable match for user-named MCP SynthWorld; not proven deployed multiplayer or 3D.
- **Inspection:** ZIP and Python inspected. **[Original source](https://drive.google.com/file/d/1igXMuVwfNV0eijp-Bf1JH483k1oOf7zf/view)**.

### ConsciousnessRealm (York build bridge)

- **Platform:** HTML / Termux shell. **Audience / role:** Not established.
- **Contains:** Bootloader HTML and Android build script that expects another ConsciousnessRealm source ZIP and York builder.
- **Missing or unverified:** The reviewed archive contains TWO files, not the complete realm/game or verified APK.
- **Inspection:** Both files listed; build script read. **[Original source](https://drive.google.com/file/d/1lUsrZc9-criUahS9JjYJ0mQNClh2PDhH/view)**.

### YOU-N-I-VERSE Cynthia Morph Game

- **Platform:** Node.js / Python. **Audience / role:** Personal three-world game; future community separate.
- **Contains:** Three persistent worlds, identity history, photo morph, RPG/story journeys, saved progress, Cynthia tool interface.
- **Missing or unverified:** Local studio not evidence of online agent community or complete 3D residents.
- **Inspection:** ZIP README and source inspected. **[Original source](https://drive.google.com/file/d/1fDvIpqkXOawi_frUGg7M5UbX5TwlMygg/view)**.

### YOU-N-I-VERSE World Engine v2

- **Platform:** Standalone HTML / JavaScript. **Audience / role:** Offline local world/lab.
- **Contains:** Seeded terrain, animated agents, wave interference, fields, character JSON and SVG export; research workbench.
- **Missing or unverified:** README says it is not a merge of the existing GitHub code; no backend, multiplayer or LLM.
- **Inspection:** ZIP README/source inspected. **[Original source](https://drive.google.com/file/d/165PuaP45XU2eGrDnKXm3_Bjf3VjESssm/view)**.

### YOU-N-I-VERSE HybridRepo

- **Platform:** JS / JSX / JSON. **Audience / role:** Agent scenario prototype.
- **Contains:** Birth input, gate logic, field scanner, agent spawner, ScenarioRoom, dashboard, memory log.
- **Missing or unverified:** Small prototype, not a full running world.
- **Inspection:** ZIP files listed. **[Original source](https://drive.google.com/file/d/1VGH2ti4KxDLw3o9dBP_mwDbAqQOfcZah/view)**.

### SimWorldForge / ModularSimWorld

- **Platform:** C# .NET / FreeSO. **Audience / role:** Simulation framework.
- **Contains:** Simulation ticks and objects, autonomous agents, astrological characters, avatars and console world viewer; FreeSO file interfaces.
- **Missing or unverified:** World viewer is console; FreeSO object code includes simulation placeholders; no playable APK verified.
- **Inspection:** ZIP and C# inspected. **[Original source](https://drive.google.com/file/d/1W3vc9LK60ViiuhlyhpZJvAbOh-q1Z-bf/view)**.

### Foundry + World Engine (GitHub Supabase edition)

- **Platform:** HTML / JS / Supabase. **Audience / role:** Browser visual world.
- **Contains:** Index.html contains sky/ground, environment, Foundry HUD and Supabase integration.
- **Missing or unverified:** Earlier standalone implementation; backend connectivity not verified.
- **Inspection:** GitHub file inspected. **[Original source](https://github.com/justappgrabbin/World-engine-)**.

### Foundry World Engine Qualia

- **Platform:** Standalone HTML. **Audience / role:** Browser world and creation surface.
- **Contains:** World viewport, environment, Foundry drop area, qualia panels; separate mobile and API-enabled variants exist.
- **Missing or unverified:** Distinct branch/files, not proven integrated with Godot.
- **Inspection:** HTML inspected. **[Original source](https://drive.google.com/file/d/1OF77LCrgO-R3LeAR1gDOjlQADX5OT75O/view)**.

### Consciousness Simulation Game

- **Platform:** HTML / JS. **Audience / role:** Browser agent activity/demo.
- **Contains:** Agent cards, control panel and simulation UI.
- **Missing or unverified:** Not proof of a fully deployed ConsciousnessRealm.
- **Inspection:** HTML inspected. **[Original source](https://drive.google.com/file/d/1koGI05v9Zl_esuHpGVwz-drYp65afD19/view)**.

## Games and activities

### Self-Discovery / Synthworld V2

- **Platform:** React / Express / TypeScript. **Audience / role:** Human-facing self-cultivation game.
- **Contains:** Game HUD, coherence, Datababy collection, Gene Gnomes, awakening, mini-games, progression, server routes.
- **Missing or unverified:** Not yet connected as a page in Godot or shared Worlds app.
- **Inspection:** ZIP / React and server code inspected. **[Original source](https://drive.google.com/file/d/1JayS0GclgyJRMh6QC8VO7Zk3FImVT5-c/view)**.

### Human Design Life-Sim v8

- **Platform:** Built web frontend. **Audience / role:** Human-facing life-sim.
- **Contains:** index.html and compiled JS/CSS frontend artifacts.
- **Missing or unverified:** Unminified source and actual gameplay unverified.
- **Inspection:** ZIP paths inspected. **[Original source](https://drive.google.com/file/d/13y3e2vO3nw__Tl7b8frr4E6pCZ3sKbVW/view)**.

## Builders, bridges and donor components

### SynthWorld Consciousness donors

- **Platform:** TS / Python / Godot packages. **Audience / role:** World orchestration source collection.
- **Contains:** World orchestrator, symbolic parser, consciousness field and many nested engines/starters.
- **Missing or unverified:** Mixed collection rather than single finished world; variants may diverge.
- **Inspection:** ZIP and README inspected. **[Original source](https://drive.google.com/file/d/1qjr0u4I81kaBS6JF36xcgDMWlHRGEvXg/view)**.

### YOU-N-I-VERSE Game Unit patch

- **Platform:** React / TypeScript. **Audience / role:** Games and world launch interface.
- **Contains:** Adds game-unit route and launcher; references GameEngineX, GameAssetStudio, SimsConverterStudio; adds Resonance ZIPs.
- **Missing or unverified:** Overlay requires existing browser baseline; not a new complete world.
- **Inspection:** Handoff/source inspected. **[Original source](https://drive.google.com/file/d/1BvNtRrwZsYxOcnYVmGiKgZrWVqVKy_YP/view)**.

### YOU-N-I-VERSE Browser / IDE

- **Platform:** React / Node. **Audience / role:** Worlds access/dev shell.
- **Contains:** Browser dashboard and built-in developer studio plus standalone IDE extraction.
- **Missing or unverified:** Some heavy payloads intentionally excluded; does not establish a live shared world.
- **Inspection:** ZIP README inspected. **[Original source](https://drive.google.com/file/d/1ULik7DcfS7O5R60BcP7dr1Nj7stQNtOV/view)**.

### WorldGen panorama generator

- **Platform:** Python / GPU image diffusion. **Audience / role:** World environment generator.
- **Contains:** Panorama fill/generation, inpaint, segmentation, depth and splat utilities.
- **Missing or unverified:** Asset creation pipeline, not gameplay world; GPU requirements.
- **Inspection:** ZIP files inspected. **[Original source](https://drive.google.com/file/d/1Lop7ONxHDnd8AYRSfA9GyzXjV-mtpuI0/view)**.

### Synthia GameForge

- **Platform:** TS / Vite. **Audience / role:** Game engine/builder.
- **Contains:** GameForge, GameGAN, Unreal adapter, media engine, GitHub speed dial.
- **Missing or unverified:** Builder source; not a completed world or a verified Unreal integration.
- **Inspection:** ZIP source inspected. **[Original source](https://drive.google.com/file/d/1tmgkAHg-JqNOxtdxhcY2wSSSVpg2vgbw/view)**.

### VERSE origin and adventure sites

- **Platform:** HTML / JS / Python. **Audience / role:** Cross-site access hub.
- **Contains:** Origin, vault/pipeline, Resonance social site, Adventure games/agents site, Prosperity site.
- **Missing or unverified:** README still lists WebSockets and agent initialization as future steps.
- **Inspection:** GitHub README/tree inspected. **[Original source](https://github.com/justappgrabbin/VERSE)**.

### Synthia Morph Forge Offline

- **Platform:** HTML. **Audience / role:** Morph asset/interface donor.
- **Contains:** An offline Morph Forge HTML project was located.
- **Missing or unverified:** Capabilities not deeply audited; do not classify as playable world.
- **Inspection:** Metadata verified. **[Original source](https://drive.google.com/file/d/1d-YeKt3bD5OKiwMzF4DH4lDO0q7Bz66M/view)**.

### Paper World HTML

- **Platform:** HTML. **Audience / role:** Page/world experiment.
- **Contains:** paper-world-1767275247917.html identified.
- **Missing or unverified:** Source not yet inspected; status and relationship to full world unknown.
- **Inspection:** Metadata verified. **[Original source](https://drive.google.com/file/d/1CTNi2RsR60eXts8z0AYPzc_saOTuMDgg/view)**.

### Synthia Light Mobile (Nodejs-1)

- **Platform:** Node.js / Express / TypeScript / Kaboom.js. **Audience / role:** mobile-first world and sprite builder with playable web games; not an agent-only world.
- **Contains:** Synthia Light Mobile app, a responsive world builder with tiles/sprites/entities, JSON game-spec compiler, /play game route, JupyterLite-based journal page and API documentation. Source includes src/server.ts, src/routes/games-lite.ts, scripts/game_maker.cjs, termux/setup.sh and public game sprites.
- **Missing or unverified:** No proof of live hosting, integration into the YOU-N-I-VERSE Worlds page, or conversion into a full 3D agent reality. Nodejs-1 ZIP contains an embedded .git directory and Replit agent state; do not import those into a shared repository.
- **Inspection:** ZIP README, package.json, source listing and server code inspected; not launched. **[Original source](https://drive.google.com/file/d/1RPGsH9N9UgmZNST6TdgtzyoMUasLVNY2/view)**.

## Alternate/donor locations

- [SynthWorld-321 original source ZIP](https://drive.google.com/file/d/10n4q1tZc165YQx7fc3Fn0hwtX-_rycae/view).
- [Foundry World Engine mobile/API variant](https://drive.google.com/file/d/13dholHHS33q93eKOQDWKYfX7JVNObx7H/view).
- [YOU-N-I-VERSE GameUnit alternate patch](https://drive.google.com/file/d/1DX65aeLa9Ei0cYml0HEbkiRCQ7RICZ-A/view).
- [ConsciousnessRealm alternate builder](https://drive.google.com/file/d/1UGG29iOwi70EmXX8j6xBX8vJKwO7zW0V/view).

## Key distinction

The eventual Worlds PAGE is a product interface that can list these as available, in-development or source-only. An agent-only world, a human/agent shared world, a personal Indieverse and a game/activity are separate roles. We have not made the world page live, migrated any world state, connected these runtimes or merged their visual systems here.

The archives contain nested repos and sometimes compiled assets; this catalog intentionally records provenance rather than uploading entire ZIPs into a public GitHub repository. Do not strip original mechanics to fit a single engine.
