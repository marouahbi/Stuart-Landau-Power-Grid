# Stuart–Landau Model of Power Grids

This repository contains the code used for the Bachelor Thesis **"Stuart–Landau Model of Power Grids"** completed as part of the BSc Physics and Data Science program at Constructor University.

## Overview

The project investigates the dynamics of low-inertia power grids using the Stuart–Landau oscillator framework. The work combines analytical derivations and numerical simulations to study synchronization, limit-cycle behavior, and transient stability in modern power systems with increasing renewable energy penetration.

The repository includes implementations of:

- Single Stuart–Landau oscillator dynamics
- Coupled Stuart–Landau oscillator networks
- Two-node power-grid models
- Kuramoto synchronization simulations
- Numerical experiments investigating low-inertia effects
- Figure generation for thesis results

## Requirements

The code was developed in Python 3 and requires the following packages:

- numpy
- scipy
- matplotlib

Install the required dependencies using:

```bash
pip install numpy scipy matplotlib
```

## Running the Simulations

Execute the relevant Python scripts to reproduce the simulations and figures presented in the thesis.

Example:

```bash
python stuart_landau.py
```

or

```bash
python coupled_stuart_landau.py
```

Generated figures will be saved locally depending on the configuration specified in each script.

## Main Results

The simulations reproduce the key findings presented in the thesis:

- Emergence of a stable limit cycle above the Hopf bifurcation threshold.
- Recovery of the classical synchronization condition for coupled oscillators.
- Characterization of the inertia proxy

\[
\tau = \frac{1}{2\sigma_r}
\]

which governs amplitude recovery dynamics in low-inertia systems.

## Thesis Information

**Author:** Maroua Ouahbi  
**Degree Program:** BSc Physics and Data Science  
**Institution:** Constructor University  
**Supervisor:** Professor Stefan Kettemann

## License

This repository is provided for academic and research purposes.
