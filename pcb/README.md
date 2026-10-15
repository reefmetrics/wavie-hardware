# Circuit boards

Wavie's three circuit boards, as [EasyEDA Pro](https://pro.easyeda.com) projects. Each `.epro` file holds the full project: schematic, board layout and parts. Import it into EasyEDA Pro (free, in the browser at [pro.easyeda.com](https://pro.easyeda.com) or as a desktop app) with **File → Import → EasyEDA Pro**; KiCad can also import `.epro` files.

From the project you can export whatever you need: Gerbers to have a board made, a BOM, pick-and-place files, schematic PDFs or a 3D model.

| Folder | Board | What it does |
|---|---|---|
| `main-board/` | Main board (V0.1) | Runs the instrument: ESP32-S3, the two stepper drivers, the isolated probe inputs, CAN bus, USB-C and power |
| `led-array/` | LED array | The photometer's light source: the LEDs and their constant-current driver, facing the light sensor across the cell |
| `rgb-board/` | RGB board | The addressable RGB LEDs of the lighting at the base |

The light sensor is a ready-made TSL2591 module, so it has no board file here.

The [wiki](https://github.com/reefmetrics/wavie-hardware/wiki) explains what is on each board: [Electronics](https://github.com/reefmetrics/wavie-hardware/wiki/Electronics), [Optics](https://github.com/reefmetrics/wavie-hardware/wiki/Optics), [Lighting](https://github.com/reefmetrics/wavie-hardware/wiki/Lighting).

These are pre-release designs and will change before Beta Kits ship. Licensed under [CC BY-NC-SA 4.0](../LICENSE).
