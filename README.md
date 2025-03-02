# MonteFlow
MonteFlow is a MATLAB-based solver for 2D steady-state heat transfer problems. It currently uses an iterative method to compute temperature fields and visualize the solution. The heatTransfer_MonteCarlo.m file runs a Monte Carlo simulation and visualizes data from the simulations. The stocasticBoundaryCondition.m file is a function that allows you to choose from three SBC choices: Gaussian noise, bimodal noise, and Brownian motion.

## How to Use
1. Clone the repository.
2. Run the 'BilinearInterpolation.m' file in MATLAB.
   - This code will allow you to visualize steady-state 2D heat transfer without SBCs.
3. Run the 'heatTransfer_MonteCarlo.m' file in MATLAB.
   - This code will perform Monte Carlo simulations with your chosen SBC.

## Features
- Iterative solution for 2D steady-state heat transfer
- Visualizes results at each step
- Runs a Monte Carlo simulation on the heat transfer problem
- Three available SCBs

## Planned Updates
- Explicit time stepping
