# STARSTATION

Interactive **orbital Starship station assembler** — radial LEO station with hub Starship, outer ships, tubes, connectors, and a 16-petal solar assembly.

**Play:** [https://elonph2025.github.io/STARSTATION/](https://elonph2025.github.io/STARSTATION/)

## Controls

| Action | How |
|--------|-----|
| Orbit / zoom / pan | Drag · scroll · right-drag |
| Add parts | Left panel: Starship, Solar unit, Connector, Tube |
| Full wheel preset | **Presets → Radial station** |
| Focus / Move / Rotate / Delete | Structure list: **F** · **M** · **R** · **×** |

## Local

```bash
cd STARSTATION
python3 -m http.server 8765
# http://127.0.0.1:8765/
```

Meshes and textures ship as embedded data-URLs (`assets-embedded-*.js`) so the app works as a static GitHub Pages site. Draco decoder loads from Google’s public host.

## Stack

Three.js (CDN) · OrbitControls · TransformControls · GLTFLoader + Draco · Flight12-style orbital Starship meshes only (no Super Heavy).

## Note

Fan / education demo. Not affiliated with SpaceX.
