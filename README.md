# Can we predict next-day COVID-19 infection prevalence in Greater London using wastewater-based surveillance? A comparative study of geospatial machine learning methods

## Overview
Machine learning models (XGBoost, LSTM, ST-GCN (Adjacency and Distance)) for predicting COVID-19 infection rates using London wastewater-based surveillance (WBS) data.

## Code Environment
All scripts and notebooks were run using the following environment:
- Python version: 3.12.2 (Anaconda base environment)

## Required Packages
```bash
pip install pandas numpy scikit-learn torch torch-geometric xgboost geopandas matplotlib seaborn jupyter
```

## Usage
Run notebooks in order:
1. `01_data_exploration.ipynb` - Data analysis
2. `02_xgboost_model.ipynb` - XGBoost models
3. `03_lstm_model.ipynb` - LSTM models
4. `04_stgcn_model.ipynb` - STGCN models
5. `05_results_analysis.ipynb` - Results comparison

## Data
- **Period**: Sep 2020 - Feb 2021
- **Coverage**: 27 London CIS sub-regions
