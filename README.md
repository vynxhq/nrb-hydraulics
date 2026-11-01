# NRB Flare Connection System — Interactive 3D Simulator

**Live page: https://vynxhq.github.io/jic-connection/**

The NRB flare connection system as a live, parametric 3D simulator — driven end-to-end by the **NRB Product Universe (Sep26)** workbook: 280 configurations across 11 product families, parsed verbatim into the machine.

One self-contained HTML file, no server, no internet required. The machine auto-tours itself when left alone; click anything to take over.

## The fleet — covering the full Product Universe

| Machine | Families | Configurations | Status |
|---|---|---|---|
| **1 · Flare Connection System** (this page) | JIC Nut, JIC Insert, Ferrule (Collar), Steel Tube End, Male Fittings, 45° Bend, 90° Bend | **82** | **LIVE** |
| 2 · MP/HP Adaptor | Adaptor (MP/HP × MPM/HPM/FNPT end pairs, F/L dims) | 90 | Next — awaiting reference drawings for the cone ends |
| 3 · MP/HP Connectors + Nipple | Male Connector, Female Connector, Pipe Nipple | 108 | Next — same |
| | | **280 / 280** | |

Machine 1 is fully parametric: pick a **topology** (straight · 45° · 90° · tube end · male NPT · male BSPP), a **size row** (all 17 dash/thread combinations from the workbook — DASH-02 to DASH-32, UNF and BSPP, 6K/20K classes) and a **material** (SS316 · carbon steel · brass). The machine rebuilds live: geometry, thread pitch and major diameter, hex, seat circle, torque spec, working and proof pressures — every gauge reads the same model that moves the parts.

## What's inside

- **The machine** — JIC insert (37° flare nose, real UNF/BSPP/NPT thread geometry), female JIC nut (37° counterseat landing on the computed seat circle), crimped ferrule (smooth-bore 6K / grooved 20K), hose stub or steel tube or port boss, fluid column with a fill that follows the bend
- **Four phases** — Flare · Thread · Seat · Prove, scrubbed from the strip or the drag bar
- **Real numbers, one source** — thread pitch from the thread string (e.g. DASH-08 = 3/4"-16 UNF, 1.59 mm pitch, 52 N·m), travel = turns × pitch, working 6,000 psi / proof 12,000 psi (6K class) or 20,000 / 30,000 (20K class)
- **Cutaways** — x-ray glass, longitudinal section with adjustable depth, solid
- **Views** — Hero, Flare, Thread, Seat, Bore (down-axis), Over — keys 1–6
- **UNIVERSE overlay** — the coverage ledger: all 11 families, their configuration counts, and which machine covers them

## Specs shown (from the workbook / SAE J514 practice)

| | |
|---|---|
| Threads | Per configuration row — 7/16-20 UNF … 2"-11 BSPP, NPT/BSPP male pipe |
| Flare | 37° included (SAE J514) |
| Torque | 7–190 N·m by thread (nominal, lubricated) |
| Working pressure | 6,000 psi (6K) · 20,000 psi (20K) |
| Proof pressure | 12,000 psi · 30,000 psi |
| Materials | SS303/304/316 · carbon steel · brass |

## Credits

Built with the open-source **[teardown](https://github.com/elvarofficial/teardown)** skill (MIT) — the runtime kit, review loop and build pipeline come from there. Product data from the NRB Product Universe (Sep26) and SAE J514 practice. Prototype for internal review.
