
# Short-Term Rainfall Forecasting in Cork Using ERA5 Reanalysis

This repository contains research code for short-term rainfall forecasting in Cork, Ireland, using ERA5 reanalysis data.

The project investigates deep learning approaches for precipitation prediction, with a particular focus on bidirectional recurrent neural networks, uncertainty estimation, and model evaluation.

## Overview

The associated study explores a Bidirectional Uncertainty-aware Long Short-Term Memory (BU-LSTM) approach for short-term rainfall forecasting in Cork, Ireland.

The research focuses on:

- Modelling temporal dependencies in meteorological data
- Improving short-term rainfall prediction
- Estimating predictive uncertainty
- Comparing deep learning methods with machine learning baselines
- Analysing meteorological predictor relationships

## Dataset

- **Study area:** Cork, Ireland
- **Data source:** ERA5 Reanalysis
- **Period:** 2012–2024
- **Temporal resolution:** 6 hours
- **Input window:** 6 time steps
- **Forecast horizon:** 6 hours ahead
- **Prediction target:** Total precipitation

## Repository Contents

The repository currently includes:

- Meteorological data preprocessing and exploratory analysis
- Spearman correlation analysis
- Bidirectional LSTM with attention
- Gaussian negative log-likelihood training
- Prediction uncertainty visualisation
- XGBoost comparison experiments

## Repository Structure

```text
Rainfall-Prediction-in-Cork/
├── Cork_Rainfall_Prediction.ipynb
└── README.md
```

## Code

The experimental notebook is available at:

[Cork_Rainfall_Prediction.ipynb](Cork_Rainfall_Prediction.ipynb)

The notebook includes selected model implementations, training procedures, and evaluation analyses.

## Data Availability

ERA5 reanalysis data are available from the Copernicus Climate Data Store:

https://cds.climate.copernicus.eu/datasets/reanalysis-era5-single-levels

The processed dataset is not included in this repository.
