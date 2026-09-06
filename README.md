# Wallpyria

**Project website: https://wallpyria.altlogic.pl**

Wallpyria is a macOS wallpaper app by AltLogic. All information, downloads, privacy policy and terms are on the project website — this repository is not a copy of it.

## What is here

This repository distributes the on-device AI models for the **Frame Expansion** effect. The app downloads them from [Releases](../../releases) on demand; nothing here is required to install or use the app.

- Files are served under the release tag `models-v1`, with flat names (`/` in the model path replaced by `__`) and files larger than 1 GiB split into `.000`, `.001`, … parts.
- The app verifies every file against a SHA-256 manifest and reassembles the parts locally. Images never leave the user's Mac.

## Licenses

Model licenses are in [`LICENSES/`](LICENSES/): CreativeML Open RAIL++-M (SDXL Inpainting, VAE, text encoders), BSD 3-Clause (Real-ESRGAN), MIT (CLIP tokenizer). Full list: https://wallpyria.altlogic.pl/licenses/

© 2026 AltLogic. All rights reserved.
