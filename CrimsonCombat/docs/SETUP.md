# CrimsonCombat setup

## Recommended Roblox placement

- Server code: `ServerScriptService`
- Client GUI/input: `StarterPlayer > StarterPlayerScripts`
- Any shared RemoteEvents/configuration should be created by the server package or kept in `ReplicatedStorage` as appropriate.

## Using the installer

The installer is provided for Roblox Studio. Run it from the Studio Command Bar in your own place, then inspect the generated instances before publishing.

## GitHub workflow

1. Create a GitHub repository named `CrimsonCombat`.
2. Upload this folder while preserving its structure.
3. Commit changes as you update the combat system.
4. Use GitHub's **Raw** view when you need the raw contents of a specific file for your own game's server-side loader.

## Important

A GitHub URL is a code distribution/versioning mechanism; it is not a security boundary. Keep authoritative gameplay validation inside Roblox's server environment.
