# CrimsonCombat

A Roblox combat package for the Crimson project.

## Repository layout

```text
CrimsonCombat/
├── README.md
├── src/
│   └── CombatServer.luau
├── client/
│   └── CombatClient.luau
├── installers/
│   └── CrimsonCombatInstaller.luau
└── docs/
    └── SETUP.md
```

## Files

- `src/CombatServer.luau` — server-side combat authority.
- `client/CombatClient.luau` — Combat GUI and client input.
- `installers/CrimsonCombatInstaller.luau` — Studio installer that creates the Roblox-side scripts.
- `docs/SETUP.md` — setup notes.

## Security model

Damage and other gameplay effects that affect other players should be validated and applied by the Roblox server. The client is responsible for UI/input and requests; it should not be trusted to choose arbitrary damage values or targets.

## GitHub raw files

After pushing this repository to GitHub, raw file addresses will follow this pattern:

```text
https://raw.githubusercontent.com/<OWNER>/CrimsonCombat/main/src/CombatServer.luau
https://raw.githubusercontent.com/<OWNER>/CrimsonCombat/main/client/CombatClient.luau
https://raw.githubusercontent.com/<OWNER>/CrimsonCombat/main/installers/CrimsonCombatInstaller.luau
```

Replace `<OWNER>` with your GitHub username or organization.

## Notes

Do not put API keys, passwords, tokens, or other secrets in this repository. If the repository is only for your game, consider keeping it private.
