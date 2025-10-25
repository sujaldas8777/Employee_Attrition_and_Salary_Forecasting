# Attrition_Risk_Scoring_Model

This repository contains the Attrition Risk Scoring Model, a machine learning–based system designed to predict employee attrition using historical HR data.

The model identifies key factors influencing employee retention and assigns an Employee Value Score to each individual, enabling organizations to not only take proactive measures to enhance retention but also predict potential salary hikes and workforce value trends with data-driven precision.

#🧠 Project Overview

The Attrition Risk Scoring Model leverages machine learning and sentiment analysis to assess the likelihood of employee turnover.

It combines structured HR data with sentiment-driven insights to generate a holistic prediction of employee attrition risk.

Key Highlights

Predicts employee attrition using historical HR datasets (sourced from Kaggle).

Performs sentiment analysis using BERT to incorporate emotional and textual feedback into prediction.

Uses Random Forest and XGBoost models for classification.

Generates a employee value score for each employee based on multiple features.

Includes data visualization and feature importance analysis using Matplotlib and Seaborn.

# ⚙️ Requirements

Before running the project, ensure you have Python 3.10 or higher installed.

Install all dependencies using:

pip install -r requirements.txt

# 📊 Dataset

The model uses the Employee Attrition Dataset available on Kaggle.

# 🧩 Technologies Used

Python 3.10+

Pandas, NumPy, Matplotlib, Seaborn

Scikit-learn, Imbalanced-learn, XGBoost

Transformers (BERT)

TQDM for progress tracking
