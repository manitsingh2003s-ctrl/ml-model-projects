# ml-model-project
💤 Sleep Disorder Prediction using Machine Learning
📌 Project Overview

Sleep disorders such as Insomnia and Sleep Apnea significantly affect physical health, mental well-being, and daily performance.
This project focuses on building machine learning models to accurately predict sleep disorders based on lifestyle, physiological, and demographic factors.

The goal is to assist early identification of sleep disorders using data-driven insights.
🎯 Problem Statement

Sleep disorders are often underdiagnosed due to lack of awareness and limited access to clinical testing.
This project aims to:

Develop reliable ML models to classify sleep conditions

Identify key factors contributing to sleep disorders

Compare model performance and select the best-performing algorithm
🗂 Dataset Description

The dataset contains individual-level health and lifestyle data, including:

Gender

Age

Occupation

Sleep Duration

Quality of Sleep

Physical Activity Level

Stress Level

BMI Category

Heart Rate

Daily Steps

Systolic BP

Diastolic BP

Target Variable:

Sleep Disorder Class

0 – Insomnia

1 – Sleep Apnea

2 – No Sleep Disorder

🛠️ Technologies Used

Python

Pandas & NumPy – Data preprocessing

Matplotlib & Seaborn – Data visualization

Scikit-learn – Model building & evaluation

Jupyter Notebook

🔄 Project Workflow

Data Loading & Exploration

Data Cleaning & Preprocessing

Exploratory Data Analysis (EDA)

Feature Encoding & Scaling

Model Training

Model Evaluation

Feature Importance Analysis

Model Comparison

🤖 Models Implemented

Decision Tree Classifier

Random Forest Classifier

📊 Model Performance Summary
🔹 Random Forest

Accuracy: 88%

Strong performance on majority class

Robust and less prone to overfitting

Provided stable feature importance

🔹 Decision Tree

Accuracy: 89%

Better interpretability

Slightly higher F1-score across classes

Risk of overfitting on small datasets

🏆 Best Model Selection

Although the Decision Tree achieved marginally higher accuracy,
the Random Forest Classifier was selected as the final model due to:

Better generalization ability

Reduced overfitting

More reliable performance on unseen data

🔍 Feature Importance (Top Contributors)

BMI Category

Systolic Blood Pressure

Diastolic Blood Pressure

Occupation

Age

Sleep Duration

Physical Activity Level

These features play a significant role in predicting sleep disorders.

📈 Evaluation Metrics Used

Accuracy

Precision

Recall

F1-Score

Confusion Matrix



🚀 Future Improvements

Hyperparameter tuning

Cross-validation

Class imbalance handling

Try advanced models (XGBoost, Gradient Boosting)

Deploy model using Flask or FastAPI

👨‍💻 Author

Magan Singh
Data Science Project
Boston Institute of Analytics
