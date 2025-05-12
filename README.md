# Heart-Disease-Classification

This repository walks through an end-to-end workflow for classifying heart disease risk using structured data from the UCI Heart Disease dataset. It covers data ingestion, preprocessing, feature engineering, model training, evaluation, and serialization for deployment.

Data Description

* heart.csv: Original dataset containing 303 samples and 14 attributes (age, sex, chest pain type, resting blood pressure, cholesterol, etc.).

* processed_data.csv: After handling missing values, encoding categorical features, feature scaling, and train-test splitting.

Modeling

* Algorithms Explored: Logistic Regression, Random Forest, XGBoost

* Selected Model: XGBoost classifier tuned via cross-validation

* Feature Engineering: One-hot encoding for categorical variables, MinMax scaling for continuous features

* Hyperparameter Tuning: Grid search on learning rate, max depth, and number of estimators

Evaluation

* Metrics Reported: Accuracy, Precision, Recall, F1-score, ROC-AUC

* Visualization: Confusion matrix, ROC curve, feature importance bar chart
