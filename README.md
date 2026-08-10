# STARSTATION

Interactive **orbital Starship station assembler** — radial LEO station with hub Starship, outer ships, tubes, connectors, and a 16-petal solar assembly.

## Play now

**https://starstation.netlify.app/**

(Also: [GitHub repo](https://github.com/ElonPh2025/STARSTATION) · GitHub Pages when enabled.)

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
# open http://127.0.0.1:8765/
```

Meshes and textures ship as embedded data-URLs (`asset_*.js`) so the app works as a static site. Draco decoder loads from Google’s public host.

## Stack

Three.js (CDN) · OrbitControls · TransformControls · GLTFLoader + Draco · Flight12-style orbital Starship meshes only (no Super Heavy).

## Note

Fan / education demo. Not affiliated with SpaceX.
