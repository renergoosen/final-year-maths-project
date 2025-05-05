# Final Year Mathematics Project - Numerical Methods

This repository contains the code and explanations for various numerical methods implemented during my final year Mathematics project at the University of Leeds. The project focuses on solving mathematical problems using computational techniques such as finite difference schemes, Monte Carlo methods, and numerical integration.

---

## 📚 Project Overview

The project involved solving the following problems:

1. **Solving the Heat Equation using Finite Difference Scheme**
    - **Methods used**: Forward Difference Scheme, Crank-Nicolson Scheme.
    - **Problem**: Solve the one-dimensional heat equation to model heat diffusion in a given domain.
    - **Von Neumann Stability Analysis**: Performed stability analysis on the schemes used.

2. **Monte Carlo Integration**
    - **Methods used**: Monte Carlo methods for numerical integration.
    - **Problem**: Approximating the value of an integral using random sampling techniques.

3. **Two-Body Planetary Orbit Simulation**
    - **Methods used**: Numerical integrators including:
        - Forward Euler Method
        - Modified Euler Method
        - Leapfrog Method
        - Runge-Kutta 4th Order (RK4)
    - **Problem**: Simulating the motion of two bodies (e.g., planets) in orbit using Newton's laws of motion.

---

## 🛠 Tech & Tools

- **Programming Language**: Python
- **Libraries**: 
    - NumPy
    - Matplotlib (for visualization)
    - SciPy (for numerical methods)
    - Sympy
      
- **Development Environment**: Jupyter Notebook (for exploration and testing)

---

## Problems Solved & Methods Used

### 1. **Heat Equation Solver**
- Used the finite difference method to approximate the solution to the heat equation.
- Implemented both **Forward Difference Scheme** and **Crank-Nicolson Scheme** for comparison.
- Performed Von Neumann Stability Analysis to assess the stability of the methods.

### 2. **Monte Carlo Integration**
- Implemented Monte Carlo methods to estimate the value of an integral.
- Demonstrated its application on various mathematical functions to approximate the area under curves.

### 3. **Two-Body Orbital Problem**
- Simulated the interaction between two orbiting bodies using different numerical integration methods:
  - **Forward Euler**: Simple but less accurate.
  - **Modified Euler**: Improved accuracy by refining the solution.
  - **Leapfrog**: Optimised for long term Planetary orbit simulation.
  - **Runge-Kutta 4th Order**: Higher-order method providing better accuracy for short term simulations.

