# Nemo-K temperature sensor for type K thermocouple gauge

## Overview

This is Nemo-K board for ESP-01 and type K thermocouple temperature gauge. The board contains [MAX6675](https://www.analog.com/en/products/max6675.html)
analog-to-digital converter.

Because of its measuring range (0°C to +1024°C) MAX6675 and type K gauge is an ideal setup for measuring components
which may become extremely hot. In boat environment the engine exhaust pipes are typical monitoring target requiring
this type of scale.

The board is designed to be used with ESP-01 microcontroller running Nemo-K firmware.

## Content

The repository contains schematics and PCB in KiCad 8.0 format. The footprint properties contains LCSC part numbers
used by [JLCPBC.com](https://jlcpcb.com). If present, the `sensor-temp-max6675/production/` contains all necessary
files to order boards from JLCPCB. The production files can be easily re-created using
[KiCad Fabrication Toolkit](https://github.com/bennymeg/Fabrication-Toolkit).

The Nemo-K project is not affiliated or sponsored by JLCPCB. The project does not endorse JLCPCB.

## Changelog

* At the moment there is no field tested versions.

## Copyright and License

The license and copyright can be found in the file `LICENSE`.

The license and copyright cover only the schematic diagram and the PCB design. It does not cover footprints and other
embedded elements or technical documentation which may or may not be covered by their own licenses.
