# Earth — Interactive 3D Digital Twin

A single-file Cesium globe with free, key-less data:

- Esri satellite base imagery
- NASA GIBS **daily cloud cover** (multi-day temporal fallback to fill gaps)
- **Daily Black Marble night lights** — VIIRS Day/Night Band, recoloured amber, with an all-season 2012 fill for summer-pole gaps
- A **simulated global flight fleet** with glowing trails
- Hover (or tap on touch) a country for live area / population / GDP stats

No API keys, no build step — one HTML file.

## View it

Must be served over http(s) — Chrome will not render Cesium from a `file://` path.
Known to work on Safari without hosting.

- **Hosted:** open the GitHub Pages URL.
- **Local:** `python3 -m http.server 8770` then open <http://localhost:8770/index.html>.
