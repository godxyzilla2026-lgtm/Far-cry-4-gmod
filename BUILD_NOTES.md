# Build notes

The package intentionally does not contain Garry's Mod or Far Cry 4 assets.

The GMod side is structured as an addon, using `garrysmod/addons/<addon>/...`.
The companion bridge is plain Python so it can be replaced by a packaged Windows executable once the real machine is available.

The bridge's discovery uses Steam library metadata and the Far Cry 4 Steam App ID already associated with the player's installation. It only finds and launches the player's own copy; it does not copy or redistribute game data.

Before a public release, the following still need to be completed on the player's actual Windows PC:
- verify the portal and HUD inside GMod;
- verify the Far Cry 4 companion launches;
- implement the final in-session handoff/synchronization between the games;
- implement and test solo/co-op behavior with two running copies;
- capture real gameplay media;
- validate and submit the Melty recipe;
- only then publish.
