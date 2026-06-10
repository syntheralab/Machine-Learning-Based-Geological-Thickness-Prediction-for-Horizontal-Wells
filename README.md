# Machine-Learning-Based-Geological-Thickness-Prediction-for-Horizontal-Wells
## Overview

This project was developed using the ROGII Wellbore Geology Prediction dataset from Kaggle. The objective is to predict True Vertical Thickness (TVT) values for horizontal wells based on well trajectory and geological measurements.

A Random Forest Regression model was trained using wellbore features such as measured depth (MD), spatial coordinates (X, Y, Z), geological markers, and gamma ray (GR) logs.

## Dataset

Source:
ROGII - Wellbore Geology Prediction (Kaggle)

Data includes:
- Well trajectory information
- Geological marker depths
- Gamma Ray (GR) measurements
- TVT (True Vertical Thickness)

## Features Used

- MD
- X
- Y
- Z
- ANCC
- ASTNU
- ASTNL
- EGFDU
- EGFDL
- BUDA
- GR

## Model

- Random Forest Regressor
- Missing values handled using median imputation
- Train/Test split for validation

## Results

Model Performance:

- RMSE: 0.623

The model successfully generated predictions for all test wells and produced a valid Kaggle submission file containing 14,151 predictions.

## Technologies

- Python
- Pandas
- NumPy
- Scikit-Learn
- Jupyter Notebook

## Project Structure
wellbore-geology-prediction/
│
├── ROGII_Wellbore_Geology_Prediction.ipynb
├── submission.csv
├── README.md
└── data/
