# NRB Product Universe — Interactive 3D Simulator

**Live page: https://vynxhq.github.io/jic-connection/**

The approved NRB Product Universe (Sep26) — **280 configurations across 11 product families** — as one interactive, parametric 3D build. One self-contained HTML file, no server, no internet required. The machine auto-tours itself when left alone; click anything to take over.

## One build, two worlds

A toggle top-left switches between the two connection systems that together cover the entire universe:

| World | Families | Configurations |
|---|---|---|
| **JIC · Flare Connection System** | JIC Nut, JIC Insert, Ferrule (Collar), Steel Tube End, Male Fittings, 45° Bend, 90° Bend | **82** |
| **MP · HP · Cone & Thread System** | Adaptor, Male Connector, Female Connector, Pipe Nipple — the coned & threaded world (gland nut + collar + 60° cone seat, L.H. threads, MP to 20K / HP to 60K) | **198** |
| | | **280 / 280** |

Every configuration is a picker state in the **CONFIGURE** panel — topology or family, size row (DASH-02 to DASH-32, UNF/BSPP/NPT, 6K–20K classes) and material — never a separate build. The machine rebuilds live: geometry, thread pitch and major diameter, hex, seat circle, torque spec, working and proof pressures.

## What's inside

- **The make-up story, four phases** — Flare · Thread · Seat · Prove, scrubbed from the strip or the drag bar; every gauge, chart and callout reads the same model that moves the parts
- **Cutaways** — x-ray glass, longitudinal section with adjustable depth, solid
- **Views** — Hero, Flare/Gland, Thread, Seat, Bore (down-axis), Over — keys 1–6; `W` toggles worlds
- **UNIVERSE overlay** — the coverage ledger: all 11 families, their configuration counts, and which world covers them
- **Exploded walk-round** in the auto tour

## Design language

Styled in the approved NRB design system: daylight panels on Waterline hairlines floating over the dawn-sky studio ramp (the warm low-sun bounce is what makes machined stainless read as metal), Montserrat headings, Deep Channel as the only action blue, Harbor Depth data accents, tabular numerals, film grain at 4.5%.

## Data provenance

- **Configurations**: NRB Product Universe (Sep26) — 280 rows, parsed verbatim; the single source of scope
- **Engineering constants**: thread geometry parsed from the workbook's own thread strings; gland A/F and L.H. thread tables from NRB's published catalogue practice; flare 37° per SAE J514; cone 60° per coned & threaded practice; torque and proof values nominal — pending NRB engineering sign-off

## Credits

Built with the open-source **[teardown](https://github.com/elvarofficial/teardown)** skill (MIT) — the runtime kit, review loop and build pipeline come from there. Prototype for internal review.
