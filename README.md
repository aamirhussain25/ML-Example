# ML-Example
ML Model on Melbourne Housing Dataset

🏡 Melbourne Housing Price Prediction using Random Forest
This repository contains a beginner-friendly machine learning project implemented in Google Colab. It focuses on predicting property prices in Melbourne, Australia using historical housing data. The project involves full-cycle machine learning: from data cleaning and visualization to model training and evaluation using the Random Forest Regressor.

📁 Files
File Name	Description
ML Model on Melbourne Housing dataset_.ipynb	Main Jupyter Notebook with full ML workflow
melb_data.csv	Housing dataset containing Melbourne real estate listings

📌 Project Objectives
Perform exploratory data analysis (EDA) on real-world housing data
Handle missing values and irrelevant features
Apply one-hot encoding to categorical features
Train a machine learning model using the Random Forest algorithm
Evaluate performance using Mean Absolute Error (MAE)

🧠 Features of the Dataset
Feature	Description
Rooms	Number of rooms
Type	Property type (House, Unit, etc.)
Price	Sale price (target variable)
Distance	Distance to Melbourne CBD
Landsize	Land size in square meters
Bathroom	Number of bathrooms
YearBuilt	Year the property was built
Regionname	Region in Melbourne
...	Other demographic and geographic info

🔍 Workflow Summary
1. Data Loading & Inspection
Used pandas to read melb_data.csv
Displayed shape, column types, and missing values
Checked duplicate rows and summary statistics

2. Data Cleaning
Dropped high-cardinality and unhelpful columns:
Address, SellerG, Date, Postcode, Method

Handled missing values:
Categorical columns filled with mode

3. Feature Engineering
Applied one-hot encoding to categorical variables
Split data into features (X) and target (y = Price)
Performed an 80/20 train-test split

4. Model Training
Trained a RandomForestRegressor with default parameters
Fitted the model on X_train, y_train

5. Model Evaluation
Predicted on X_test

Calculated Mean Absolute Error (MAE) for performance assessment

📈 MAE Result: Printed after training
(Shows the average prediction error in Australian dollars)

🔧 Libraries Used
pandas, numpy – data manipulation
matplotlib, seaborn – visualization
sklearn – model building & evaluation

✅ Ideal For
Beginners in machine learning
Learning how to build ML RandomForest models in Google Colab
Practicing feature preprocessing, encoding, and error evaluation
