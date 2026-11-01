# JIC · Female Connection — Interactive 3D Simulator

**Live page: https://vynxhq.github.io/jic-connection/**

An interactive 3D simulator of a female JIC hose connection (DASH-08, SAE J514): assemble it, torque it to spec, and prove it to 12,000 psi — with every gauge, chart and readout driven by the same numbers that move the parts.

One self-contained HTML file, no server, no internet required. The machine auto-tours itself when left alone; click anything to take over.

## What's inside

- **The machine** — JIC insert (37° flare nose, 7/16-20 UNF thread), female JIC nut (37° counterseat), crimped ferrule, hose stub — all four components of the connection, exploded in the tour
- **Four phases** — Flare · Thread · Seat · Prove, scrubbed from the strip or the drag bar
- **Real numbers** — 20 N·m seat torque, 6,000 psi working, 12,000 psi proof (2×), 1.27 mm pitch × turns = nut travel; every panel reads the same model that poses the geometry
- **Cutaways** — x-ray glass, longitudinal section (with adjustable cut depth), solid
- **Views** — Hero, Flare, Thread, Seat, Bore (down-axis), Over — keys 1–6

## Specs shown (public data)

| | |
|---|---|
| Thread | 7/16-20 UNF · 20 TPI · 1.27 mm pitch |
| Flare | 37° included (SAE J514) |
| Torque | 20 N·m (steel practice) |
| Working pressure | 6,000 psi |
| Proof pressure | 12,000 psi |
| Material | SS316 |

## Credits

Built with the open-source **[teardown](https://github.com/elvarofficial/teardown)** skill (MIT) — the runtime kit, review loop and build pipeline come from there. Dimensional data from SAE J514 / public product documentation. Prototype for internal review.
