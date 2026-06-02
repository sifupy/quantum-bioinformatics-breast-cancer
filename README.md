# Quantum-Inspired Biomarker Selection for Breast Cancer Mutation Analysis

This repository contains the implementation, datasets, experiments, and results developed for a Master's thesis on quantum-inspired optimization methods for biomarker selection in breast cancer mutation analysis.

## Overview

The project evaluates and compares several biomarker selection approaches on both real and synthetic mutation datasets:

- LASSO
- TPGrowth
- MILR
- NEAL
- QAOA

Performance is assessed using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Cross-validation analysis

## Repository Structure

```text
data/
├── real/
└── synthetic/

notebooks/
├── real_dataset_experiment.ipynb
└── synthetic_benchmark_experiment.ipynb

results/
├── figures/
└── tables/

thesis/
└── thesis.pdf
```

## Datasets

### Real Dataset
Breast cancer mutation dataset used for biomarker discovery and classification experiments.

### Synthetic Benchmark Dataset
A controlled synthetic mutation dataset created to evaluate biomarker selection methods under reproducible conditions.

## Reproducibility

Clone the repository and install dependencies:

```bash
git clone <repository-url>
cd quantum-bioinformatics-breast-cancer

pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

## Results

Experimental results, figures, ROC curves, confusion matrices, and statistical analyses are available in the `results/` directory.

## Author

Master Thesis Project  
Quantum Optimization & Bioinformatics