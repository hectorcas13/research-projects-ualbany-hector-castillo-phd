# Research Projects UAlbany - Hector Castillo

This repository contains two R notebook projects developed as part of my PhD-related statistical learning work at the University at Albany, SUNY.

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
└── usa-house-price-regression/
    ├── README.md
    ├── assets/
    ├── data/
    └── notebooks/
```

## Software

- R
- Jupyter Notebook with an R kernel

## Notes

- The notebooks were copied into this repository with relative paths so they can be shared more easily.
- Image assets used in formulas and markdown explanations are stored locally inside each project folder.
- A command log for the GitHub publishing workflow is included in `docs/github_commands.md`.
