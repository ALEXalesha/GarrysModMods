# GarrysModMods

**Planned.** A collection of Garry's Mod addons: physics toys, disasters, a learning car and an arcade cabinet
with real mini-games inside. Every addon works in multiplayer.

[Русская версия](README.ru.md)

[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)
[![Status](https://img.shields.io/badge/status-planned-lightgrey)](#status)
[![Garry's Mod](https://img.shields.io/badge/Garry's_Mod-Lua_addons-1a9fff)](https://gmod.facepunch.com/)

[![Built with Claude Code](https://img.shields.io/badge/Built_with-Claude_Code-D97757?logo=claude&logoColor=white)](https://claude.com/claude-code)

Code, tests and docs are written by Claude (Anthropic) in Claude Code. Ideas, testing and decisions - Alexey.

## Status

There is no code yet. Ten addons are chosen out of about a hundred ideas; work starts after the current projects.
This README describes the plan, not working addons.

## Planned addons

| Addon | What it does |
|---|---|
| Black Box | Records what happened around you and plays it back from any camera. |
| Disasters | Earthquake, tornado and tsunami that really break and carry props. |
| Catapult and FPV drone | Build a catapult and launch props; fly a first-person drone. |
| Learning Car | A small car that learns to drive a track by itself - you watch it get better. |
| Arcade Cabinet | A cabinet with mini-games on its screen (from the author's AI game collection); some games can be "pulled out" into 3D right on the map. |
| Mini Paint | Draw on any surface with a brush, shapes and colors. |
| Cutter | Cut props into pieces along a line you choose. |
| Shrink and Grow | Make players and props tiny or huge. |
| 3D Printer | A printer prop that "prints" a model layer by layer. |
| Black Hole | Pulls in everything around it, with growing strength. |

## How it will be made

- Lua addons for Garry's Mod, one folder per addon, a shared library for common code.
- Multiplayer from the start: the server owns the game state, clients only draw.
- Each addon is checked for similar ones in the Steam Workshop first, so it brings something new.
- Publishing: Steam Workshop (gmad and gmpublish) and this repository.

## License

MIT - see [LICENSE](LICENSE).
