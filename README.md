# Fraud Detection System

A machine learning based fraud detection web application built using Streamlit.

## Features

- Fraud prediction using Logistic Regression
- Interactive Streamlit interface
- Model comparison with:
  - Decision Tree
  - Random Forest
  - Gradient Boosting
  - XGBoost

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Streamlit
- Joblib

## Run Locally

```bash
pip install -r requirements.txt
streamlit run fraud_detection.py
```

## Model Used

Logistic Regression was selected for deployment due to:
- Fast inference
- Interpretability
- High recall on fraud transactions