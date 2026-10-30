# Minotaur Arcade — v0.3.0

Four installable SMAPI arcade machines in Stardew Valley 1.6: maze escape, minotaur survival, **Block Caverns** and **Crystal Siege**.

- **Block Caverns:** first-person voxel-like raycast dungeon. Mine crystal and stone (F), build walls (G), collect 14 crystals. Shared block world and resource counter via lobby-owner sync.
- **Crystal Siege:** defend the base crystal for 100 seconds against three waves. Mine F, place G, shoot Space. Shared monsters, base HP and resources. Host-authoritative state.
- **Co-op:** create and find rooms **within the same Stardew Valley farm** (up to four players, each has the mod). No global lobby matchmaking.
- **Not full 3D:** stylized single-height blocks are rendered through a software 2.5D raycaster, no vertical stacking/free building.

The online [site](site/index.html) links to the compiled installable ZIP in [GitHub releases](../../releases/tag/auto-build). A successful C# build **does not** establish in-game compatibility.

## Installation
Download **MinotaurArcade.zip** from Releases, unzip the inner `MinotaurArcade` folder into `Stardew Valley/Mods/`, start game via SMAPI. After loading farm enter `arcade_give` in SMAPI console to receive four machines.

## Development
The complete C# sources and assets are kept in `source/MinotaurArcade_Source_v0.3.0.zip`. GitHub Actions unpacks and builds them automatically. Requires the appropriate SMAPI references.
