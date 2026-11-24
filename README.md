# StudioForge AI trained data

This repository contains only the trained StudioForge model payloads used by the desktop app.
The payloads live in [`data/`](data):

- [`data/own-model.json`](data/own-model.json) — active spatial U-Net model
- [`data/text-model.json`](data/text-model.json) — trained text model used by the ensemble
- [`data/own-field.bin`](data/own-field.bin) — learned silhouette field
- [`data/manifest.json`](data/manifest.json) — sizes and SHA-256 hashes

The app verifies every file's SHA-256 from the manifest before installing it. This repository
does not contain scene caches, checkpoints, training images, GLBs, source code, or user data.

See [LICENSE](LICENSE) for the terms that apply to these model payloads.

**Built by [StudioForge-Team](https://github.com/StudioForge-Team).**
