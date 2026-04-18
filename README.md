# RNK Alpha MapGen

RNK Alpha MapGen is the compact alpha-tier Foundry VTT dungeon generator for the RNK module family. It keeps the core map generation workflow, theme selection, architecture controls, and trap placement, while leaving the advanced tier features out of the way.

## Features

- Theme-driven dungeon generation
- Stacked alpha-tier GM Hub layout
- Architecture and trap controls
- Scene generation and export actions
- Foundry VTT scene control integration

## Installation

1. Copy the `rnk-alpha-mapgen` folder into your Foundry `Data/modules` directory.
2. Start the local Python service defined in `server.py`.
3. Enable the module in Foundry and open the GM Hub from the scene controls.

## Module details

| Field | Value |
| --- | --- |
| Module ID | `rnk-alpha-mapgen` |
| Title | `RNK Alpha MapGen` |
| Compatibility | Foundry VTT v11-v13 |
| License | Proprietary |

## Folder layout

```text
rnk-alpha-mapgen/
├── module.json
├── README.md
├── scripts/
│   ├── rnk-dungeon.js
│   ├── rnk-movement.js
│   └── rnk-traps.js
├── styles/
│   └── rnk-dungeon.css
└── templates/
    ├── gm-hub.html
    └── scene-tracker.html
```

## Notes

- The alpha tier is intentionally simpler than the higher RNK module tiers.
- The module id and runtime namespace use `rnk-alpha-mapgen`.
- Keep the folder name aligned with the module id when packaging for Foundry.
