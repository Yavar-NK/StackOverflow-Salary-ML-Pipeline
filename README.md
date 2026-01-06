# StackOverflow Salary Prediction Pipeline

This repository contains an end-to-end Machine Learning pipeline to predict developer salaries based on the **2022 Stack Overflow Developer Survey** dataset.

## 🛠️ Key Features
- **Automated Pipeline:** Integrated data cleaning and preprocessing using Scikit-learn Pipelines.
- **Advanced Modeling:** Optimized **XGBoost Regressor** for accurate salary estimation.
- **Modular Structure:** Professional directory organization (models, notebooks).
- **Production Ready:** Pre-trained model serialized as a `.joblib` file for immediate deployment.

## 📂 Project Structure
- `notebooks/`: Jupyter notebook containing Exploratory Data Analysis (EDA) and model training.
- `models/`: Contains the final trained XGBoost pipeline (`xgbpipe.joblib`).
- `requirements.txt`: List of Python dependencies for easy environment setup.

## 🚀 Getting Started

1. Clone the repo: 
   ```bash
   git clone [https://github.com/Yavar-NK/StackOverflow-Salary-ML-Pipeline.git](https://github.com/Yavar-NK/StackOverflow-Salary-ML-Pipeline.git)

## 🚀 How to Run
To install the requirements, run:
pip install -r requirements.txt

## 🧠 How to Use the Model
You can load the trained pipeline using the following code:

import joblib
model = joblib.load('models/xgbpipe.joblib')
