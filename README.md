# CM4 Baseboard LVDS Adapter

Copyright (c) 2024 [Antmicro](https://www.antmicro.com)

![](img/cm4-lvds-adapter-visualization.png)

## Overview

This project contains open hardware design files for an LVDS display adapter which is a bridge between Antmicro CM4 Baseboard and an LCD panel with a touchscreen interface.
This is a reference design that can be customized for different displays.
The PCB design files were prepared in KiCad 7.x.

## Key features

* Fits into the Antmicro CM4 Baseboard  
* Based on `Texas Instruments/SN65DSI84TPAPRQ1` MIPI DSI to LVDS Bridge
* Supports I2C communication for the touchscreen interface
* Integrated power supply for a TFT display (`18V`, `9.6V`, `3.9V`, `3.3V`)
* Integrated backlight driver

## Project structure

The main project directory contains KiCad PCB project files, a LICENSE, and a README.
The remaining files are stored in the following directories:

* `lib` - contains the component libraries
* `img` - contains board visualization for this README
* `doc` - contains schematics
* `assets` - contains visual assets for showcasing this design on [Open Hardware Portal](https://openhardware.antmicro.com)

## Licensing

This project is published under the [Apache-2.0](LICENSE) license.
