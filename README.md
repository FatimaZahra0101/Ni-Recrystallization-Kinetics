# Ni-Recrystallization-Kinetics

## Overview
This repository contains a Python-based numerical simulation of the recrystallization behavior of high-purity Nickel produced via Laser Powder Bed Fusion (PBF-LB/M). 

The project aims to demonstrate how processing parameters (which influence stored energy and residual stress) dictate the recrystallization temperature and kinetics, aligning with modern metallurgical research in Additive Manufacturing.

## Key Features
- **JMAK Modeling:** Implements the Johnson-Mehl-Avrami-Kolmogorov (JMAK) equation to predict phase transformation.
- **Process Parameter Linking:** Correlates stored energy (derived from simulated PBF-LB/M energy densities) with the rate of microstructural evolution.
- **Data Visualization:** Generates kinetic curves showing the fraction of recrystallized grains over time.

## Scientific Context
In PBF-LB/M, rapid cooling rates ($10^5 - 10^7$ K/s) create high dislocation densities. This "stored energy" acts as the driving force for recrystallization during post-process heat treatment. This tool helps estimate the time-temperature-transformation (TTT) relationship for Nickel alloys.

## Requirements
- Python 3.x
- NumPy
- Matplotlib
