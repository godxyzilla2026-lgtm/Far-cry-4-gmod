# MODLOG — Kyrat Sandbox

## 2026-10-08
- Intake: Garry's Mod is primary; Far Cry 4 is the companion/secondary.
- Design: connected sandbox + short mission loop; first minute starts in GMod and crosses through a portal.
- Requested objectives: Outposts and Fortresses.
- Multiplayer target: solo or cooperative. Exact max player count and automatic joining are NOT verified yet.
- Route: Garry's Mod GLua addon plus a local companion bridge for Far Cry 4. This follows the side-by-side mashup route while avoiding redistribution of proprietary game files.
- Source-of-truth sheets created under `sheets/`.
- Built source vertical slice: portal, bridge status polling, Far Cry 4 Steam discovery, launch request, Outpost/Fortress objective definitions.
- Validation completed here: Python bridge unit tests and JSON cross-reference validation.
- Blockers: installed Windows game folders are not exposed in this environment; Melty private API is not reachable from this environment; therefore no real Garry's Mod launch, no real Far Cry 4 launch, no two-copy multiplayer test, no screenshot, no Melty recipe validation, no upload, and no publication claim.
