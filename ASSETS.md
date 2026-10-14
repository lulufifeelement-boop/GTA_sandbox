# 3D asset sources and licenses

All bundled models in `assets/kenney/packs/` are original models by **Kenney**, distributed under **Creative Commons Zero 1.0 (CC0)**. CC0 allows personal and commercial use without mandatory attribution.

- **City Kit (Commercial)** — buildings and skyscrapers: https://kenney.nl/assets/city-kit-commercial
- **Car Kit** — sedans, sports cars, SUV, truck, garbage truck and police car: https://kenney.nl/assets/car-kit
- **Nature Kit** — detailed trees and pine trees: https://kenney.nl/assets/nature-kit
- Model source repository and license text: https://github.com/Hidencod/tge-assets

The selected original GLB assets were bundled as base64 text files so GitHub Pages can serve them from the same origin. They are decoded by Three.js GLTFLoader at runtime; no account or third-party CDN is needed for these model files.

The game still has procedural fallbacks for models that fail to decode, preserving playability when possible.


## Detailed vehicle models

The published site downloads these game-ready GLB vehicle meshes during the Pages build. If a source is temporarily unavailable, the game falls back to the bundled Kenney Car Kit model. All listed vehicle models are labeled CC0 1.0 on their source pages; they include their own wheels as part of their model hierarchy.

- Sports car (2K PBR materials, separate rolling wheels): https://grab3d.com/models/vehicles/sports-car/
- Sedan: https://grab3d.com/models/vehicles/sedan/
- Hatchback: https://grab3d.com/models/vehicles/hatchback/
- Classic car: https://grab3d.com/models/vehicles/classic-car/
- SUV: https://grab3d.com/models/vehicles/suv/
- Police car: https://grab3d.com/models/vehicles/police-car/
- Dump truck: https://grab3d.com/models/vehicles/dump-truck/
- Garbage truck: https://grab3d.com/models/vehicles/garbage-truck/

Source site and license information: https://grab3d.com/ . These GLB files are copied into the published assets/vehicles/ directory by .github/workflows/pages.yml; they are not served from a third-party domain at runtime.
