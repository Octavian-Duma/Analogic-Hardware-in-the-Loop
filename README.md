# Buck Converter Analog Hardware in the Loop (AnHIL) Project

This project focuses on designing and simulating an Analog Hardware in the Loop (AnHIL) system for a Buck converter, which is a DC-DC step-down voltage converter. 

## Project Overview

The Buck converter is designed with the following specifications:
- Input voltage: 48V
- Output voltage: 14V
- Switching frequency: 25 kHz
- Nominal load resistance: 10Ω
- Acceptable inductor current variation
- Acceptable output voltage variation

## Key Components

The project progresses through several phases:
1. **Design calculations** - Determining the minimum inductor and capacitor values needed for proper operation
2. **Mathematical modeling** - Developing equations to describe the converter's behavior in both ON and OFF switching states
3. **Simulation** - Using both instantaneous and average value simulation strategies
4. **Implementation with operational amplifiers** - Creating an analog model of the Buck converter using op-amps

## Simulation Approach

Two simulation strategies were employed:
- Small signal simulation (instantaneous values)
- Large signal simulation (average values)

The project includes structural diagrams, circuit schematics, and implementations in both LTSpice and Simulink environments to validate the design.

## Application

The final part of the project demonstrates an application of the Buck converter as a stabilized DC power supply with performance specifications and consideration of possible disturbances.
