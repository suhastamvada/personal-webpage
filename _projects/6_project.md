---
layout: page
title: Cooling Power electronics
description: A thermo-mechanical analysis
img: assets/img/PowerElectronics_simulation.jpg
importance: 6
category: work
---

### Project Overview

This project involves the simulation of a Wolfspeed power module (CAS325M12HM2) using COMSOL. The aim is to co-design electronics with an integrated thermal management system, crucial for an NSF proposal focusing on enhancing the thermal performance of power modules.

### Simulation Methodology

We conducted simulations to analyze the thermal behavior of the power module under various conditions. The module consists of MOSFETs mounted on Active Metal Brazed (AMB) units. Key materials and their properties, including SiC, Copper, Si3N4, and AlSiC-8, were considered in the analysis.

### Key Findings

1. **Heat Flux Distribution**: Examined scenarios with a total heat flux of 498W distributed among 7 dies, considering both uniform and varied distributions.
2. **Thermal Resistance**: Simulations accounted for a thermal resistance of 0.1°C/W from the dies to the baseplate.
3. **Boundary Conditions**: Ambient temperature was set at 25°C with specific boundary conditions for heat advection.
4. **Meshing and Solver Details**: Various meshing types were used, and a time-dependent segregated solver calculated the steady-state time.

### Results

- The mean thermal conductivity for the entire device was found to be 187.50 W/m-K.
- Steady-state conditions were achieved after 150 seconds, validating the simulation accuracy.

### Conclusion

Our simulations provide a detailed understanding of the thermal management requirements for the CAS325M12HM2 power module, aiding in the design of more efficient thermal systems for power electronics.
