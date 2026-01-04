# Granovetter Threshold Model Simulation on the Bowdoin Facebook Network

This repository contains a simulation of social contagion dynamics using the **Granovetter Threshold Model**, applied to the Bowdoin College Facebook network. The project explores how different threshold distributions and seeding strategies influence adoption cascades in a social network.

## Overview

The notebook implements:
- Construction of a social network from Facebook data  
- Node-level adoption thresholds drawn from beta distributions  
- Threshold-based diffusion dynamics  
- Multiple seeding heuristics to initiate cascades  
- Measurement and visualization of adoption outcomes  

The goal is to understand how network structure, threshold heterogeneity, and initial conditions shape collective behavior.

## Contents

- **Network Building**: Loads and constructs the Bowdoin Facebook network  
- **Threshold Distributions**: Assigns thresholds using configurable beta distributions  
- **Threshold Dynamics**: Simulates adoption over discrete time steps  
- **Seeding Strategies**: Tests heuristic-based seeding approaches  
- **Experiment Runner**: Runs repeated simulations across parameter settings  
- **Visualization & Analysis**: Plots diffusion trajectories and threshold distributions  

## Requirements

- Python 3.x  
- Common scientific libraries (e.g. `networkx`, `numpy`, `pandas`, `matplotlib`, `scipy`)  
- Jupyter Notebook  

## Usage

1. Open the notebook:
   ```bash
   jupyter notebook Assignment2_zuijderwijk_16493559.ipynb
