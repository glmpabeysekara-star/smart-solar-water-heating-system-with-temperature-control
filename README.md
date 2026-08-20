# Smart Solar Water Heating System with Temperature Control

## Overview

This repository contains the conference paper and simulation work for a proposed Smart Solar Water Heating System with Temperature Control.

The study investigates a smart control approach for utilizing solar energy to heat water while maintaining a user-defined output temperature and minimizing reliance on grid electricity.

## Key Features

- Solar irradiance modelling
- Solar-heated water temperature simulation
- User-defined temperature setpoint
- Automatic hot and cold water mixing
- Auxiliary electric heater control
- ON/OFF heater control logic
- Energy consumption calculation
- MATLAB and Simulink-based system modelling

## System Operation

The proposed system continuously evaluates the temperature of solar-heated water against the user-defined temperature setpoint.

When the solar-heated water temperature is sufficient, the system calculates an appropriate hot--cold water mixing ratio to achieve the desired output temperature without using additional electrical energy.

When solar energy is insufficient, an auxiliary electric heating mechanism is activated to provide the additional heating required.

## Simulation

The proposed system was modelled and simulated using MATLAB and Simulink.

The simulation considers:

1. Time-varying solar irradiance
2. Solar energy conversion to thermal energy
3. Water temperature variation
4. Temperature-control logic
5. Hot--cold water mixing
6. Auxiliary heater operation
7. Electrical energy consumption

## Results

The simulation demonstrates the potential of intelligent temperature control to:

- Maximize the utilization of available solar energy
- Reduce unnecessary auxiliary heater operation
- Maintain water temperature close to a user-defined setpoint
- Reduce dependence on grid electricity
- Improve overall energy efficiency

## Authors

- G.L.M.P. Abeysekara
- Y.D. Amarasinghe
- S.A. Ambalangodage

Department of Electrical Engineering  
University of Moratuwa, Sri Lanka

## Paper

The conference paper is available in the [`paper`](./paper) directory.

## Disclaimer

This repository presents a proposed system and simulation study. The complete physical solar water heating system was not fabricated as part of this work.
