# Operation Cosmoform

*Asteroid Belt Mining Continuum* is a mobile-first 3D arcade mission game. You design self-replicating drones with TCTA, then mine the asteroid belt and build fuel waystations for the crewed ship **the Marauder**. After that, the network spreads to the outer planets and the stars, with the uncrewed **Marauder's Daughter**.

## Links

- **Play (phone, tablet or desktop, no login, works offline once loaded):** https://nhartman000.github.io/asteroid-belt-mining-continuum-play/
- **Demo video (29.5 s, narrated):** https://nhartman000.github.io/asteroid-belt-mining-continuum-play/demo/operation-cosmoform-demo.mp4 · demo page with the voiceover script: https://nhartman000.github.io/asteroid-belt-mining-continuum-play/demo.html
- **Source code:** https://github.com/nhartman000/operation-cosmoform

## Tutorial (first launch)

The splash screen leads straight into an interactive tutorial of about a minute. It has 16 short steps, and each one spotlights one thing, shows a hand gesture, and waits for you to do it. When you do, it says "✓", plays a sound, and moves on. Controls you haven't learned yet stay hidden until their step, and if you pause for about 6 s the hint pulses again.

1. Tap Miners to select them
2. Tap empty space to send them
3. Press and hold to rally
4. Two fingers: swipe down to zoom
5. Tap Ice Harvester to design it
6. Tap a glowing part — watch it narrow (one TCTA step)
7. Drag to set your fleet size
8. Tap Launch!
9. Watch: they land and build
10. Tap Ceres to see its waystation
11. Tap to send the Marauder
12. Tap 🌌 to zoom out to the stars
13. Tap to launch seed probes
14. Tap Console to go home
15. Tap Saved games
16. Tap Save as new

- **Skip:** tap **Skip ▸▸** (top right, always visible), swipe with four fingers, or press Esc.
- **Replay:** use **🎓 Tutorial** on the start screen or the Console, or **🎓 Replay tutorial** in 📚 About. If you replay during a game, the game is autosaved first and you can return to it at the end.
- Finishing or skipping is remembered on the device, so returning players go straight to the start screen. Advanced panels show a one-line "first time here?" tip the first time you open them.

## Controls

| Action | Touch | Mouse / keyboard |
|---|---|---|
| Select a drone group | Tap a group chip (ALL, Miners…) | Click |
| Send the selected group (waypoint) | Tap empty space | Click |
| Send a group to an asteroid | Tap the asteroid | Click |
| Rally the swarm | Press and hold, release to resume | Hold the mouse button |
| Rotate the camera | One-finger drag | Drag |
| Zoom | Two-finger swipe ↓ to zoom in, ↑ to zoom out (pinch also works), or ＋ / − | Mouse wheel |
| Fly to an asteroid (Solar System view) | Tap it | Click |
| Zoom out to deep space | 🌌 button, or keep zooming out past Neptune | Same |
| Drone POV | Stick to steer, THRUST, MINE, TRANSFER, BRAKE | Same buttons |
| Skip the intro or tutorial | Four-finger swipe or Skip | Esc |

## How the game works

### Stage 1 · Drone design with TCTA
In the Drone Design Studio you design one drone for each job in four families: replicators, builders, miners and payload transporters, plus an optional terraformer kit. The design method is **TCTA (Trajectory-Constrained Transform Algebra)** by Nicholas Hartman / American Milestone Inc.:
- every design step (transform) has to stay inside the admissible space Ω(C), so mass, power, heat and cost all fit;
- the order of steps (the trajectory) resolves a design family and narrows the search;
- an HDRP predictor shows a ghost marker for the likely next step.

If you're in a hurry, tap **✨ Auto-design all**. Then set the fleet ratio under **② Fleet mix** and tap **🚀 Launch mission**.

### Stage 2 · Swarm, factories and waystations in the belt
The swarm cruises to real asteroids (Ceres, Vesta, Psyche, Bennu and others, from the JPL Small-Body Database). There it lands, mines, and turns drones into factories that print more drones. Haulers carry seed payloads on to new asteroids. Ice-bearing sites become **waystations** that turn water ice into H₂/O₂ propellant, with a life-support readiness meter. Mission events ask for team decisions, and the mission ends with a scored debrief. Local multiplayer works for 1–4 players with roles on one device.

### Stage 3 · Outer planets and deep space
- **Solar System:** all 8 planets (JPL mean orbital elements), 8 resource moons (Luna, Phobos, Europa, Ganymede, Callisto, Titan, Enceladus, Triton), and 5 dwarf planets / Kuiper belt objects (Pluto, Eris, Makemake, Haumea, Arrokoth).
- **Waystation chain:** belt → Jupiter (Callisto) → Saturn (Titan/Enceladus) → Uranus → Neptune (Triton) → Kuiper belt → interstellar jump-off at about 120 AU. Beyond Jupiter, fission power replaces solar.
- **Galaxy map:** zoom from the Solar System to the stellar neighborhood, the Orion Arm and the whole Milky Way. Exoplanet systems from the NASA Exoplanet Archive are placed by real distance and galactic coordinates. The spiral arms are a procedural model.
- **TCTA star targeting:** choose propulsion and cruise speed, narrow every system down to the admissible ones (trip-time limit and rocket-equation mass ratio), then launch von Neumann seed probes. Each arrival builds a factory and sends more probes, so a replication wave spreads across the galaxy.

### The two ships
- **The Marauder** is the **crewed** (human) ship of the asteroid belt and Solar System. It refuels at your waystations along the chain.
- **The Marauder's Daughter** is the **uncrewed**, autonomous interstellar ship, and it is **FUTURE TECH**. It is built at the jump-off by the swarm that the Marauder's waystations made possible. It hops waystation to waystation (colony shipyards and relay depots no more than ~7 ly apart) for fuel, repairs and spare parts. It holds position and wears down if a waystation isn't ready.

### Optional seed vault (panspermia)
The Daughter can carry an optional **seed vault**: hypothetical directed panspermia with hardy microbes and a genetic archive. It is **off by default** and labeled **SPECULATIVE · HYPOTHETICAL**. It comes with an ethics note on NASA/COSPAR planetary protection, because seeding a world that may already host life could harm that life and spoil the search for it. Seeded worlds show in magenta on the map.

### He-3 post-game round
After a mission debrief, the bonus **⚛ Helium-3 Engineering Round** unlocks. You plot He-3 mine sites along your routes and compare chemical, ion and fusion propulsion. Fusion and He-3 are **FUTURE TECH**. **Water ice stays the main fuel** in the game, and He-3 appears only in this optional round.

### Saved games
You get up to 20 named save slots plus an autosave, stored in this browser. Each slot shows a thumbnail, date, play time, stage and stats. You can save, overwrite, load, rename and duplicate slots. Delete has a confirmation step ("This can't be undone"). You can also export or import a save as a .json file or a share code. A save from an older version is moved into the list automatically, along with the ship's new name.

## Data sources

Values are bundled snapshots, so the game runs offline. Imported values are labeled **IMPORTED**, sensor readings are **SIMULATED**, and the game never claims a live connection unless a request really succeeds.
- JPL Small-Body Database API (asteroid targets, bundled snapshot): https://ssd-api.jpl.nasa.gov/doc/sbdb.html · lookup: https://ssd.jpl.nasa.gov/tools/sbdb_lookup.html
- JPL Approximate Positions of the Planets (mean orbital elements): https://ssd.jpl.nasa.gov/planets/approx_pos.html · JPL Solar System Dynamics: https://ssd.jpl.nasa.gov/
- NASA Exoplanet Archive, Planetary Systems Composite Parameters (bundled snapshot fetched 2026-11-15): https://exoplanetarchive.ipac.caltech.edu/
- NASA Science: Solar System https://science.nasa.gov/solar-system/ · Asteroids https://science.nasa.gov/solar-system/asteroids/ · Ceres https://science.nasa.gov/dwarf-planets/ceres/
- Missions: Dawn https://science.nasa.gov/mission/dawn/ · Psyche https://science.nasa.gov/mission/psyche/ · OSIRIS-REx https://science.nasa.gov/mission/osiris-rex/ · OSIRIS-APEX https://science.nasa.gov/mission/osiris-apex/ · NEAR Shoemaker https://science.nasa.gov/mission/near-shoemaker/ · Voyager https://science.nasa.gov/mission/voyager/
- NASA Basics of Space Flight (orbits, Hohmann transfers, rocket equation): https://science.nasa.gov/learn/basics-of-space-flight/ · Deep Space Network: https://www.nasa.gov/communicating-with-missions/dsn/
- Breakthrough Starshot (light sail, future tech): https://breakthroughinitiatives.org/initiative/3 · Project Daedalus, British Interplanetary Society (fusion probe study, future tech): https://www.bis-space.com/what-we-do/projects/project-daedalus/

Models used include Hohmann transfer time and Δv, the Tsiolkovsky rocket equation, solar flux ∝ 1/r², radio light-time, equilibrium temperature, and the electrolysis minimum. Game rates are simplified and labeled simulated.

## Demo video

The demo is **29.5 s, 1080×1920, narrated** (en-US-AndrewNeural text-to-speech, with captions that match the voiceover word for word). The only music is the game's Stage 1 design-screen song. Most of it is real gameplay capture with cinematic camera moves and transitions. A **5.85 s hand-drawn-style cartoon of the Marauder's Daughter is AI-generated**: an original ship design made with AI image and video generation tools, with no text or agency logos. The demo page says so too.

> Operation Cosmoform. Design self-replicating drones with TCTA. The swarm lands, mines, and builds factories that build more drones. Waystations turn ice into fuel for the Marauder, our crewed ship. Then the network leaves the belt for the stars. The uncrewed Marauder's Daughter hops waystation to waystation across the galaxy.

## Tech and tools

- One self-contained HTML file: vanilla JavaScript, Three.js (WebGL) for 3D, Web Audio for procedural music and sound effects, and localStorage for saves. No server, no login, no tracking.
- Mobile-first touch UI with touch targets of at least 44 px. Tested at phone portrait (390×844) and tablet (1024×768) with Playwright on headless Chromium.
- Demo video tooling: Playwright frame capture under a virtual clock, FFmpeg, and edge-tts. Its scripts are in `tools/demo-video/` in the source repo.

## Disclaimer

All values are **simulated** or approximate reference values for learning, unless labeled imported. This is an arcade game, **not a flight-certified mission planning system**. Interstellar propulsion, fusion, He-3 and exoplanet resources are FUTURE TECH / SPECULATIVE.

NASA Space Apps Challenge entry · not affiliated with or endorsed by NASA. "NASA" appears only as plain text naming data sources. No NASA or Space Apps logos are used.

## This repository

This repo is the GitHub Pages build of the game: `index.html`, the `demo.html` page and `demo/operation-cosmoform-demo.mp4`. The source, build script and video tooling are at https://github.com/nhartman000/operation-cosmoform.
