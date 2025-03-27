# Explainable AI Techniques with XGBRegressor

This project demonstrates the use of Explainable AI (XAI) techniques applied to a regression task using a car dataset. 
The goal is to explore how different XAI tools can be used to interpret the predictions of a machine learning model (XGBRegressor).

## Features

- Data loading and preparation from `Cars_data.csv`
- Training of an XGBRegressor model for predicting car-related attributes
- Application of explainability techniques:
  - SHAP (SHapley Additive exPlanations)
  - LIME (Local Interpretable Model-agnostic Explanations)
- Visualisation of feature importance and model explanations

## Technologies

- Python
- XGBoost
- SHAP
- LIME
- Pandas, NumPy, Matplotlib

## How to Run

1. Clone this repository.
2. Ensure all required libraries are installed:
   ```bash
   pip install xgboost shap lime pandas numpy matplotlib
