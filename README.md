# portfolio-aerospace-engineer
#Wind Turbine Numerical Analysis Suite
#This repository contains Python scripts applying numerical methods to evaluate wind turbine power using numerical methods 

## Key Features
- **Numerical Differentiation:** Calculated power rate-of-change  from time-series data using Finite Difference Schemes (Forward, Backward, Central).
- **Differential Integration:** Modelled  displacement over time using Euler’s Method across varying time steps
- **Root-Finding:** Calculated exact time of maximum horizontal displacement by solving for velocity convergence using the Bisection Method.

## Tools & Libraries
- Python
- NumPy (Data manipulation & numerical arrays)
- Matplotlib (Parametric visualization & plotting)

## Usage Note
Running the finite difference analysis requires an external time-series dataset (`windturbinepower.txt`). Euler's and Bisection algorithms execute independently.
