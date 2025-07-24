# Laptop-Price-Prediction-
💻 Laptop Price Predictor
This repository contains a machine learning project that predicts laptop prices based on various specifications. The project involves data preprocessing, exploratory data analysis (EDA), feature engineering, and training multiple regression models to find the best-performing one.

✨ Features
Data Preprocessing:

Handling missing values and duplicates.

Cleaning and transforming 'Ram' and 'Weight' columns.

Extracting numerical values from 'ScreenResolution' and calculating Pixels Per Inch (PPI).

Categorizing 'Cpu' and 'Gpu' brands.

Processing 'Memory' column to separate HDD, SSD, Hybrid, and Flash Storage.

Categorizing 'OpSys' into broader groups (Windows, Mac, Others/No OS/Linux).

Exploratory Data Analysis (EDA):

Visualizations to understand the distribution of 'Price' and its relationship with other features (e.g., Company, TypeName, Touchscreen, IPS, CPU Brand, RAM, GPU Brand, OS, Weight).

Feature Engineering:

Creation of 'Touchscreen', 'IPS', and 'ppi' features from 'ScreenResolution'.

Creation of 'Cpu brand' from 'Cpu'.

Separation of 'Memory' into 'HDD' and 'SSD' components.

Model Training & Evaluation:

Implementation and evaluation of various regression models:

Linear Regression

Ridge Regression

Lasso Regression

K-Nearest Neighbors (KNN) Regressor

Decision Tree Regressor

Support Vector Machine (SVM)

Random Forest Regressor

Extra Trees Regressor

AdaBoost Regressor

Gradient Boosting Regressor

XGBoost Regressor

Voting Regressor (Ensemble)

Stacking Regressor (Ensemble)

Evaluation metrics used: R 
2
  score and Mean Absolute Error (MAE).

🛠️ Technologies Used
Python

Pandas: For data manipulation and analysis.

NumPy: For numerical operations.

Matplotlib: For data visualization.

Seaborn: For enhanced data visualization.

Scikit-learn: For machine learning models and utilities (preprocessing, model selection, metrics).

XGBoost: For XGBoost Regressor.

Jupyter Notebook: For interactive development and analysis.
