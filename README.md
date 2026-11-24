# StudioForge AI trained data

This repository contains only the trained StudioForge model payloads used by the desktop app:

- `own-model.json` — active spatial U-Net model
- `text-model.json` — trained text model used by the ensemble
- `own-field.bin` — learned silhouette field

The app verifies every file's SHA-256 from `manifest.json` before installing it. It does not
contain scene caches, checkpoints, training images, GLBs, source code, or user data.

**Built by [StudioForge-Team](https://github.com/StudioForge-Team).**
