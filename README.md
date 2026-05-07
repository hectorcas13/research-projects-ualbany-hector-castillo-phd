# Research Projects UAlbany - Hector Castillo

This repository contains notebook projects developed as part of my PhD-related statistical learning and cybersecurity research work at the University at Albany, SUNY.

## Projects

### 1. Fraud Classification

Location: `fraud-classification/`

This project studies binary fraud detection with a banking transaction dataset. The notebook compares logistic regression, LDA, QDA, Naive Bayes, KNN, regularization, and cross-validation-based model comparison.

Main notebook:

- `fraud-classification/notebooks/Fraud_banking_classification_stratified_80_20.ipynb`

Dataset included:

- `fraud-classification/data/fraud_data.csv`

### 2. USA House Price Regression

Location: `usa-house-price-regression/`

This project studies house-price prediction for U.S. states and territories using multiple regression, interactions, polynomial terms, stepwise selection, ridge, lasso, step functions, splines, local regression, KNN regression, and cross-validation.

Main notebook:

- `usa-house-price-regression/notebooks/USA_house_price_regression.ipynb`

Sample dataset included:

- `usa-house-price-regression/data/USA Real Estate Dataset_sample.csv`

Note:

The original real-estate dataset is larger than GitHub's standard single-file upload limit, so the full file is not stored in this repository. The notebook is configured to use the full dataset if it is placed at:

- `usa-house-price-regression/data/USA Real Estate Dataset.csv`

It can also be downloaded from Dropbox:

- `https://www.dropbox.com/scl/fi/4ixfif7buj5xt2bvlcoen/USA-Real-Estate-Dataset.csv?rlkey=e2v2eekghwjr42ixh0jxobmbz&st=imx6jme5&dl=1`

Otherwise, it falls back to the included sample dataset.

### 3. IIoT Intrusion Detection with Tabular Baselines, Graph Analysis, and GNNs

Location: `iiot-intrusion-detection-gnn/`

This project analyzes the CIC IIoT Dataset 2025 using exploratory data analysis, classical classification baselines, graph-analysis designs, and richer graph neural network experiments for benign-vs-attack intrusion detection.

Main notebooks:

- `iiot-intrusion-detection-gnn/notebooks/CIC IIoT dataset 2025_Benign data.ipynb`
- `iiot-intrusion-detection-gnn/notebooks/CIC IIoT dataset 2025_attack data.ipynb`
- `iiot-intrusion-detection-gnn/notebooks/Benign vs Attack.ipynb`
- `iiot-intrusion-detection-gnn/notebooks/Baseline Models and GNN Roadmap.ipynb`
- `iiot-intrusion-detection-gnn/notebooks/Rich Graph GNN Experiments.ipynb`

Dataset note:

The original CIC IIoT Dataset 2025 files are not stored in this repository. The notebooks use local dataset paths and can be updated to match the user's local data directory.

## Repository Structure

```text
research-projects-ualbany-hector-castillo-phd/
├── README.md
├── docs/
│   └── github_commands.md
├── fraud-classification/
│   ├── README.md
│   ├── assets/
│   ├── data/
│   └── notebooks/
├── iiot-intrusion-detection-gnn/
│   └── notebooks/
└── usa-house-price-regression/
    ├── README.md
    ├── assets/
    ├── data/
    └── notebooks/
```

## Software

- R
- Python
- Jupyter Notebook with R and Python kernels

## Notes

- The notebooks were copied into this repository with relative paths so they can be shared more easily.
- Image assets used in formulas and markdown explanations are stored locally inside each project folder.
- A command log for the GitHub publishing workflow is included in `docs/github_commands.md`.
