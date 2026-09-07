# TFM_MQIST

This repository contains the code and simulations for the Master's Thesis (TFM), concentrated in the notebook `TFM_MQIST.ipynb`.

## Features

- **Coherences & Populations Evolution:** Simulate and plot the time evolution of system coherences and populations for a specified initial state and bath temperature.
- **Protocol Fidelity Comparison:** Evaluate and compare fidelity dynamics under two distinct thermal protocols:
  - **Three-temperature protocol:** Cold, Warm & Hot.
  - **Two-temperature protocol:** Cold & Hot.
- **Execution Modes:** Supports local simulation or submitting jobs directly to **IBM Quantum** hardware.

## Requirements

The project relies on the following Python libraries:

- **Python** 
- **NumPy**
- **SciPy**
- **Matplotlib**
- **Qiskit**

## Usage

Open and run `TFM_MQIST.ipynb` using Jupyter Notebook, JupyterLab, or VS Code. Set your desired parameters (initial state, bath temperatures, protocol type) and select whether to run locally or send the jobs to IBM Quantum.
