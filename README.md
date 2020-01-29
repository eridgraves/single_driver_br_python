# single_driver_br_python
Modeling a single-driver unported/ported speaker enclosure in Python using a hybrid Thiele-Small model.

## Setup
Using a single driver in a simple box enclosure:
- Thiele-Small parameters can be obtained from the driver spec sheet and box dimensions.
- Physical parameters obtained from constants at STP.

## Methods
From Thiele-Small:

<img src="https://latex.codecogs.com/svg.latex?\Large&space; Z_\text{sp}=\frac{F}{V}=\frac{K}{j\omega}=\frac{1}{j \omega C_m}" title="\Large Z_\text{sp}=\frac{F}{V}=\frac{K}{j\omega}=\frac{1}{j \omega C_m}" />

From Acoustical Lumped Networks:
- Assume devices are small compared to λ.
- Treated as hydraulic systems, with air being the fluid. (Ignoring compressibility of air)

Mechanical : <img src="https://latex.codecogs.com/svg.latex?\Large&space; Z_m=\frac{F}{v}" title="\Large Z_m=\frac{F}{v}" />
Electrical : <img src="https://latex.codecogs.com/svg.latex?\Large&space; Z_e=\frac{V}{I}" title="\Large Z_e=\frac{V}{I}" />
Acoustical : <img src="https://latex.codecogs.com/svg.latex?\Large&space; Z_a=\frac{P}{Q}" title="\Large Z_a=\frac{P}{Q}" />

