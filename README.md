# Quantum Electron Cloud Simulation

## Overview

This project aims to simulate the **electron cloud of an atom** using the principles of **Quantum Mechanics** and the **Schrödinger Wave Equation**. Rather than modeling the exact trajectory of an electron, the simulation visualizes the **probability distribution** of finding an electron in space based on its quantum state.

The probability density is computed from the electron's **quantum numbers** and **polar coordinates**, providing a three-dimensional representation of atomic orbitals such as the familiar *s*, *p*, and *d* orbitals.

## Technologies Used

The project is implemented in **Python** and leverages several scientific computing and visualization libraries:

- **NumPy** – Numerical computations and array operations
- **SciPy** – Scientific computing and special mathematical functions
- **Matplotlib** – 3D plotting and visualization
- **scikit-image (skimage)** – Image processing and surface extraction
- **mpi4py** – Parallel computation using MPI for improved performance

## Features

- Numerical implementation of the Schrödinger wave equation
- Computation of electron probability densities
- Generation of three-dimensional electron cloud visualizations
- Support for different atomic orbitals through configurable quantum numbers
- Parallelized computation for handling computationally intensive simulations

## Project Goal

The primary goal of this project is to bridge theoretical quantum mechanics with scientific visualization by producing accurate and intuitive 3D representations of electron probability clouds. It serves as both an educational tool and a computational exploration of atomic orbital structures.

## Author

This project was independently designed and developed by me, **Aayush Pal**.
