# Operation Cosmoform

*Asteroid Belt Mining Continuum*: a mobile-first mission game about drones that build drones, mine asteroids, and build refueling waystations for the crewed ship, the Marauder’s Daughter.

Play: https://nhartman000.github.io/asteroid-belt-mining-continuum-play/

All values are simulated unless labeled imported. This is not a flight-certified planning system.

Demo video (29.5 s, narrated): https://nhartman000.github.io/asteroid-belt-mining-continuum-play/demo/operation-cosmoform-demo.mp4

## Stage 3 · Deep Space

The network doesn't stop at the belt. From the console's **STAGE 3 · Deep Space** card, or by zooming out with two fingers past Neptune, you can:

- **Solar System:** all 8 planets (JPL mean orbital elements), 8 resource moons (Luna, Phobos, Europa, Ganymede, Callisto, Titan, Enceladus, Triton), and 5 dwarf planets / Kuiper belt objects (Pluto, Eris, Makemake, Haumea, Arrokoth). Each body lists its known resources and how much sunlight reaches it.
- **Waystation chain:** belt → Jupiter (Callisto) → Saturn (Titan/Enceladus) → Uranus → Neptune (Triton) → Kuiper belt → an interstellar jump-off at about 120 AU. Beyond Jupiter, fission power takes over from solar.
- **Galaxy map:** zoom from the Solar System to the stellar neighborhood, the Orion Arm, and the whole Milky Way. Exoplanet systems are placed by real distance and galactic coordinates (Proxima Centauri out to SWEEPS and OGLE near the bulge). The spiral arms are a procedural model.
- **TCTA star targeting:** pick propulsion and cruise speed, then narrow every system down to the admissible ones (trip-time limit and rocket-equation mass ratio) and rank them by value. Launch von Neumann seed probes. Each arrival builds a factory and sends more probes, so a replication wave spreads across the galaxy. In deep space the **Marauder's Daughter** flies **UNCREWED · autonomous**, with no humans aboard. It hops waystation to waystation along the probe network: colony shipyards and relay depots spaced no more than ~7 ly apart. Each stop refuels, repairs and resupplies it. If a waystation isn't finished in time, the ship holds position and its wear rises, and low-fuel warnings show on long legs. In the Solar System it stays crewed, as before. Time runs from 1 to 1,000,000 years per second.

Interstellar propulsion (Breakthrough Starshot–class light sails, Project Daedalus–class fusion) is **FUTURE TECH**. Exoplanet resources are **SPECULATIVE · SIMULATED**. Water ice stays the main fuel. He-3 appears only in the optional post-game round.

## Data sources

- NASA Exoplanet Archive, Planetary Systems Composite Parameters (bundled snapshot fetched 2026-11-15): https://exoplanetarchive.ipac.caltech.edu/
- JPL Small-Body Database API (asteroid targets, bundled snapshot): https://ssd-api.jpl.nasa.gov/doc/sbdb.html
- JPL Approximate Positions of the Planets: https://ssd.jpl.nasa.gov/planets/approx_pos.html
- NASA Science, Solar System: https://science.nasa.gov/solar-system/
- Breakthrough Starshot: https://breakthroughinitiatives.org/initiative/3
- Project Daedalus (British Interplanetary Society): https://www.bis-space.com/what-we-do/projects/project-daedalus/
