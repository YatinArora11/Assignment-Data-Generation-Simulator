# Assignment-Data-Generation-Simulator

# Data Generation using Modelling and Simulation for Machine Learning

Submitted by - Yatin Arora [102303935]

## Objective
The goal of this assignment is to generate synthetic data using a simulation model and apply machine learning techniques to analyze the generated data.

## Simulation Tool
The Lotka–Volterra Predator–Prey Model is used as the simulation framework.  
SciPy's numerical ODE solver (`odeint`) is used to simulate the system dynamics.

## Parameters and Bounds
| Parameter | Description | Range |
|--------|------------|-------|
| alpha | Prey growth rate | 0.5 – 1.5 |
| beta | Predation rate | 0.02 – 0.1 |
| delta | Predator reproduction rate | 0.01 – 0.1 |
| gamma | Predator death rate | 0.5 – 1.5 |

## Data Generation
- 1000 simulations were generated
- Each simulation used randomly sampled parameters
- Final prey and predator populations were recorded

## Machine Learning Models Used
- Linear Regression
- Ridge Regression
- Decision Tree
- Random Forest
- Gradient Boosting

## Evaluation Metrics
- Mean Squared Error (MSE)
- R² Score

## Results
Random Forest and Gradient Boosting models achieved the highest performance based on R² score.

## Conclusion
Simulation-based data generation provides a powerful way to create synthetic datasets for machine learning when real-world data is limited.
