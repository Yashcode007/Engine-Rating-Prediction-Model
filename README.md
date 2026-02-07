# Engine-Rating-Prediction-Model

📌 Project Overview

This project focuses on building a machine learning system to predict engine and transmission ratings of vehicles based on structured automobile specifications. The goal is to compare multiple regression models and identify the best-performing approach using proper evaluation metrics.

📊 Dataset

Structured vehicle dataset containing engine, transmission, and performance-related features

Includes both numerical and categorical attributes

Missing values and inconsistencies handled during preprocessing

⚙️ Methodology

Performed data cleaning, feature engineering, encoding, and scaling

Trained and evaluated multiple regression models including:

Linear Regression

Support Vector Regression (SVR)

Random Forest

XGBoost

CatBoost

LightGBM

Used cross-validation and error-based metrics to compare model performance

🏆 Best Model

LightGBM Regressor achieved the best performance after hyperparameter tuning

Evaluation Metrics:

RMSE: 0.429

MAE: 0.321

R² Score: 0.74

🧪 Model Evaluation

Models evaluated using:

Root Mean Squared Error (RMSE)

Mean Absolute Error (MAE)

R² Score

GridSearchCV used for hyperparameter optimization

🚀 Tech Stack

Programming Language: Python

Libraries:

NumPy, Pandas

Scikit-learn

XGBoost, CatBoost, LightGBM

Matplotlib / Seaborn (for visualization)

📁 Project Structure
engine_rating_prediction.ipynb   # Main notebook with EDA, modeling & evaluation
README.md                        # Project documentation

✅ Key Learnings

Practical comparison of tree-based and linear regression models

Importance of feature preprocessing in structured ML problems

Hands-on experience with gradient boosting frameworks

🔮 Future Improvements

Deploy the model using FastAPI

Add SHAP-based model interpretability

Experiment with ensemble averaging
