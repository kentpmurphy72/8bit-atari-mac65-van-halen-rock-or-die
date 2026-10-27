# Van Halen: Rock or Die! — Technical Design

**Version:** 0.1  
**Date:** 2026-10-27  
**Status:** Planning placeholder — no architecture implemented  
**Target:** Atari 800XL (Atari 8-bit family)

## Purpose

Record implementation decisions **after** design and prototyping. Do not imply that a playable build, assembly routines or verified performance benchmarks exist yet.

## Known constraints / intentions

- Atari 800XL hardware is the target; **not** Atari 2600.
- Repository name calls out **MAC/65**. Document the actual assembler/editor/emulator/debugger workflow after it has been tested.
- The intended game combines road chase, venue defense, and a basement/boss finale, so shared input, sprites, HUD, collision, sound and scene transitions will need consideration.
- Cash, clock/deadline, Rock Meter and Venue Power are named gameplay systems, with numeric representation and implementation not yet chosen.
- Atari audio and graphics implementations must use original/licensable content.

## Engineering decisions still open

1. Atari 800XL memory layout, screen modes, player/missile graphics and scrolling design.
2. How to build/load/run MAC/65 assembly and test with DDT or another debugger.
3. Road-stage camera, draw pipeline, steering/guitar shooting with one joystick.
4. Scheduling CPU budget for traffic, collision, enemies, projectile effects and HUD.
5. Concert gameplay loop, per-venue power simulation, sound and performance feedback.
6. Basement map engine and boss-fight state machine.
7. Asset conversion pipeline and practical screen/music size budgets.
8. Starting address, executable packaging (binary/ATR/XEX/cartridge), versioning and release testing.

**Implementation state:** No committed assembly source yet. The src/ directory is reserved with a .gitkeep placeholder.

## Change log

- **2026-10-27 — v0.1:** Initial technical design placeholder; no premature architectural commitments.
