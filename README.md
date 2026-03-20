# Welcome Back, Commander

Game voice lines as Claude Code hooks.

## Sound Packs

### Command & Conquer: Tiberian Sun

- `GDI/` — GDI EVA voice lines (WAV files)
- `NOD/` — NOD CABAL voice lines (WAV files)
- `GDI-hooks.json` / `NOD-hooks.json` — Hook configurations

### StarCraft II

- `Terran/` — SCV, Marine, and Adjutant voice lines (OGG files)
- `Zerg/` — Queen creature sounds (OGG files)
- `Protoss/` — Zealot, Carrier, and Executor voice lines (OGG files)
- `Terran-hooks.json` / `Zerg-hooks.json` / `Protoss-hooks.json` — Hook configurations

## Setup

1. Clone this repo to `~/dev/CommandAndClanker`
2. Copy the `hooks` section from any hooks JSON file into your `~/.claude/settings.json` (top level peer of "permissions")
3. Start a Claude Code session and enjoy

### What plays when

| Event | C&C: GDI / NOD | SC2: Terran | SC2: Zerg | SC2: Protoss |
|---|---|---|---|---|
| Session starts | "Establishing battlefield control" | SCV Ready | Queen Ready | Carrier has arrived |
| Task completes | "Construction complete" | SCV "Job's finished" | Queen Yes | Warp-in complete |
| Idle | "Select target" | SCV "What?" | Queen What | Zealot "Command me" |
| Permission prompt | "Incoming transmission" | "Base under attack" | Queen Yes | "Base under attack" |
| Session ends | "Battlefield control offline" | "Command center upgrade complete" | Queen Yes | "Research complete" |
| Context compaction | "Insufficient funds" | "Not enough minerals" | Queen Yes | "Additional pylons required" |
| Subagent spawns | "Reinforcements have arrived" | SCV Ready | Queen Yes | Zealot "My life for Aiur!" |

Other hooks exist, and all the game audio files are available so have fun!
