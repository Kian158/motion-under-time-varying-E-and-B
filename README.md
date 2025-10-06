# Charged particle simulator for time varying oscillatory E and B fields

This project models the Lorentz force over time for a charged particle in time varying (or constant) E and B vector fields, and then visualises the trajectory in a 3D plot (All in Python)
I was originally only utilising constant E and B fields, but later decided to extend it to time varying ones. The hardest part was the differential equation approximations, but this project definitely has made me more confident. 


<img width="571" height="590" alt="example 3" src="https://github.com/user-attachments/assets/71e59904-c080-4962-a2c9-62abe7d82e6e" />
<img width="580" height="590" alt="example 1" src="https://github.com/user-attachments/assets/5700fab2-e03f-4323-a08a-ea7a0d56fc33" />
<img width="571" height="590" alt="example 2" src="https://github.com/user-attachments/assets/a8ca62ff-994e-4ee5-8ac4-7e8da12458df" />



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
