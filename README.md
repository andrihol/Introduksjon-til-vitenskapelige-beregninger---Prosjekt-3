
# The Josephson Effect – Numerical Modelling

**TMA4320 – Introduction to Scientific Computation | NTNU | Spring 2026**

## Overview

Academic project exploring numerical methods for solving differential equations and modelling superconducting systems.

The project focuses on the Josephson effect, where an electrical supercurrent can flow between two superconductors separated by a non-superconducting material.

Numerical methods are used to solve boundary value problems and investigate how superconducting properties influence the electronic density of states and current through a Josephson junction.

## Technologies

- Python
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook
- Numerical Analysis
- Scientific Computing

## Project Components

### 1. Numerical Differential Equation Solvers

Implemented numerical algorithms for solving initial value problems and boundary value problems.

The work included:
- Implementing an adaptive Runge-Kutta method
- Controlling step sizes using local error estimates
- Implementing the secant method for root finding
- Combining numerical integration and root finding using the shooting method
- Investigating numerical accuracy and convergence
- Comparing custom implementations with SciPy's `solve_bvp`

### 2. Numerical Solution of the Usadel Equations

Worked with the Usadel equations to model superconducting proximity effects in a Josephson junction.

The work included:
- Converting complex matrices into real-valued vectors
- Formulating a system of 32 real differential equations
- Implementing boundary conditions for normal metals and superconductors
- Solving the resulting boundary value problem using SciPy
- Computing Green's functions from numerical solutions

### 3. Electronic Density of States

Investigated the electronic density of states in the normal region between two superconductors.

The work included:
- Calculating the normalized density of states
- Investigating the superconducting proximity effect
- Studying how the induced energy minigap changes with junction length
- Visualizing the density of states as a function of position and energy

### 4. Josephson Supercurrent

Investigated the relationship between superconducting phase differences and electrical current.

The work included:
- Calculating the spectral current integrand
- Investigating current conservation
- Comparing systems with and without a phase difference
- Applying numerical integration using Simpson's method
- Computing and visualizing the current-phase relationship

## Key Learning Outcomes

- Implementing numerical algorithms from mathematical descriptions
- Solving ordinary differential equations
- Working with complex matrices and vectorized systems
- Applying numerical root-finding techniques
- Solving boundary value problems using SciPy
- Evaluating numerical accuracy and stability
- Visualizing and interpreting scientific simulation results

## Project Structure

- `Josephson_Effect.ipynb` – Numerical implementations, simulations, visualizations, and analysis

## Academic Context

Completed as part of TMA4320 – Introduction to Scientific Computation at the Norwegian University of Science and Technology (NTNU).

The project combines numerical mathematics, differential equations, computational physics, and scientific programming to investigate superconductivity and the Josephson effect.
