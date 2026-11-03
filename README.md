# Drone Earth

Fly a drone anywhere on the real planet, in your browser.

Search any address or place, and you start flying over Google's real 3D world (buildings, trees, hills), shown with CesiumJS.

**Live:** https://drone-earth.vercel.app

## Controls
| Key | Action |
|---|---|
| W / S | forward / back |
| A / D | slide left / right |
| ← / → | turn |
| ↑ / ↓ | look up / down |
| Space / Shift | up / down |
| E | boost |
| R | restart |
| M | new place |

Fly through the 10 yellow rings as fast as you can. The mini map (bottom right) shows you as a red arrow.

## Run locally
```
python3 -m http.server 4660
```
Then open http://localhost:4660.

## Built with
- [CesiumJS](https://cesium.com) + Google Photorealistic 3D Tiles (through Cesium ion)
- Google address search (through Cesium ion) + [Photon](https://photon.komoot.io) (OpenStreetMap)
- [Leaflet](https://leafletjs.com) + OpenStreetMap for the mini map
