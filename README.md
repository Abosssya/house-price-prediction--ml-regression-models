# house-price-prediction--ml-regression-models
Predicting house sale prices using Linear and ElasticNet, DecisionTree, Random Forest and XGBoost Regressions, SHAP, and advanced model tuning (Ames Housing Dataset)


House Price Prediction using Machine Learning (Ames Housing Dataset)

This project builds and evaluates machine learning models to predict house prices using the Ames Housing Dataset. The focus is on creating a robust end-to-end pipeline that includes data preprocessing, feature engineering, model training, hyperparameter tuning, and explainability using SHAP values.

📌 Overview
The goal of this project is to predict housing prices based on various property features such as lot size, number of rooms, quality ratings, etc. A variety of models were developed and tested, ranging from baseline models to advanced ensemble methods like XGBoost.

🧠 Models Used
Default Linear Regression

ElasticNetCV Ref\gression

Tuned Decision Tree Regressor

Random Forest Regressor (with RandomizedSearchCV)

XGBoost Regressor (with early stopping and SHAP interpretability)

🧪 Evaluation Metrics
Models were evaluated using:

1) Root Mean Squared Error (RMSE)

2) Mean Absolute Error (MAE)

✅ Results Summary
The XGBoost Regressor with early stopping performed best:

Model	MAE	RMSE
Decision Tree	~22,553	~32,796
Random Forest	~17,024	~26,465
XGBoost (early stop)	~14,266	~23,354

🔍 Explainability with SHAP
To ensure the model is not a "black box", SHAP (SHapley Additive exPlanations) was used to:

Identify globally important features

Explain individual predictions (local explanations)

Build trust and transparency into the model

