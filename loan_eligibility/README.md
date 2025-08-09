# Loan Approval Prediction Project

## Project Overview

This project focuses on building a predictive model to determine loan approval status based on a comprehensive dataset of applicant information. The analysis follows a standard machine learning workflow, including data loading, exploratory data analysis, data preprocessing, model training, and evaluation.

## Steps Performed:

1.  **Data Loading and Initial Exploration**: The dataset was loaded into a pandas DataFrame. The shape and initial rows were inspected to understand the data structure.
2.  **Exploratory Data Analysis (EDA)**: Visualizations were created to explore the relationships between key features and the target variable ('LoanApproved'). This included analyzing the distribution of loan approvals across different employment statuses and marital statuses using count plots, and visualizing the distribution of employment and education levels using pie charts.
3.  **Data Preprocessing**:
    *   Checked for duplicate rows and missing values.
    *   The 'ApplicationDate' column was handled by converting it to a numerical representation (ordinal).
    *   Categorical columns ('EmploymentStatus', 'EducationLevel', 'MaritalStatus', 'HomeOwnershipStatus', 'LoanPurpose') were encoded into numerical format using Label Encoding.
    *   Features (X) and the target variable (y) were separated.
4.  **Data Splitting**: The dataset was split into training and testing sets to evaluate the model's performance on unseen data.
5.  **Model Selection and Training**: A Decision Tree Classifier was selected and trained on the training data.
6.  **Model Evaluation**: The trained model was evaluated on the testing data using standard classification metrics:
    *   Accuracy Score
    *   Confusion Matrix
    *   Classification Report (Precision, Recall, F1-score)

## Evaluation Results:

Based on the test data, the Decision Tree Classifier achieved the following results:

-   **Accuracy:** 0.99
