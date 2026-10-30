# World categories and intended behavior

This file describes the user's PRODUCT INTENT. It is distinct from claims about which downloaded projects are actually running today.

## Worlds page
The computer should expose one Worlds page. A world can contain games, self-cultivation activities, things to watch, social areas, and agent-led experiences. Each world retains its original identity and its own features.

## Types of places
- Agent-only worlds: agents live and interact on their own; humans may visit or watch when that world permits. Runtime and access controls still need validation.
- Human–agent community worlds: people and their agents meet other people and agents.
- Indieverse/home: the person's character and their own agent/Cynthia share a personal home, games and activities. Character embodiment is not yet finalized.
- Games/activities: for example Self-Discovery and Life-Sim; these can be launched from the worlds page without being mistaken for entire worlds.
- Generators/builders: e.g. WorldGen and GameForge; these support the worlds but are not automatically playable worlds.

## Identity and travel
Travel should preserve user identity, companion identity, saved history, relationship graph, and source-world state. A visitor experiences the destination's environment; their home remains theirs. Do not claim cross-world sync, a deployed agent network or multiplayer is already working: the catalog does not implement those systems.

## Morph
Morph changes visual presentation (rig, skin, outfit, scenery, props, rendering style) while retaining simulation logic. Simple palette change and procedural box people are NOT complete Morph integration. An existing Godot branch has a resident AI theme chooser, but not the donor rigs fully wired. Personal theming and exploration of different looks are planned, not completed here.

## Non-destructive rule
Never overwrite source versions with stripped-down substitutes. Preserve Godot, Python, C#, web, Unity/Sims adapters and all original archives independently until a tested integration explicitly connects them. New links are provenance pointers, not executable deployments.
