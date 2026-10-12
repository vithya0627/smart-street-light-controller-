# Smart Street Light Controller using Verilog HDL

## Project Overview
The Smart Street Light Controller is a VLSI mini-project designed to reduce unnecessary electricity consumption by automatically controlling street lights based on ambient-light conditions.

The system is implemented using Verilog HDL on a Cyclone II FPGA. A switch simulates the day/night condition, and FPGA LEDs represent individual street lights.

## Features
- Automatic Day and Night Mode Selection
- Individual Street Light Control
- Energy-Saving Mode
- Alternate LED Lighting Pattern
- PWM-Based Brightness Control
- Verilog Simulation and Waveform Verification
- FPGA Implementation using Quartus II

## Technologies Used
- Verilog HDL
- Quartus II 13.0
- ModelSim
- Cyclone II FPGA

## Working Principle
- **Day Mode:** All street lights remain OFF.
- **Normal Night Mode:** All street lights turn ON.
- **Energy-Saving Mode:** Selected lights operate using an alternate lighting pattern and PWM dimming, as implemented in the design.

## Applications
- Smart Campus Lighting
- Street Lighting Systems
- Parking Area Lighting
- Energy-Efficient Outdoor Lighting
- Smart City Infrastructure

## Future Enhancements
- Integration of real ambient-light sensors
- Motion-based lighting control
- Automatic brightness adjustment
- IoT-based remote monitoring

## Author
Vithya S