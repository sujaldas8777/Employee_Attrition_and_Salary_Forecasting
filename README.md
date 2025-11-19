# Employee Retention Model – Predicting Attrition, Sentiment & Salary Hike

This README provides a complete guide to setting up and executing the Employee Retention Model, an intelligent data-driven system that predicts employee attrition, analyzes sentiment from feedback, assigns employee value scores, and forecasts potential salary hikes.

# Dataset

The model uses the IBM HR Analytics Employee Attrition Dataset, available on Kaggle:  
[IBM HR Analytics Attrition Dataset – Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

Download the dataset and place it in your project directory before execution.
## Step-by-Step Execution Instructions
### 1. Install Dependencies
Before running the project, ensure you have Python 3.10 or higher installed.

Install all dependencies using:

```bash
pip install -r requirements.txt
```
### 2. Prepare the Dataset
 - Download the Employee Attrition Dataset.
 - Place it in the project’s folder.
 - Ensure the dataset is clean and properly formatted (e.g., .csv file).
### 3. Run the Complete Pipeline
To execute the complete pipeline, run the Jupyter Notebook file's.  

The system will:
- Analyze historical employee data to predict the likelihood of attrition.
- Perform sentiment analysis on employee feedback using BERT to assess job satisfaction and emotional tone.
- Compute an Employee Value Score combining performance, sentiment, and attrition risk.
- Predict salary hike recommendations based on employee potential and retention probability.

## Troubleshooting
- Ensure all dependencies are correctly installed via requirements.txt.
- Verify that the dataset is downloaded and paths are correctly set.
- For BERT, confirm that the Hugging Face model loads without connectivity issues.
- Restart the runtime if kernel crashes due to high memory usage.
- Validate that preprocessing steps align with dataset columns before training. 
