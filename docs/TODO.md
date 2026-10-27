# Van Halen: Rock or Die! — Project To-Do List

**Version:** 0.1  
**Date:** 2026-10-27  
**Target:** Atari 800XL  
**Status:** Story and packaging concept chosen; gameplay not implemented  
**Companion documents:** [Game Design](GAME_DESIGN.md) · [Art Assets](ART_ASSETS.md) · [Technical Design](TECHNICAL_DESIGN.md)

> Living checklist. Checked items indicate decisions or repository setup already accomplished, **not** that game features exist in working code. An unchecked proposal is not a product commitment.

## Phase 1 — Story and overall design

- [x] Choose official game title: **Van Halen: Rock or Die!**.
- [x] Choose time period: **1984**.
- [x] Establish interconnected road, concert, and finale mini-games.
- [x] Establish desired tone: somewhat serious rock adventure with some humor.
- [x] Name the band vehicle **Vanama**.
- [x] Identify Victor Voss / Control Records as the conspiracy behind the shutdowns.
- [x] Link mysterious venue power drain to the **Silence Machine**.
- [x] Establish narrative arc: tour → briefcase clue → New York final concert → basement → boss guitar duel → encore.
- [x] Establish fans as overenthusiastic obstacles and executives as deliberate villains.
- [ ] Decide the exact number of gigs, city order and unique challenges at each.
- [ ] Write concise opening text, between-stage cutscenes and final ending script.
- [ ] Determine if the game loops or offers a harder second tour after victory.

## Phase 2 — Road chase mechanics

- [x] Choose Eddie-on-roof guitar-note attacks as the central road combat visual.
- [x] Choose fans boarding the van as a **slowdown** penalty.
- [x] Choose executives boarding from black limousines as a **cash theft** penalty.
- [x] Establish cash collection and a minimum cash threshold to play each gig.
- [x] Establish deadline pressure; late arrival can mean missing a gig.
- [ ] Choose road stage camera, orientation and scrolling.
- [ ] Design single-joystick driving plus aiming/firing controls.
- [ ] Define vehicle spawn patterns, enemy movement, collision and note hit behavior.
- [ ] Define boarding chance, limits, passenger removal and speed penalties.
- [ ] Define cash theft rate, cash pickup behavior and exact road payout.
- [ ] Define time, venue arrival, late/missed gig and recovery rules.
- [ ] Prove resource economy cannot trap the player without a recoverable path.
- [ ] Prototype first playable road loop.

## Phase 3 — Concert mechanics

- [x] Establish stage-crashing fans and gear-stealing record executives.
- [x] Establish crowd-excitement **Rock Meter**.
- [x] Establish **Venue Power** drain as a show-ending threat.
- [x] Establish that successful shows earn money toward the next gig.
- [ ] Choose exact player representation and controls during a concert.
- [ ] Make performing the show a fun, interactive mini-game.
- [ ] Design fan crowding/stage-boarding defense.
- [ ] Design executive equipment-theft AI and recovery.
- [ ] Design actionable venue-power restoration / drain resistance.
- [ ] Tune the Rock Meter, power meter and cash rewards.
- [ ] Specify blackout and equipment-loss failure/retry behavior.
- [ ] Prototype the first playable concert.

## Phase 4 — Finale

- [x] Establish final New York arena broadcast and emergency-power performance.
- [x] Establish basement reveal beneath final venue.
- [x] Establish Voss's Silence Machine powered by stolen electrical energy.
- [x] Establish Eddie's final guitar-note attack / electronic wave boss concept.
- [ ] Design the basement camera, map, rooms, gates and enemies.
- [ ] Prototype Voss battle, amplifier destruction and final solo input.
- [ ] Build final cutscene: venues relight, encore, Vanama sunset/limo gag.
- [ ] Test finale for difficulty and satisfying payoff.

## Phase 5 — Packaging, branding and art

- [x] Select **highway-chase Option 1** from three packaging directions.
- [x] Choose a **lighter sky / daylight** box background.
- [x] Choose portrait box target **7.5 in high × 5.5 in wide × 1 in deep**.
- [x] Choose **Atari 800XL** branding (correct erroneous 2600 mockup).
- [x] Establish composition: Vanama center; groupies in Pinto-like car **left**; execs/limos **right**.
- [x] Establish matching box and black cartridge art.
- [ ] Import approved concept image binaries to assets/cover-art/.
- [ ] Create print-safe original layout/dieline and exact box measurements.
- [ ] Create simplified readable cartridge label.
- [ ] Choose/recreate game logo and complete licensed/rights clearance as needed.
- [ ] Design in-game title screen, road sprites, concert sprites, basement sprites, HUD.

## Phase 6 — Technical architecture and assembly

- [x] Create or identify dedicated GitHub repository.
- [x] Mirror Gas Blasters '82 repository file/folder structure.
- [x] Create tailored Game Design, Art Assets, Technical Design, and TODO documents.
- [ ] Establish a working MAC/65 assembly/edit/debug/run workflow.
- [ ] Select emulator(s) and any target real hardware testing.
- [ ] Choose display mode, memory map, PMG strategy, sound implementation and asset pipeline.
- [ ] Commit first minimal runnable assembly program to src/.
- [ ] Add input handling, scrolling, collisions, HUD and state transitions.
- [ ] Add build/test instructions and practical performance checklist.

## Phase 7 — Sound and music

- [ ] Determine music style for title, drive, concert, boss and victory screens.
- [ ] Implement original/licensable POKEY music cues and effects.
- [ ] Prototype guitar-note shot, collision, power-drain and stage crowd audio.
- [ ] Check music/likeness/logos licensing requirements for distribution.

## Phase 8 — Playtesting and release

- [ ] Review first road/combat prototype with user.
- [ ] Review concert meter/power economy prototype with user.
- [ ] Tune learning curve and penalties.
- [ ] Test on target emulator and real Atari 800XL hardware if available.
- [ ] Create release build, instructions and proper packaged artwork.
- [ ] Confirm distribution rights and credits.
- [ ] Publish and version a release after tested build exists.

## Ongoing maintenance

- [ ] Keep confirmed vs proposed decisions clearly differentiated.
- [ ] Update art and game design documents after each design change.
- [ ] Record technical decisions only after testing.
- [ ] Track and close completed tasks based on evidence, not intentions.

## Change log

- **2026-10-27 — v0.1:** Created initial prioritized plan and recorded current decisions.
