# DevelopersHub-DataScience-Intership-Phase01-Task02

## Task 2: Credit Risk Prediction

### Objective

The objective of this project is to build a machine learning model that predicts whether a loan applicant is likely to default on a loan based on applicant information such as income, credit score, employment status, loan amount, and loan term.

---

## Dataset

**Loan Prediction Dataset**

The dataset contains information about loan applicants, including:

* Age
* Income
* Credit Score
* Loan Amount
* Loan Term
* Employment Status
* Loan Approved (Target Variable)

### Target Variable

| Value | Meaning           |
| ----- | ----------------- |
| 0     | Loan Not Approved |
| 1     | Loan Approved     |

---

## Project Workflow

### 1. Data Cleaning

* Loaded the dataset using Pandas.
* Checked for missing values.
* Handled missing data appropriately.
* Verified data types and dataset integrity.

### 2. Exploratory Data Analysis (EDA)

Performed visual analysis to understand the relationships between features and loan approval.

Visualizations included:

* Loan Approval Distribution
* Income Distribution
* Credit Score Distribution
* Loan Amount Distribution
* Employment Status vs Loan Approval
* Correlation Heatmap

### 3. Feature Engineering

* Applied One-Hot Encoding on the `Employment_Status` categorical feature.
* Prepared data for machine learning algorithms.

### 4. Model Training

Implemented a classification model using:

* Logistic Regression

The dataset was split into:

* Training Set
* Testing Set

using Scikit-Learn's `train_test_split()` function.

### 5. Model Evaluation

The model was evaluated using:

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1 Score

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Skills Demonstrated

### Data Cleaning

* Handling missing values
* Data preprocessing
* Feature encoding

### Exploratory Data Analysis (EDA)

* Statistical summaries
* Data visualization
* Correlation analysis

### Machine Learning

* Binary Classification
* Logistic Regression
* Model Training and Testing

### Model Evaluation

* Accuracy Measurement
* Confusion Matrix Analysis
* Precision, Recall, and F1 Score Interpretation

---

## Results

The Logistic Regression model was trained successfully and evaluated using multiple classification metrics to assess its predictive performance on unseen data.

Key evaluation metrics:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

These metrics provide insights into the model's ability to correctly classify loan approval outcomes.

---

## Repository Structure

```text
.
├── DevelopersHub-DataScience-Intership-Phase01-Task02.ipynb
├── dataset.csv
├── README.md
```

---

## Conclusion

This project demonstrates the complete machine learning workflow for a binary classification problem. By applying data preprocessing, exploratory data analysis, feature engineering, and Logistic Regression, the model can predict loan approval outcomes based on applicant characteristics and financial information.
