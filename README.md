# student-dropout-prediction
This project applies machine learning to predict student dropout in online higher education using multimodal data. It integrates student demographics, assessments, and VLE interactions to build predictive models and support early intervention strategies.
# Files Included

Data Cleanind EDA: Cleaned with EDA

Technical Dissertation 1.ipynb: Main Jupyter Notebook with full pipeline


# How to Use
## Clone the repository

git clone https://github.com/your-username/student-dropout-prediction.git

Place required CSV files (studentInfo.csv, studentAssessment.csv, etc.) into a data/ folder.

## Install dependencies

pip install pandas numpy scikit-learn seaborn matplotlib imbalanced-learn

Run the notebook Technical Dissertation 1.ipynb step by step in Jupyter.

## Models Used

Logistic Regression (baseline)

Random Forest (best performance)

## Key Features

total_clicks: VLE activity

avg_score: Average assessment score

total_assessments: Number of assessments submitted

## Output Metrics

Accuracy

Precision, Recall, F1 Score

Confusion Matrix

Visualizations of dropout trends

## Use Case

This model helps educators identify at-risk students early and design intervention strategies to improve student retention in online learning platforms.
