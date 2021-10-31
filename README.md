# Life Support

Reads gas sensor and controls volume pumps to bring atmosphere to desired Oxygen, CO2, and N2 level.

## LIFE
## LIFE2

Tries to pad atmosphere with CO2 if there's insufficient nitrogen.

## LIFE3

Simpler version that only tries to raise gas levels to the desired percentage.

## Pressure Management

# Proportional Pressure Controller (PBFC)

Activates a pump when pressure is exceeded. It turns on at 50MPa by default.
Probably should be renamed to Proportional Back Pressure Controller.

Reads `Pressure` and sets `Setting` on a volume pump.

# Production

## AFA - Arc Furnace Array

Automates up to six arc furnaces. Reads `Occupied` and controls `Activate`.

# Temperature

## THST - Thermostat

Manages base temperature by controlling up to two heating and cooling devices. Works with wall heaters, wall coolers, digital valve to control a radiator, etc.

Reads `Temperature` and controls `On`.

# Unsorted

## AC - Air Conditioner
## ATMO - Atmopherics Controller
## FCTRL1 - Furnace Controller mk1
## FCTRL2 - Furnace Controller mk2
## FCTRL3 - Electric Furnace Controller
## FFC - Furnace Fuel Controller
## FPC - Furnace Pressure Controller
## HPID - Hardcoded PID
## Legacy Heater cooler
## MSYNC - Mode Synchronizer
## OC - Outflow Control
## OSRT - Ore Sorter
## PBD - Prime Bit Decoder
## PBE - Prime Bit Encoder
## PID
## PMC - Pump Monitor and Control
## PPC - Proportional Pump Controller
## PRD - Pressure Reader
## PSA - Power Saving Airlock
## PSYNC5 - 5-way Power Synchronizer
## PSYNC5-200 - 5-way Power Synchornizer
## SPL12 - Splitter
## SSYNC3 - Setting Synchronizer
## STC2A - 2-axis Solar Tracking with Park
## TRD - Temperature Reader
## VC-100 - Valve Control
