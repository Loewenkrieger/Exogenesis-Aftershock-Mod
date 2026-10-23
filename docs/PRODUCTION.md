# Production overview — 0.3.2

Overdrive scales process speed and power demand once. Unfed, output/return-blocked and disabled plants draw no process power. A Calamity cell remains capped at 9.6 million energy with overdrive and requires at least 12 million charging energy.

Quantities are per batch. Flow, cooling, consumed power and generation are per second. Inputs work on every side. Only output directions rotate with the building.

Coolant returns on the right (80%); liquid products use front/left/back. Full byproduct or return outlets stop production. Power failure pauses. Deliberately aborting a batch discards reserved ingredients. Cartridges hold 100 units and are returned by unpacking.

| Building | Footprint | Recipes |
|---|:---:|---:|
| Siradamite synthesizer | 5×5 | 1 |
| Beryllium synthesizer | 5×5 | 1 |
| Tungsten synthesizer | 5×5 | 1 |
| Acid processor | 3×3 | 1 |
| Axinian condenser | 5×5 | 2 |
| Pyroplasma synthesizer | 5×5 | 1 |
| Rutuxium refinery | 5×5 | 1 |
| Calamity cell charger | 5×5 | 1 |
| Ceramic and casing works | 3×3 | 2 |
| Matrix fabricator | 3×3 | 1 |
| Coil fabricator | 3×3 | 1 |
| Special ammunition assembler | 5×5 | 3 |
| Stabilized coolant plant | 3×3 | 1 |
| Coolant regenerator | 3×3 | 1 |
| Reclaimer and disposer | 4×4 | 1 |
| Gas packer | 2×2 | 5 |
| Gas unpacker | 2×2 | 5 |
| Industrial buffer | 3×3 | 0 |
| Jupiteium cycle reactor | 5×5 | 1 |
| Axinian fusion reactor | 7×7 | 1 |
| Calamity pulse reactor | 7×7 | 1 |
| Ground unit fabricator | 7×7 | 1 |
| Air unit fabricator | 7×7 | 1 |
| Support unit fabricator | 5×5 | 1 |

## Siradamite synthesizer

**Siradamite synthesis** — 20 s; 16000 power/s; heat 40; coolant 0/s; generation 0/s gross.

- Input: `exogenesis-astrolite` × 8, `silicon` × 12, `exogenesis-dytrix` × 4; liquids: `exogenesis-acid` × 40.
- Output: `exogenesis-siradamite` × 4; liquids: `slag` × 20; flows/s: —.


## Beryllium synthesizer

**Beryllium synthesis** — 30 s; 16000 power/s; heat 40; coolant 0/s; generation 0/s gross.

- Input: `sand` × 30, `metaglass` × 12, `silicon` × 16; liquids: `hydrogen` × 60.
- Output: `beryllium` × 6; liquids: `slag` × 30; flows/s: —.


## Tungsten synthesizer

**Tungsten synthesis** — 30 s; 16000 power/s; heat 60; coolant 0/s; generation 0/s gross.

- Input: `exogenesis-osmium` × 12, `thorium` × 8, `silicon` × 16; liquids: `hydrogen` × 90.
- Output: `tungsten` × 4; liquids: `slag` × 30; flows/s: —.


## Acid processor

**Wastewater processing** — 10 s; 4000 power/s; heat 0; coolant 0/s; generation 0/s gross.

- Input: `exogenesis-dytrix` × 2; liquids: `exogenesis-liquid-radoactive-water` × 60, `water` × 30.
- Output: —; liquids: `exogenesis-acid` × 40, `slag` × 15; flows/s: —.


## Axinian condenser

**Axinian condensation** — 15 s; 16000 power/s; heat 0; coolant 5/s; generation 0/s gross.

- Input: `exogenesis-gamma-green` × 6; liquids: `exogenesis-cold-plasma` × 90, `hydrogen` × 60.
- Output: —; liquids: `exogenesis-axinian` × 60; flows/s: —.

**Arkycite synthesis** — 20 s; 16000 power/s; heat 20; coolant 5/s; generation 0/s gross.

- Input: `spore-pod` × 16; liquids: `oil` × 80, `hydrogen` × 60.
- Output: —; liquids: `arkycite` × 40; flows/s: —.


## Pyroplasma synthesizer

**Pyroplasma synthesis** — 20 s; 16000 power/s; heat 60; coolant 0/s; generation 0/s gross.

- Input: `exogenesis-volcanite` × 8; liquids: `hydrogen` × 90, `slag` × 120.
- Output: —; liquids: `exogenesis-pyroplasma` × 60; flows/s: —.


## Rutuxium refinery

**Rutuxium refining** — 25 s; 16000 power/s; heat 40; coolant 5/s; generation 0/s gross.

- Input: `phase-fabric` × 6, `exogenesis-gamma-green` × 8, `exogenesis-xytranite` × 10; liquids: `exogenesis-acid` × 60.
- Output: `exogenesis-rutuxium` × 4; liquids: `slag` × 30; flows/s: —.


## Calamity cell charger

**Calamity charging** — 240 s; 50000 power/s; heat 0; coolant 5/s; generation 0/s gross.

- Input: `exogenesis-blue-titan-alloy` × 8, `exogenesis-omega-blue` × 10, `exogenesis-rutuxium` × 6, `exogenesis-aftershock-impulse-coil` × 4, `exogenesis-annihilation-crystal` × 2; liquids: —.
- Output: `exogenesis-calamity-energy-cell` × 1; liquids: —; flows/s: —.


## Ceramic and casing works

**Thermoceramic** — 12 s; 4000 power/s; heat 20; coolant 0/s; generation 0/s gross.

- Input: `oxide` × 4, `metaglass` × 8, `silicon` × 6; liquids: —.
- Output: `exogenesis-aftershock-thermoceramic` × 6; liquids: —; flows/s: —.

**Gas cartridges** — 12 s; 4000 power/s; heat 0; coolant 0/s; generation 0/s gross.

- Input: `exogenesis-osmium` × 2, `plastanium` × 4, `exogenesis-aftershock-thermoceramic` × 2; liquids: —.
- Output: `exogenesis-aftershock-gas-cartridge` × 4; liquids: —; flows/s: —.


## Matrix fabricator

**Control matrices** — 15 s; 4000 power/s; heat 0; coolant 5/s; generation 0/s gross.

- Input: `silicon` × 12, `phase-fabric` × 4, `exogenesis-gamma-green` × 4, `exogenesis-xanium` × 4; liquids: —.
- Output: `exogenesis-aftershock-control-matrix` × 4; liquids: —; flows/s: —.


## Coil fabricator

**Impulse coils** — 12 s; 4000 power/s; heat 0; coolant 0/s; generation 0/s gross.

- Input: `copper` × 20, `exogenesis-alpha-yellow` × 4, `exogenesis-voltirium-alloy` × 4; liquids: —.
- Output: `exogenesis-aftershock-impulse-coil` × 4; liquids: —; flows/s: —.


## Special ammunition assembler

**Breakthrough ammunition** — 8 s; 16000 power/s; heat 20; coolant 5/s; generation 0/s gross.

- Input: `exogenesis-jupiteium` × 6, `exogenesis-osmium` × 4, `exogenesis-aftershock-thermoceramic` × 2; liquids: —.
- Output: `exogenesis-aftershock-breakthrough-ammo` × 8; liquids: —; flows/s: —.

**Pulse ammunition** — 8 s; 16000 power/s; heat 20; coolant 5/s; generation 0/s gross.

- Input: `exogenesis-alpha-yellow` × 4, `exogenesis-rutuxium` × 2, `exogenesis-aftershock-impulse-coil` × 2; liquids: —.
- Output: `exogenesis-aftershock-pulse-ammo` × 6; liquids: —; flows/s: —.

**Suppression ammunition** — 8 s; 16000 power/s; heat 20; coolant 5/s; generation 0/s gross.

- Input: `exogenesis-gamma-green` × 4, `exogenesis-xytranite` × 4, `exogenesis-siratla-diamond` × 2, `exogenesis-aftershock-control-matrix` × 2; liquids: —.
- Output: `exogenesis-aftershock-suppression-ammo` × 6; liquids: —; flows/s: —.


## Stabilized coolant plant

**Coolant stabilization** — 1 s; 8000 power/s; heat 0; coolant 0/s; generation 0/s gross.

- Input: —; liquids: `exogenesis-osmilium-liquid` × 30.
- Output: —; liquids: `exogenesis-aftershock-stabil-coolant` × 30; flows/s: —.


## Coolant regenerator

**Coolant regeneration** — 1 s; 10000 power/s; heat 0; coolant 0/s; generation 0/s gross.

- Input: —; liquids: `exogenesis-aftershock-warm-coolant` × 30.
- Output: —; liquids: `exogenesis-aftershock-stabil-coolant` × 30; flows/s: —.


## Reclaimer and disposer

**Basic material recycling** — 15 s; 4000 power/s; heat 0; coolant 0/s; generation 0/s gross.

- Input: `scrap` × 20; liquids: `slag` × 60.
- Output: `copper` × 4, `lead` × 4, `graphite` × 2, `sand` × 2; liquids: —; flows/s: —.


## Gas packer

**Pack hydrogen** — 2 s; 1000 power/s; heat 0; coolant 0/s; generation 0/s gross.

- Input: `exogenesis-aftershock-gas-cartridge` × 1; liquids: `hydrogen` × 100.
- Output: `exogenesis-aftershock-packed-hydrogen` × 1; liquids: —; flows/s: —.

**Pack ozone** — 2 s; 1000 power/s; heat 0; coolant 0/s; generation 0/s gross.

- Input: `exogenesis-aftershock-gas-cartridge` × 1; liquids: `ozone` × 100.
- Output: `exogenesis-aftershock-packed-ozone` × 1; liquids: —; flows/s: —.

**Pack nitrogen** — 2 s; 1000 power/s; heat 0; coolant 0/s; generation 0/s gross.

- Input: `exogenesis-aftershock-gas-cartridge` × 1; liquids: `nitrogen` × 100.
- Output: `exogenesis-aftershock-packed-nitrogen` × 1; liquids: —; flows/s: —.

**Pack cyanogen** — 2 s; 1000 power/s; heat 0; coolant 0/s; generation 0/s gross.

- Input: `exogenesis-aftershock-gas-cartridge` × 1; liquids: `cyanogen` × 100.
- Output: `exogenesis-aftershock-packed-cyanogen` × 1; liquids: —; flows/s: —.

**Pack axinian** — 2 s; 1000 power/s; heat 0; coolant 0/s; generation 0/s gross.

- Input: `exogenesis-aftershock-gas-cartridge` × 1; liquids: `exogenesis-axinian` × 100.
- Output: `exogenesis-aftershock-packed-axinian` × 1; liquids: —; flows/s: —.


## Gas unpacker

**Unpack hydrogen** — 2 s; 1000 power/s; heat 0; coolant 0/s; generation 0/s gross.

- Input: `exogenesis-aftershock-packed-hydrogen` × 1; liquids: —.
- Output: `exogenesis-aftershock-gas-cartridge` × 1; liquids: `hydrogen` × 100; flows/s: —.

**Unpack ozone** — 2 s; 1000 power/s; heat 0; coolant 0/s; generation 0/s gross.

- Input: `exogenesis-aftershock-packed-ozone` × 1; liquids: —.
- Output: `exogenesis-aftershock-gas-cartridge` × 1; liquids: `ozone` × 100; flows/s: —.

**Unpack nitrogen** — 2 s; 1000 power/s; heat 0; coolant 0/s; generation 0/s gross.

- Input: `exogenesis-aftershock-packed-nitrogen` × 1; liquids: —.
- Output: `exogenesis-aftershock-gas-cartridge` × 1; liquids: `nitrogen` × 100; flows/s: —.

**Unpack cyanogen** — 2 s; 1000 power/s; heat 0; coolant 0/s; generation 0/s gross.

- Input: `exogenesis-aftershock-packed-cyanogen` × 1; liquids: —.
- Output: `exogenesis-aftershock-gas-cartridge` × 1; liquids: `cyanogen` × 100; flows/s: —.

**Unpack axinian** — 2 s; 1000 power/s; heat 0; coolant 0/s; generation 0/s gross.

- Input: `exogenesis-aftershock-packed-axinian` × 1; liquids: —.
- Output: `exogenesis-aftershock-gas-cartridge` × 1; liquids: `exogenesis-axinian` × 100; flows/s: —.


## Industrial buffer

Buffer with reserves, intake targets and rotating output priority.

## Jupiteium cycle reactor

**Jupiteium cycle** — 10 s; 6000 power/s; heat 0; coolant 20/s; generation 90000/s gross.

- Input: `exogenesis-jupiteium` × 20, `exogenesis-gamma-green` × 5; liquids: `water` × 200.
- Output: —; liquids: —; flows/s: `exogenesis-liquid-radoactive-water` × 10.


## Axinian fusion reactor

**Axinian fusion** — 10 s; 40000 power/s; heat 40; coolant 20/s; generation 300000/s gross.

- Input: `exogenesis-alpha-yellow` × 8; liquids: `hydrogen` × 120, `exogenesis-axinian` × 40.
- Output: —; liquids: —; flows/s: —.


## Calamity pulse reactor

**Calamity pulse** — 24 s; 0 power/s; heat 0; coolant 30/s; generation 400000/s gross.

- Input: `exogenesis-calamity-energy-cell` × 1; liquids: —.
- Output: —; liquids: —; flows/s: —.


## Ground unit fabricator

**Atlas siege unit** — 120 s; 16000 power/s; heat 20; coolant 5/s; generation 0/s gross.

- Input: `tungsten` × 180, `exogenesis-osmium` × 180, `exogenesis-primal-red` × 60, `exogenesis-aftershock-thermoceramic` × 80, `exogenesis-aftershock-control-matrix` × 40, `exogenesis-aftershock-impulse-coil` × 40; liquids: —.
- Output: —; liquids: —; flows/s: —.
- Unit: `exogenesis-aftershock-atlas`.


## Air unit fabricator

**Kestrel combat aircraft** — 150 s; 16000 power/s; heat 0; coolant 5/s; generation 0/s gross.

- Input: `exogenesis-xanium` × 180, `exogenesis-voltirium-alloy` × 120, `exogenesis-alpha-yellow` × 100, `exogenesis-aftershock-control-matrix` × 50, `exogenesis-aftershock-impulse-coil` × 40; liquids: —.
- Output: —; liquids: —; flows/s: —.
- Unit: `exogenesis-aftershock-kestrel`.


## Support unit fabricator

**Aegis support unit** — 90 s; 16000 power/s; heat 0; coolant 5/s; generation 0/s gross.

- Input: `exogenesis-terrilium` × 100, `exogenesis-siratla-diamond` × 40, `exogenesis-gamma-green` × 100, `exogenesis-aftershock-thermoceramic` × 60, `exogenesis-aftershock-control-matrix` × 40; liquids: —.
- Output: —; liquids: —; flows/s: —.
- Unit: `exogenesis-aftershock-aegis`.


## Specialized weapons

| Weapon | Footprint |
|---|:---:|
| High-energy laser | 5×5 |
| Electric field | 5×5 |
| Energy air defense | 4×4 |
| Breakthrough cannon | 7×7 |
| Pulse launcher | 5×5 |
| Support hunter | 5×5 |
| Storm Gatling | 4×4 |
| Shard Flak | 4×4 |
| Energy repeater | 5×5 |

Of the six original heavy weapons, the first three require power and coolant: 90,000/60,000/45,000 power/s and 8/5/5 coolant/s. The other three heavy weapons require their specialized ammunition and power. The precision turret prioritizes support units.

Recycling returns only part of the input resources. Disposal consumes power to destroy scrap or liquids. A Calamity cell costs at least 12M charging energy and releases at most 9.6M; pumps, cooling and upstream production cost extra.

### Rapid-fire weapons

Storm Gatling: 15 shots/s, 120 damage, ground only, range 480; 3 graphite/s and 1,800 power/s. Build: 400 copper, 300 lead, 250 silicon, 200 titanium, 100 Osmium.

Shard Flak: 12 shots/s, 100 direct plus 45 splash damage in radius 24, air only, range 560; 2 metaglass/s and 2,400 power/s. Build: 400 lead, 250 metaglass, 300 silicon, 200 titanium, 100 Osmium.

Energy repeater: 10 shots/s, 320 damage, ground and air, range 600; 24,000 power/s and 6 stabilized coolant/s with 4.8/s warm return. Build: 800 silicon, 500 surge alloy, 500 Osmium, 150 control matrices, 150 impulse coils. Missing coolant or full return stops firing.
