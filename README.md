# Credit Card Approval

This project involves the analysis and modeling of credit card approval data using logistic regression and grid search for hyperparameter tuning.

## Dataset

The dataset used for this project is stored in the file `cc_approvals.data`. It is loaded using pandas and then processed to handle missing values and categorical features.

## Data Preprocessing

1. Handling missing values: The missing values in the dataset are imputed using mean imputation for numerical features and most frequent value imputation for categorical features.

2. Categorical feature encoding: The categorical features are one-hot encoded to prepare the data for modeling.

3. Scaling: The features are scaled using Min-Max scaling to bring them into a similar range.

## Logistic Regression Model

A logistic regression model is trained on the preprocessed data to predict credit card approvals. The model is evaluated using accuracy and a confusion matrix.

## Hyperparameter Tuning

Grid search with cross-validation is employed to find the best hyperparameters for the logistic regression model.

## Usage

1. Clone the repository:

   ```bash
   git clone <repository_url>



**Title:** Automating Credit Card Approval Decisions: A Comparative Analysis of Machine Learning Models

Author Aaron Singh , Will Watson, Mila Avagimova

**Goal of the project:**

The goal of this project is to develop and evaluate machine learning models for automating credit card approval decisions. This will streamline the approval process, reduce the risk of human error, and improve overall efficiency.

**Data set / Source of the data:**

The Credit Card Approval dataset from the UCI Machine Learning Repository will be used for this project: http://archive.ics.uci.edu/dataset/27/credit+approval

This dataset contains information on over 20,000 credit card applications, including various factors influencing an individual's creditworthiness.







**Brief explanation of the data set:**

# The Credit Card Approval dataset contains the following features:

* **Gender:** Applicant's gender
* **Age:** Applicant's age
* **Debt:** Applicant's outstanding debt
* **Married:** Whether the applicant is married
* **BankCustomer:** Whether the applicant is a customer of the bank
* **EducationLevel:** Applicant's education level
* **Ethnicity:** Applicant's ethnicity
* **YearsEmployed:** Number of years the applicant has been employed
* **PriorDefault:** Whether the applicant has had any prior defaults
* **Employed:** Whether the applicant is currently employed
* **CreditScore:** Applicant's credit score
* **DriversLicense:** Whether the applicant has a driver's license
* **Citizen:** Whether the applicant is a U.S. citizen
* **ZipCode:** Applicant's zip code
* **Income:** Applicant's annual income
* **ApprovalStatus:** Whether the applicant's credit card application was approved

# The target variable in this dataset is **ApprovalStatus**. The goal is to build a machine learning model that can predict the value of this variable based on the other features in the dataset.

**Models:**

# Two machine learning models will be trained and evaluated in this project:

* **Logistic regression:** Logistic regression is a statistical method for predicting the probability of a binary outcome. It is a simple and effective algorithm that is well-suited for tasks like credit card approval.

* **Decision tree:** Decision trees are tree-like structures that are used for classification and regression tasks. They are easy to interpret and can be used to model complex relationships between features and the target variable.

**Evaluation:**

## The performance of the two models will be evaluated using the following metrics:

* **Accuracy:** Accuracy is the proportion of predictions that are correct.
* **Precision:** Precision is the proportion of positive predictions that are actually correct.
* **Recall:** Recall is the proportion of actual positive cases that are correctly identified as such.
* **F1-score:** The F1-score is a harmonic mean of precision and recall.

## The model with the highest F1-score will be considered the best model for predicting credit card approval status.
