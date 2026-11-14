# 100 LED Oscilloscope

This is a simple oscilloscope with a display of 100 LEDs (10 × 10). The resolution is too low for measurements, but it is very good to see audio waveforms from a microphone.

<img width="1024" height="768" alt="100 LED Oscilloscope" src="https://github.com/user-attachments/assets/54c27abd-6ee8-4a90-9ee3-42a39f39980d" />

## Build guide and video

- Step-by-step build guide on Instructables: [100 LED Oscilloscope](https://www.instructables.com/100-LED-Oscilloscope/)
- Video on YouTube: [100 LED Oscilloscope](https://youtu.be/FqV2W9gObf8)

## How it works

The circuit has 4 ICs:

| IC | Function |
|----|----------|
| 4017 decade counter | Selects the LED columns |
| LM3914 LED driver | Selects the LED rows from the signal level |
| 555 timer | Makes the clock signal |
| LM386 amplifier | Makes the input signal larger |

The LEDs are 5 mm square LEDs. Their flat tops make it easy to keep them straight and in line when you solder them.

## What you need

- All parts are in the [parts list](LED%20Oscilloscope%20-%20Parts%20List.pdf).
- Schematics: [version 1](LED%20Oscilloscope%20V1%20Schematic.pdf) and [version 2](LED%20Oscilloscope%20V2%20Schematic%20.pdf).

> **Note:** These design files are not in this repository yet:
> - Gerber files for the PCB
> - Eagle files (schematic and board)
> - Front panel design (Inkscape)

## Files in this repository

| Folder or file | Contents |
|----------------|----------|
| `LED Oscilloscope - Parts List.pdf` | Parts list |
| `LED Oscilloscope V1 Schematic.pdf` | Schematic, version 1 |
| `LED Oscilloscope V2 Schematic .pdf` | Schematic, version 2 |

## Credits

- Based on the [LED oscilloscope with 100 LEDs](https://www.eddybergman.com/2017/10/led-oscilloscope-with-100-leds.html) by Eddy Bergman.
- PCB and build: Marcus ([lonesoulsurfer](https://github.com/lonesoulsurfer)).

## Support

Do you like this project? You can support my work on [GitHub Sponsors](https://github.com/sponsors/lonesoulsurfer).

## Licence

This project uses the [CERN Open Hardware Licence v2, Strongly Reciprocal](LICENSE) (CERN-OHL-S-2.0). Copyright (c) 2025 Marcus (lonesoulsurfer).

You can make, change and sell boards from these files. If you share or sell a changed design, you must also share the changed design files under the same licence.
