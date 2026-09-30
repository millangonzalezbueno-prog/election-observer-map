# Election Observer Map

Interactive world map of international election observers in contested regimes, 1985–2025.

**Live page:** https://millangonzalezbueno-prog.github.io/election-observer-map/

Built for *Witnesses without weapons: when do international observers protect elections, and when do they launder them?*
(Being a Politician: An International Perspective, Sciences Po, Fall 2026).

## Data

- Coppedge, Michael, et al. 2026. *V-Dem Country-Year Dataset v16*. Varieties of Democracy (V-Dem) Project.
  Variables: `v2elintmon`, `v2elmonden`, `v2elmonref`, `v2x_regime_amb`, `v2x_polyarchy`, `e_regionpol_6C`.
- Map geometry: Natural Earth 1:110m via [world-atlas](https://github.com/topojson/world-atlas).

V-Dem codes 0 as "No/Unclear", so observer presence is a lower bound. The data records whether
international observers were present, not which organisations observed or how credible they were.
