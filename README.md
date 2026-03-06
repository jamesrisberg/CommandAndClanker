# Welcome Back, Commander

Command & Conquer Tiberian Sun voice lines as Claude Code hooks. 

## Files

- `GDI/` — GDI EVA voice lines (WAV files)
- `NOD/` — NOD CABAL voice lines (WAV files)
- `GDI-hooks.json` — Hook configuration using GDI sounds
- `NOD-hooks.json` — Hook configuration using NOD sounds

## Setup

1. Clone this repo to `~/dev/CommandAndClanker`
2. Copy the contents of either `GDI-hooks.json` or `NOD-hooks.json` into your `~/.claude/settings.json` (top level peer of "permissions")
3. Start a Claude Code session and enjoy

### What plays when

| Event | Sound |
|---|---|
| Session starts | "Establishing battlefield control, standby" |
| Task completes | "Construction complete" |
| Idle | "Select target" |
| Permission prompt | "Incoming transmission" |
| Session ends | "Battlefield control offline" |
| Context compaction | "Insufficient funds" |
| Subagent spawns | "Reinforcements have arrived" |

Other hooks exist, and all the game audio files are available so have fun!
