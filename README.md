# Tacoma Narrows Bridge Analysis Project

A mathematical analysis and simulation of the 1940 Tacoma Narrows Bridge collapse using numerical methods and Python.
  <div>
    <img src="/images/tacoma.png" alt="Tacoma" />
  </div>

## Numerical Analysis
  <div>
    <img src="/images/numerical.png" alt="numerical" />
  </div>
  
## Project Overview

This project implements and analyzes the McKenna and Tuama (2001) mathematical model of the Tacoma Narrows Bridge incident, focusing on how torsional oscillations can be magnified by vertical forcing.

## Tools & Technologies

- Python
- Jupyter Notebook
- NumPy
- Matplotlib

## Key Features

- Implementation of multiple numerical solvers:
  - Euler's Method
  - Trapezoid Method
  - Runge-Kutta 4 (RK4) Method
- Convergence rate analysis
- Wind speed impact simulation
- Bridge oscillation visualization
- Minimum wind speed calculation using bisection method

## Project Activities

1. Stability analysis at wind speed W = 80 km/hr
2. Comparative analysis of Trapezoid and RK4 methods
3. Magnification factor calculation for small initial angles
4. Critical wind speed determination
5. Analysis of extreme conditions
6. Impact of damping coefficient

## Key Findings

- RK4 method proved more accurate than the Trapezoid method
- Critical wind speed of approximately 59.01 km/hr (using RK4)
- Doubling the damping coefficient increased wind resistance from 59.01 to 105.62 km/hr
- Structure showed instability at higher wind speeds even with small initial angles

## Reference Sources

- Timothy Sauer's Numerical Analysis (3rd Edition)
- Historical documentation of the 1940 Tacoma Narrows Bridge
- Python for Data Analysis (2nd Edition)

## Contributors

[Your Name]

## License

[Your License Choice]
