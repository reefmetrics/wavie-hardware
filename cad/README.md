# CAD

The mechanical design of Wavie, in [FreeCAD](https://www.freecad.org) (free, Windows, macOS and Linux). The files were made with FreeCAD 1.1; open them with 1.1 or newer.

Open **`WavieFrame/wavieFrame.FCStd`** to see the whole instrument. It is the assembly: it links the other files below, which FreeCAD opens alongside it. Keep the folders together and don't rename them, or the links break.

| File | What it is |
|---|---|
| `WavieFrame/wavieFrame.FCStd` | The assembly: printed frame, tiers, brackets and the reagent ports, with every part below placed in it |
| `waviePCB/pcb.FCStd` | 3D model of the mainboard and the RGB ring board, with components |
| `rgbBoard/rgbboard.FCStd` | The RGB ring board's outline and mounting pads |
| `cuvette/cuvette.FCStd` | The cell and its light-tight holder, between the LED board and the light sensor |
| `Nema11Pump/NEMA11Pump.FCStd` | The peristaltic pump, driven by a NEMA 11 stepper |
| `rotaryPinchValve/rotaryvalvebody.FCStd` | The eight-port rotary pinch valve |
| `manifold/circular8tubemanifold.FCStd` | The circular eight-tube manifold the valve works on |
| `stepperMotor/stepper_motor.FCStd` | The NEMA 17 stepper that turns the valve |
| `limitSwitch/limitswitch.FCStd` | The switch that marks the valve's home position |

The [wiki](https://github.com/reefmetrics/wavie-hardware/wiki) explains what each part does: [Enclosure](https://github.com/reefmetrics/wavie-hardware/wiki/Enclosure), [Fluid path](https://github.com/reefmetrics/wavie-hardware/wiki/Fluid-path), [Optics](https://github.com/reefmetrics/wavie-hardware/wiki/Optics).

These are pre-release designs and will change before Beta Kits ship. Licensed under [CC BY-NC-SA 4.0](../LICENSE).
