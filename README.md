# Loan_Approval_Classifier

## Overview
The **Loan Approval Classifier** project aims to build a machine learning model to predict loan approval status based on various applicant attributes. The model is trained on a dataset that includes features such as age, income, education, loan amount, and credit score. The project employs advanced techniques, such as handling class imbalance and performing hyperparameter tuning, to achieve high performance in classifying loan approval status.

---

## Features

- **Data Preprocessing**: Handle categorical and numerical data, scaling, and encoding.

- **Modeling**: Train a Random Forest Classifier for loan approval prediction.

- **Model Evaluation**: Assess model performance using classification metrics such as accuracy, precision, recall, and F1-score.

- **Hyperparameter Tuning**: Fine-tune the Random Forest model using GridSearchCV.

---

## Prerequisites
- **Python 3.x**
- **Install dependencies:**
  You can install the necessary dependencies using **pip**.
- **Required Libraries**
  The following Python libraries are used in this project:
  - pandas
  - scikit-learn
  - matplotlib
  - seaborn
### Dataset: 
The dataset **loan_data.csv** contains various features related to loan applicants, such as:
- **person_age**: Age of the person
- **person_gender**: Gender of the person
- **person_education**: Highest education level
- **person_income**: Annual income
- **person_emp_exp**: Years of employment experience
- **person_home_ownership**: Home ownership status (e.g., rent, own, mortgage)
- **loan_amnt**: Loan amount requested
- **loan_intent**: Purpose of the loan
- **loan_int_rate**: Loan interest rate
- **loan_percent_income**: Loan amount as a percentage of annual income
- **cb_person_cred_hist_length**: Length of credit history in years
- **credit_score**: Credit score of the person
- **previous_loan_defaults_on_file**: Indicator of previous loan defaults
- **loan_status**: Loan approval status (1 = approved, 0 = rejected)

---

## Usage
### 1. Clone the Repository:
```bash
git clone https://github.com/ptrishita/Loan_Approval_Classifier.git
```
### 2. Load the dataset:
The dataset is expected to be in CSV format. Ensure that you have a file named "loan_data.csv" in the project directory or update the path in the code.
### 3. Run the script:
```bash
python InstructIQ_Loan_Approval_Classifier_Advanced_Techniques.ipynb
```
This will run the entire process, including data loading, preprocessing, model training, and evaluation.
