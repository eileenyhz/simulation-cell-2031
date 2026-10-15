# Simulation Cell 2031

A model-centered product-design concept featuring AURA, an original schematic active speaker.

## Preview

Run `python3 -m http.server 8796 --directory docs` and visit http://localhost:8796.

## GitHub Pages

Publish the `docs` folder from the `main` branch in Settings → Pages → Deploy from a branch.
All site assets use relative paths, supporting repository-based github.io URLs.
The decision-package JSON downloads directly in the browser; no Python API is required.

## Prototype scope

Numerical results, forecasts, logistics and manufacturing release are simulated. No factory is contacted. Voice input depends on browser speech recognition support and may use the browser provider's transcription service.

The speaker construction is informed by KEF documentation linked inside the site; it is not production CAD or a KEF replica.

## Third-party code

Three.js r169 is bundled under the MIT license. See `THIRD_PARTY_LICENSES.txt`.
