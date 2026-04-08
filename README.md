# data_analysis
Some projects that may be useful in order to get something about me.


# 1. GRB 211211A Data Analysis

This project analyzes gamma-ray burst GRB 211211A using real data from the Fermi GBM telescope.

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

## How to run
```bash
pip install -r requirements.txt
jupyter notebook
