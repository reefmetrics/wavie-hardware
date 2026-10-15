# Wavie

Wavie is an automated water tester for reef aquariums, made by [ReefMetrics](https://www.reef-metrics.com). It measures ten parameters on a schedule and reports them to a phone app.

| By reagent | By probe |
|---|---|
| Alkalinity | pH |
| Calcium | ORP |
| Magnesium | Salinity |
| Nitrate | Temperature |
| Phosphate | Dissolved oxygen (probe sold separately) |

The whole instrument is a tower 184 mm tall and 88 mm square.

## Status

Wavie is in development. The **Wavie Beta Kit** is open for pre-order at [reef-metrics.com](https://www.reef-metrics.com/#beta-kit) and is estimated to ship in Q1–Q2 2027, provided the project is fully funded.

- The reagent chemistry has not been formulated yet.
- Firmware and the app are still being built.
- See the [roadmap](ROADMAP.md) for what is planned.

## Open hardware

Wavie is built to be opened, understood and repaired by the person who owns it.

- **This repository** holds the hardware design files: the mechanical CAD and the circuit boards. They are pre-release designs and will change before Beta Kits ship.
- **[The wiki](../../wiki)** explains how each part of Wavie works.
- **Replacement parts** will be sold at cost.

### What's in this repository

| Folder | Contents | Open with |
|---|---|---|
| [`cad/`](cad) | The mechanical design: the frame assembly and every part placed in it | [FreeCAD](https://www.freecad.org) 1.1 or newer (free) |
| [`pcb/`](pcb) | The four circuit boards: mainboard, LED board, RGB ring board and logo backlight | [EasyEDA Pro](https://easyeda.com) (free) |

Each folder has its own README listing what every file is.

### What you may do

The contents of this repository are licensed under [CC BY-NC-SA 4.0](LICENSE). In short:

- You may build, repair and modify a Wavie for your own use.
- You may share your changes, under the same licence, with credit to ReefMetrics.
- You may not make or sell units, kits or parts commercially.

This is a non-commercial licence, so Wavie is open hardware in the sense that the designs are published and free to use for yourself. It does not meet the Open Source Hardware Association's definition, which requires that commercial use be allowed.

### What is not open

- **Reagent formulations** are not published. Reagents for Wavie are made and sold only by ReefMetrics, which is what funds the project.
- **The names and logo.** "Wavie", "ReefMetrics" and the crescent logo are not covered by the licence. Please do not use them for your own products.

## Community

- Progress updates and questions: [Discord](https://discord.gg/4rHbTdAK5G)
- Email: support@reef-metrics.com
