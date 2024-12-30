# Predict-the-Success-of-Bank-telemarketing
![GitHub license](https://img.shields.io/github/license/vikas-06978/Predict-the-Success-of-Bank-telemarketing)


## Project Overview
This project aims to predict the success of bank telemarketing campaigns by using machine learning techniques. The goal is to classify whether a client will subscribe to a term deposit based on various features related to the marketing campaign, client attributes, and previous campaign interactions.

## Project Title:
Predict the Success of Bank Telemarketing

## Project Type:
Machine Learning Project (MLP) - T32024

## Dataset Description
The dataset used for this project is related to direct marketing campaigns of a banking institution. The campaigns were conducted through phone calls, sometimes requiring multiple contacts to determine if the client would subscribe to a term deposit.

## Files Included:
- train.csv - The training dataset
- test.csv - The test dataset
- sample_submission.csv - A sample submission file in the required format

## Input Variables (Features):
1. last contact date - Date of last client contact

2. age - Client's age (numeric)

3. job - Type of job (categorical)

4. marital - Marital status (categorical: "married", "divorced", "single")

5. education - Level of education (categorical: "unknown", "secondary", "primary", "tertiary")

6. default - Credit in default? (binary: "yes", "no")

7. balance - Average yearly balance (numeric)

8. housing - Has housing loan? (binary: "yes", "no")

9. loan - Has personal loan? (binary: "yes", "no")

10. contact - Contact communication type (categorical: "unknown", "telephone", "cellular")

11. duration - Duration of last contact (numeric, in seconds)

12. campaign - Number of contacts during this campaign (numeric)

13. pdays - Days passed since last client contact (numeric, -1 if not previously contacted)

14. previous - Number of contacts before this campaign (numeric)

15. poutcome - Outcome of the previous marketing campaign (categorical: "unknown", "other", "failure", "success")

## Target Variable:
- target - Has the client subscribed to a term deposit? (binary: "yes", "no")

## Project Goals
- Perform exploratory data analysis (EDA) to understand the data distribution.

- Preprocess and clean the data by handling missing values and encoding categorical features.

- Train various machine learning models to predict the likelihood of a successful campaign.

- Evaluate model performance using appropriate metrics.

- Generate predictions for the test dataset and submit them in the required format.

## Approach
1. **Exploratory Data Analysis (EDA)**:

- Visualize the distribution of features.

- Identify correlations and key features impacting the target variable.

2. **Data Preprocessing**:

- Handle missing values.

- Encode categorical variables.

- Scale numeric features if necessary.

3. **Model Training**:

- Experiment with models such as Logistic Regression, Random Forest, and XGBoost.

- Use cross-validation for better model generalization.

4. **Evaluation**:

- Use accuracy, precision, recall, F1-score, and AUC to assess model performance.

5. **Submission**:

- Generate predictions and prepare submission in the required format.

## How to Use
1. Clone this repository:
    ```https://github.com/vikas-06978/Predict-the-Success-of-Bank-telemarketing.git```
2. Install required scikit-learn libraries
3. Run the Jupyter notebook or Python scripts to preprocess the data and train models.
4. Generate predictions and evaluate results.

## Results
- Details of model performance and key findings will be documented here after training.

## Acknowledgments
- Developed by [Vikas](https://github.com/vikas-06978)
- Dataset: [Kaggle - Bank Marketing Campaign Data](https://www.kaggle.com/)

If you use this project, please provide proper credit by linking to this repository.

