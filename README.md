# single_driver_br_python
Modeling a single-driver unported/ported speaker enclosure in Python using a hybrid Thiele-Small model.

## Setup
Using a single driver in a simple box enclosure:
- Thiele-Small parameters can be obtained from the driver spec sheet and box dimensions.
- Physical parameters obtained from constants at STP.

## Methods
From Thiele-Small:

<img src="https://latex.codecogs.com/svg.latex?\Large&space;Z_\text{sp}=\frac{F}{V}=\frac{K}{j\omega}=\frac{1}{j\omegaC_m}" title="\Large \frac{F}{V}=\frac{K}{j\omega}" />
