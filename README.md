# Charged particle simulator for time varying oscillatory E and B fields

This project models the Lorentz force over time for a charged particle in time varying (or constant) E and B vector fields, and then visualises the trajectory in a 3D plot (All in Python)

This simulation is based on the Lorentz force equation:

$F = q(E(t) + v \times B(t))$

Where:
- $E(t)$: Electric field (can be time-dependent)
- $B(t)$: Magnetic field (can be time-dependent)
- $q$: Particle charge
- $m$: Particle mass
The motion is updated using **Euler's method** of numerical integration

## Features

- 3D simulation of particle motion  
- Time-varying **electric** and **magnetic** fields  
- Realistic physics (mass, charge, Lorentz force)  
- Interactive and static 3D plots with `matplotlib`

## Requirements

- Python 3
- NumPy
- Matplotlib
