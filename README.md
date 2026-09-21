# Fell & Sell — Cheat Engine Table

A community-focused Cheat Engine table for Fell & Sell, designed to help you inspect and modify core player values while playing.

This project started because I could not find a working trainer or table for the game, so I built one myself and kept refining it as new game versions were released.

Feel free to use, modify, and learn from it. If the game updates and breaks values, I’ll do my best to keep the table current.

## Current Version

- Game version: `1.6.1`
- Table file: `Fell & Sell v1.6.1.CT`

This table is currently built for Fell & Sell `v1.6.1` and may also work with closely related versions, depending on how the game changed internally.

## Features

This table includes a structured `PlayerStats` data set for faster inspection and editing. Some of the available values include:

### Player Stats

- Max Health
- Current Health
- Health Regen Rate
- Max Stamina
- Current Stamina
- Stamina Regen Rate
- Stamina Drain — Sprint
- Stamina Drain — Jump
- Stamina Drain — Attack
- Stamina Drain — Block
- Stamina Regen Delay
- Max Mana
- Current Mana
- Mana Regen Rate
- Attack Speed Modifier

### What this table is for

- Inspecting player stats and derived values
- Testing changes without needing a full trainer
- Faster debugging and data exploration for the game
- Learning how values are stored and structured in memory

## Requirements

- [Cheat Engine](https://www.cheatengine.org/)
- Fell & Sell `v1.6.1`
- A working understanding of Cheat Engine basics, especially attaching to the running process and enabling/disabling entries safely

## Installation

1. Download the latest `.CT` file from the repository root or the latest release.
2. Launch Fell & Sell.
3. Open the Cheat Engine table file (`Fell & Sell v1.6.1.CT`).
4. In Cheat Engine, attach to the running Fell & Sell process.
5. Enable the entries you want to use.
6. If the game is running in a different version, you may need to re-check or update addresses before using the table.

## Usage Notes

- This table is intended primarily for personal and single-player use.
- Values may shift after game updates, patches, or new builds.
- Always save your game before experimenting with live values.
- If a value stops working, re-scan or re-check the table before assuming it is broken.

## Troubleshooting

If something no longer works after an update:

- Confirm that the game version matches the table version.
- Reattach Cheat Engine to the correct process.
- Check if the game launched a new build or patched the executable.
- Open an issue with the game version you are using and a short description of the broken entry.

## Contributing

Found a broken value, discovered a new stat, or have an improvement?

Feel free to open an issue or submit a pull request. If you find something useful, sharing it helps keep the table working for more players.

## Disclaimer

This project is provided as-is, without any guarantee that it will work with every version of the game.

Use it at your own discretion. I am not responsible for corrupted saves, crashes, lost progress, or other issues caused by using the table.

## Support

If this table helped you, consider giving the repository a star.

If a feature is broken or a value no longer updates correctly, please open an issue so it can be tracked and improved.

---

**Fell & Sell Cheat Engine Table — version 1.6.1**
