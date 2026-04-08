# data_analysis
Some projects that may be useful in order to get something about me.


# 1. GRB 211211A Data Analysis

This project uses real astrophysical data from the Fermi Gamma-ray Space Telescope,
processed using the official Fermi Science Tools environment.

## Goals
- Extract and clean astrophysical data
- Compute burst duration (T90)
- Perform spectral analysis
- Compare results with literature

## Tools
- Python
- NumPy / Pandas
- Matplotlib
- Astrophysics libraries (gbm)

## Key Results
- T90 computed: 43.8 s
- Hardness ratio: 0.657
- Best spectral fit: Band model

## Project Structure
- `notebooks/analysis.ipynb`: main analysis
- `data/`: input data
- `results/`: plots and outputs

## Environment

This analysis was developed using the official Fermi Science Tools environment (`fermienv`),
which ensures compatibility between scientific libraries (NumPy, Matplotlib, etc.).

Because of this, exact package versions are managed internally by the Fermi environment.

The provided `requirements.txt` is only indicative for running simplified parts of the analysis.

## How to run
```bash
pip install -r requirements.txt
jupyter notebook


