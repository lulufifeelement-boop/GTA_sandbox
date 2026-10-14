# 3D asset sources and licenses

All bundled models in `assets/kenney/packs/` are original models by **Kenney**, distributed under **Creative Commons Zero 1.0 (CC0)**. CC0 allows personal and commercial use without mandatory attribution.

- **City Kit (Commercial)** — buildings and skyscrapers: https://kenney.nl/assets/city-kit-commercial
- **Car Kit** — sedans, sports cars, SUV, truck, garbage truck and police car: https://kenney.nl/assets/car-kit
- **Nature Kit** — detailed trees and pine trees: https://kenney.nl/assets/nature-kit
- Model source repository and license text: https://github.com/Hidencod/tge-assets

The selected original GLB assets were bundled as base64 text files so GitHub Pages can serve them from the same origin. They are decoded by Three.js GLTFLoader at runtime; no account or third-party CDN is needed for these model files.

The game still has procedural fallbacks for models that fail to decode, preserving playability when possible.
