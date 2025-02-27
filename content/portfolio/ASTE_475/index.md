---
title: "ASTE 475: Rocket Propulsion"
summary: Simulated Quasi 1-D Nozzle Flow Project.
date: 2024-08-26
type: project
math: false
tags:
  - USC
image:
  caption: ''
---

Assumptions of a quazi 1D nozzle:

- Flow is only in 1 direction

- Cross sectional area is circular and is only a function of the radius at each location 

- Isentropic - adiabatic and reversible

- Ideal gas P = pRT


Using these 4 assumptions, the relationship between pressure, velocity, density and temperature can all be captured using the Area-Mach number relation. If the radius is known along the entire length of the nozzle, then each of these quantities can be analytically solved for. The caveat is that no analytic solution for the Area-Mach number relation exists meaning that it must be numerically solved for at each step.