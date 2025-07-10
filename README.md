# vu-meter
This project is a DIY modular system for adding analog VU meters to an audio setup of any size. Each unit provides visualization for the volume of one audio channel that can be installed inline with any existing setup via an RCA passthrough. Additional units can be installed in the same manner, and only a single power supply is necessary as power is daisy-chained between units.

# Table of Contents
- [Bill of Materials](#bill-of-materials)
- [Schematic](#schematic)
- [Instructions](#instructions)
- [License](#license)

# Bill of Materials
### Per Unit
For each channel the following components are needed:
- 1x 35mm VU meter
- 1x Boffintronics RCA Dual Breakout Board Kit
- 1x Texas Instruments TL081IP Op Amp
- 1x DIP-8 IC Socket
- 4x 1N4148 Switching Diode
- 1x 1kOhm Resistor
- 1x 10kOhm Potentiometer
- 2x 100kOhm Resistor
- 1x 0.1uF Ceramic Capacitor
- 2x 1 uF Polyester Film Capacitor
- 1x 10uF Electrolytic Capacitor
- 14x 4-40 x 1/4 Flat Head Machine Screw
- 2x 1x2 0.1" Header Pins
- 1x 1x4 0.1" Header Pin
- 1x Custom PCB
- 2x Panel Mount 5.5mm x 2.1mm DC Female Barrel Jacks
- 1x 12V DC Power Supply

and the following printed parts:
- [Body](../main/STLs/meterBox.STL)
- [Lid](../main/STLs/meterLid.STL)
- [Meter Panel](../main/STLs/meterVUPanel.STL)
- [RCA/Power Panel](../main/STLs/meterRCAPanel.STL)

### Additional Channels
For each additional channel added, all [Per Unit](#per-unit) components are necessary plus the following:
- 4x 4-40 x 1/4 Flat Head Machine Screws
- 1x 5.5mm x 2.1mm DC Male to Male Cable

as well as 2x printed [Couplers](../main/STLs/meterCoupler.STL) to hold the units together. There is also an optional [End Coupler](../main/STLs/meterCouplerEnd.STL), for use on the ends of the combined unit.

# Schematic
WIP
# Instructions
WIP
# License
This project is released under the [GPL-3.0 license](../main/LICENSE).
