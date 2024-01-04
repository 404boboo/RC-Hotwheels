# RC-Hotwheels
This project is a remote controlled Hotwheels. Here you can find the Ki-cad design files and STM32 project

This repository contains all the files and documentation for our DIY remote-controlled Hot Wheels car. We designed our own custom PCB using KiCad, featuring a NRF24L01 transceiver(We only used it as a receiver for now) for wireless communication, an H-bridge BD6211F-E2 to control a DC motor for propulsion, a 600mAh LiPo battery for power, and a linear servo motor for precise steering control.
## Folder Structure

- `Kicad Files`: Contains the schematic and gerber files for the PCB design.
  - `Libs`: Libraries for the components used in the KiCad.
- `Stm32F070F6P6TR`: STM32Cube project folder.
## Bill of Materials (BOM)

Check out our [Bill of Materials Spreadsheet](https://1drv.ms/x/s!AkUVCTQvexeIhbBXzQdKwvWQZ13EOg?e=rf4EnU) for a detailed list of components used in this project.
## Installation and Setup

### PCB (KiCad Files)

1. Download the KiCad software from [kicad.org](https://www.kicad.org/).
2. Open the KiCad project files in the `Kicad Files` folder.
3. Generate the gerber files for manufacturing.

### STM32Cube Project

-- TODO

### Hardware

1. Assemble the custom PCB according to the provided schematic.
2. Connect the NRF24L01 transceiver
-- To be updated..
