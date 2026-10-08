# Garry's Mod × Far Cry 4 — Kyrat Sandbox

## Status
Source prototype — not yet verified in Garry's Mod/Far Cry 4 on the target PC.

## Concept
A mashup hosted by Garry's Mod. The player starts in the Garry's Mod sandbox, uses a portal to enter a Far Cry 4 session, and can return to the sandbox. The first slice combines a sandbox area with a short objective loop featuring an **Outpost** and a **Fortress** objective.

Far Cry 4 is treated as bring-your-own-game content. The release must not ship Far Cry 4 files. The companion bridge discovers the player's own Steam installation and can launch the player's copy so the two games can run side-by-side and exchange state.

## Current vertical slice
1. Garry's Mod shows a portal near the player.
2. Using the portal sends a request to the local bridge.
3. The bridge reports whether Far Cry 4 is detected and can launch its Steam copy.
4. The GMod HUD displays the companion state.
5. Two mission objectives are represented in the GMod sandbox: `outpost` and `fortress`.
6. The bridge exposes a small local status API so a later Melty recipe can coordinate the two components.

## Important limitation
This environment does not have access to the installed Windows game folders or the Melty publishing API, so the real-game integration, screenshot capture, recipe validation, and publication have not been claimed as complete.

## GMod route
The addon uses Garry's Mod's normal `garrysmod/addons/<addon>` structure and GLua autorun/entity files.

## No redistribution
Only original source code and metadata belong in this repository/package. Far Cry 4/Garry's Mod proprietary game assets are not included.
