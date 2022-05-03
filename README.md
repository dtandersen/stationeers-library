# Life Support

Reads gas sensor and controls volume pumps to bring atmosphere to desired Oxygen, CO2, and N2 level.

## LIFE
## LIFE2

Tries to pad atmosphere with CO2 if there's insufficient nitrogen.

## LIFE3

Simpler version that only tries to raise gas levels to the desired percentage.

# Pressure Management

## Airlock

### SMAL - Smart Airlock

Pumps air out of airlock pipes and turns off the console after 30 seconds.

| Device    | Description     |
| --------- | --------------- |
| Console   | Airlock console |
| IntVent   | Interior active vent |
| ExtVent   | Exterior active vent |
| GasSensor | Gas sensor |
| IntSensor | Interior pipe analyzer |
| ExtSensor | Exterior pipe analyzer |

### PCS-AV2-HP - Pressure Controller (Active Vent -> Active Vent)

Controls

### PCS-VPAV - Pressure Controller (Volume Pump -> Active Vent)


# Proportional Pressure Controller (PBFC)

Activates a pump when pressure is exceeded. It turns on at 50MPa by default.
Probably should be renamed to Pressure Relief Valve (PRV).

Reads `Pressure` and sets `Setting` on a volume pump.

## PPC - Proportional Pump Controller

Activates up to 5 pumps to control pressure based on PID. If Setting is 50 one pump will turn on at 50%. If Setting is 250 three pumps will turn on, the first two at 100 and the third at 50.

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
## PRD - Pressure Reader
## PSA - Power Saving Airlock
## PSYNC5 - 5-way Power Synchronizer
## PSYNC5-200 - 5-way Power Synchornizer
## SPL12 - Splitter
## SSYNC3 - Setting Synchronizer
## STC2A - 2-axis Solar Tracking with Park
## TRD - Temperature Reader
## VC-100 - Valve Control
