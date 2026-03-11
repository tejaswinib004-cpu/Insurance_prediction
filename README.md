# Insurance_Prediction
# Project Overview

The Insurance Prediction System is a machine learning project that predicts the insurance premium amount based on customer information. The model analyzes important factors such as age, annual income, policy term, and sum assured to estimate the expected premium.

This system helps insurance companies determine appropriate premium values and allows customers to estimate the cost of their insurance policy.

# Features

Predict insurance premium using machine learning

Data preprocessing and feature engineering

Model training and evaluation

Interactive web application using Streamlit

Simple user interface for entering customer details

# Technologies Used

Python

Pandas

NumPy

Scikit-learn

Streamlit

# Project Structure
Insurance_prediction
│
├── app.py
├── requirements.txt
├── README.md
│
├── data
│   ├── raw
│   └── processed
│
├── models
│   ├── model.pkl
│   └── scaler.pkl
│
└── src
    ├── data_preprocessing.py
    ├── feature_engineering.py
    └── prediction.py

# Run the Application
python -m streamlit run app.py

# Input Features

The model uses the following inputs:

Age

Annual Income

Policy Term

Sum Assured

# Output

The system predicts the estimated insurance premium amount.

# Author

Tejaswini Bollaboina
