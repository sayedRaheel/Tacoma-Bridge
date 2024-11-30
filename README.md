## The Tacoma Narrows Bridge: About The Project
A comprehensive analysis implementing the McKenna and Tuama (2001) mathematical model to study the catastrophic collapse of the 1940 Tacoma Narrows Bridge. This project focuses on simulating and analyzing how torsional oscillations were magnified by vertical forcing, leading to the bridge's failure.

### The Historical Context
The Tacoma Narrows Bridge, opened in July 1940, collapsed just four months later due to wind-induced aeroelastic flutter. This project examines the engineering principles behind this famous structural failure through mathematical modeling and numerical analysis.

<div>
  <img src="/Images/tacoma.png" alt="Tacoma" />
</div>

## Numerical Analysis
<div>
  <img src="/Images/numerical.png" alt="numerical" />
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
## Citations

### Image Sources
- [Historical Newspaper Image of Tacoma Narrows Bridge](https://www.newspapers.com/image/289713513)
- [Opening Day of Tacoma Narrows Bridge](https://en.wikipedia.org/wiki/Tacoma_Narrows_Bridge_(1940))

### Literature & Documentation
- **Main Reference**: Timothy Sauer, "Numerical Analysis" (Pearson, 3rd Edition, 2017)
- [Tacoma Narrows Bridge Wikipedia Article](https://en.wikipedia.org/wiki/Tacoma_Narrows_Bridge_(1940))
- McKinney, Wes. "Python for Data Analysis" (2nd Edition, AIM-5001 Course Textbook)

### Code Implementation References
- Bisection Method Implementation: Timothy Sauer's Numerical Analysis
- Python Syntax and Library Functions: Standard Python Documentation
- Convergence Analysis: Based on numerical methods described in Sauer's textbook

All images used are in public domain or used under appropriate licensing terms.

