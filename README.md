# House Price MLOps Project

## 1. Project Overview
This project demonstrates an end-to-end Machine Learning Operations (MLOps) lifecycle for predicting house prices using machine learning.

## 2. MLOps Lifecycle

### Stage 1: Problem Definition
Develop a machine learning model to predict house prices based on property features.

### Stage 2: Data Collection
Collect a house-price dataset containing features such as area, bedrooms, bathrooms, age and location.

### Stage 3: Data Validation
Check missing values, duplicate records, incorrect data types and invalid values.

### Stage 4: Data Preprocessing
Clean the dataset, encode categorical variables and prepare features for model training.

### Stage 5: Model Training
Train a regression model using Python and Scikit-learn.

### Stage 6: Model Evaluation
Evaluate the model using:
- MAE
- RMSE
- R² Score

### Stage 7: Model Packaging
Save the trained model using Joblib.

### Stage 8: Model Deployment
Deploy the model using FastAPI and Docker.

### Stage 9: Model Monitoring
Monitor data drift, prediction performance and model reliability.

### Stage 10: Model Retraining
Retrain the model when performance degrades or new data becomes available.

## 3. Technologies Used
- Python
- Scikit-learn
- Pandas
- NumPy
- Git and GitHub
- DVC
- FastAPI
- Docker
- GitHub Actions
- Apache Airflow

## 4. Project Structure

```text
house-price-mlops/
├── data/
├── src/
├── models/
├── metrics/
├── tests/
├── README.md
└── requirements.txt
```

## 5. Project Objective
To implement a reproducible and automated machine learning lifecycle using modern MLOps tools.