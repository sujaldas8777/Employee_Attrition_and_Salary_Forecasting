# Attrition_Risk_Scoring_Model

This repository contains the Attrition Risk Scoring Model, a machine learning–based system designed to predict employee attrition, assess employee value, and recommend data-driven salary hikes.

The model identifies key factors influencing retention, assigns a risk score and value score to each employee, and helps organizations take proactive measures to improve retention and reward high-performing employees.

# 🧠 Project Overview

The Attrition Risk Scoring Model leverages machine learning and sentiment analysis to assess the likelihood of employee turnover.

It goes beyond attrition prediction by including employee value scoring and salary hike recommendations, helping HR teams make informed decisions.

Key Highlights:- 

Predicts employee attrition using historical HR datasets (sourced from Kaggle).

Performs sentiment analysis using BERT to incorporate emotional and textual feedback into prediction.

Uses Random Forest and XGBoost models for classification.

Assigns Value of Employee scores (1–10 scale) using the CRITIC method for weighting key features.

Generates salary hike recommendations based on employee importance, attrition risk, tenure, training, overtime, and sentiment.

Provides data visualization, feature importance analysis, and insights using Matplotlib and Seaborn.

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

# 🏁 Conclusion

This model provides a data-driven tool for HR analytics, enabling organizations to:

Identify high-risk employees and take proactive retention measures

Assign employee value scores to prioritize resources

Recommend fair and strategic salary hikes

Gain insights from data visualization and feature analysis

# Flow Diagram 

Data → Sentiment Analysis → Employee Value → Attrition Prediction → Salary Hike → Output & Visualization
