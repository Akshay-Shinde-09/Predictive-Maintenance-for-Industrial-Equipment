Predictive Maintenance for Industrial Equipment – Data Science Project
📌 Overview

This project aims to build a machine learning model that predicts equipment failure in industrial settings. Predictive maintenance helps reduce downtime, optimize maintenance schedules, and improve operational efficiency.
The project follows a complete data science workflow—data loading, EDA, cleaning, feature engineering, modelling, and evaluation.

📂 Dataset

The dataset contains 10,000 records with 14 features related to equipment operating conditions such as temperature, rotational speed, torque, and tool wear.
Target variable: Machine Failure (0/1) with multiple failure types.

Key Features:

Product ID & Quality Type

Air & Process Temperature

Rotational Speed

Torque

Tool Wear

Failure Types (TWF, HDF, PWF, OSF, RNF)

🛠 Tools & Technologies

Python (Pandas, NumPy, Matplotlib, Seaborn)

Scikit-learn (ML modelling)

Jupyter Notebook

Machine Learning Models
Decision Tree, Random Forest, KNN, Logistic Regression, SVM

🔍 Steps Performed
1. Data Loading

Loaded the dataset using Pandas.

Checked structure, data types, and initial statistics.

2. Exploratory Data Analysis (EDA)

Visualized product distribution and failure types.

Examined variable distributions and identified correlations.

Generated summary statistics for all features.

3. Data Cleaning

Checked for missing values and duplicates.

Removed irrelevant columns and inconsistent records.

Encoded categorical features into numeric format.

Merged failure-related variables into a single target column.

4. Feature Engineering

Selected numerical features contributing to failures.

Created a unified target variable representing failure categories.

Split data into train (80%) and test (20%).

Applied cross-validation for robust evaluation.

5. Machine Learning Models

Built and compared five ML models:

Decision Tree

Random Forest

K-Nearest Neighbour

Logistic Regression

Support Vector Classifier

All models were trained and tested to identify the best-performing technique.

6. Model Evaluation

Evaluated models using:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

All models achieved 100% accuracy, indicating excellent predictive capability for this dataset.

📈 Results

All five models performed exceptionally well with accuracy = 1.0.

Models successfully classified all failure categories with perfect precision and recall.

The dataset’s quality and strong feature–target relationships contributed to the results.
