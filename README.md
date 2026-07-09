# ESP32 Gamepad

GPL-3.0 ESP32 XInput gamepad with PCB/Gerber assets, SolidWorks/STL/STEP enclosure and button files, and BOMDoc artifacts.

## Installation / quick start

## Project

ESP32 Gamepad

GPL-3.0 ESP32 XInput gamepad with PCB/Gerber assets, SolidWorks/STL/STEP enclosure and button files, and BOMDoc artifacts.

## Quick start

1. Download the printable files from Printables: https://www.printables.com/model/1776628-esp32-gamepad
2. Download this GitHub repository as a ZIP, or clone it:

   ```bash
   git clone https://github.com/ToolKnox/hawkridge-esp32-gamepad.git
   ```

3. Use `source/upstream/` for the mirrored software, firmware, PCB, CAD-source, and upstream documentation.
4. Use the Bill of Material PDF attached to the Printables Documentation section for parts planning.
5. Read the project-specific notes below before powering electronics or uploading firmware.

## Software / firmware setup

- Install the ESP32 board support in Arduino IDE or PlatformIO before uploading firmware.
- PCB/Gerber/electronics design files are mirrored under `source/upstream/`; open them with the original toolchain noted by the file type, such as KiCad, Altium, or CAM/Gerber viewers.

## Main software/config files

- `source/upstream/.vscode/extensions.json`
- `source/upstream/.vscode/settings.json`
- `source/upstream/platformio.ini`
- `source/upstream/src/main.cpp`

## PCB / electronics design files

- `source/upstream/Controller PCB and CAD files/Controller.BomDoc`
- `source/upstream/Controller PCB and CAD files/Controller.PrjPcb`
- `source/upstream/Controller PCB and CAD files/Controller.PrjPcbStructure`
- `source/upstream/Controller PCB and CAD files/Copy of PCB1-DESKTOP-Q.PcbDoc`
- `source/upstream/Controller PCB and CAD files/Copy of PCB1.PcbDoc`
- `source/upstream/Controller PCB and CAD files/History/CAMtastic1.~(1).#(Deleted).PcbDoc.Zip`
- `source/upstream/Controller PCB and CAD files/History/CAMtastic1_1.~(1).PcbDoc.Zip`
- `source/upstream/Controller PCB and CAD files/History/CAMtastic1_1.~(2).PcbDoc.Zip`
- `source/upstream/Controller PCB and CAD files/History/CAMtastic1_1.~(3).#(Deleted).PcbDoc.Zip`
- `source/upstream/Controller PCB and CAD files/History/CAMtastic1_2.~(1).PcbDoc.Zip`
- `source/upstream/Controller PCB and CAD files/History/CAMtastic1_2.~(2).PcbDoc.Zip`
- `source/upstream/Controller PCB and CAD files/History/CAMtastic1_2.~(3).#(Deleted).PcbDoc.Zip`
- `source/upstream/Controller PCB and CAD files/History/Controller.~(1).BomDoc.Zip`
- `source/upstream/Controller PCB and CAD files/History/Controller.~(1).PrjPcb.Zip`
- `source/upstream/Controller PCB and CAD files/History/Controller.~(3).BomDoc.Zip`
- `source/upstream/Controller PCB and CAD files/History/Controller.~(4).BomDoc.Zip`
- `source/upstream/Controller PCB and CAD files/History/Controller.~(4).PrjPcb.Zip`
- `source/upstream/Controller PCB and CAD files/History/Controller.~(5).#(Deleted).BomDoc.Zip`
- `source/upstream/Controller PCB and CAD files/History/Controller.~(5).PrjPcb.Zip`
- `source/upstream/Controller PCB and CAD files/History/Controller.~(6).PrjPcb.Zip`
- … 165 more PCB/manufacturing files under `source/upstream/`.

## Upstream documentation mirrored here

- `source/upstream/README.md`

## Original source

https://github.com/Quinlan-S/ESP32-Gamepad


## Where to find things

- Printables model and printable files: https://www.printables.com/model/1776628-esp32-gamepad
- Bill of Material: `ESP32 Gamepad Bill of Material.pdf` in the Printables Documentation section
- Full mirrored upstream source/software/PCB files: `source/upstream/`
- Source asset index: `docs/source-assets.md`
- Standalone install/build guide: `docs/INSTALLATION.md`

