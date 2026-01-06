# StackOverflow Salary Prediction Pipeline

This repository contains an end-to-end Machine Learning pipeline to predict developer salaries based on the **2022 Stack Overflow Developer Survey** dataset.

## 🛠️ Key Features
- **Automated Pipeline:** Integrated data cleaning and preprocessing using Scikit-learn Pipelines.
- **Advanced Modeling:** Optimized **XGBoost Regressor** for accurate salary estimation.
- **Modular Structure:** Professional directory organization (models, notebooks, src).
- **Production Ready:** Pre-trained model serialized as a `.joblib` file for immediate deployment.

## 📂 Project Structure
- `notebooks/`: Jupyter notebook containing Exploratory Data Analysis (EDA) and model training.
- `models/`: Contains the final trained XGBoost pipeline (`xgbpipe.joblib`).
- `requirements.txt`: List of Python dependencies for easy environment setup.

## 🚀 Getting Started
1. Clone the repo: `git clone https://github.com/Yavar-NK/StackOverflow-Salary-ML-Pipeline.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Load the model:
   ```python
   import joblib
   model = joblib.load('models/xgbpipe.joblib')
