# Loan Prediction - Exploratory Data Analysis (EDA)

## Overview

This project performs **Exploratory Data Analysis (EDA)** on a Loan Prediction dataset using **Python**, **Pandas**, **Matplotlib**, and **Seaborn**. The objective is to clean the data, understand feature distributions, detect missing values and outliers, and identify relationships between variables before building machine learning models.

> **Project Status:** ✅ EDA Completed | 🚧 Machine Learning Model Coming Soon

---

## Objective

The main goal of this project is to explore and understand the characteristics of loan applicants through data visualization and statistical analysis. This serves as the first step in an end-to-end machine learning pipeline for loan approval prediction.

---

## Dataset

The dataset contains information about loan applicants, including demographic details, financial information, and loan-related attributes.

### Features

| Feature | Description |
|----------|-------------|
| Loan_ID | Unique loan application ID |
| Gender | Applicant gender |
| Married | Marital status |
| Dependents | Number of dependents |
| Education | Graduate / Not Graduate |
| Self_Employed | Self-employed status |
| ApplicantIncome | Applicant's monthly income |
| CoapplicantIncome | Co-applicant's monthly income |
| LoanAmount | Loan amount requested |
| Loan_Amount_Term | Loan repayment term (months) |
| Credit_History | Credit history (1 = Good, 0 = Poor) |
| Property_Area | Urban, Semiurban or Rural |

---

## Project Structure

```text
Loan-Prediction-EDA/
│
├── Loan Prediction Dataset.csv
├── Loan Prediction EDA.ipynb
└── README.md
```

---

## Data Cleaning

The following preprocessing steps were performed:

- Checked dataset information and summary statistics
- Identified missing values
- Filled categorical missing values using the **mode**
- Filled missing `LoanAmount` values using the **median**
- Filled missing `Loan_Amount_Term` using the **mode**
- Verified that no missing values remained

---

## Exploratory Data Analysis

The notebook includes:

### Dataset Overview
- Dataset shape
- Data types
- Summary statistics
- Missing value analysis

### Univariate Analysis
- Count plots for:
  - Gender
  - Married
  - Dependents
  - Education
- Histograms for:
  - Applicant Income
  - Co-applicant Income
- Boxplots for:
  - Applicant Income
  - Co-applicant Income
  - Loan Amount
  - Loan Amount Term

### Bivariate Analysis
- Applicant Income vs Loan Amount
- Average Loan Amount by Property Area
- Average Applicant Income by Credit History

### Correlation Analysis
- Correlation Heatmap for numerical features

---

## Key Insights

- Most applicants are male.
- The majority of applicants are graduates.
- Applicant income and loan amount contain several high-value outliers.
- Most applicants have a positive credit history.
- Applicant income generally increases with loan amount, although the relationship is not very strong.
- Property areas show slight variation in average loan amounts.

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Skills Demonstrated

- Data Cleaning
- Missing Value Imputation
- Exploratory Data Analysis (EDA)
- Data Visualization
- Correlation Analysis
- Outlier Detection
- Python for Data Analysis

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/your-username/Loan-Prediction-EDA.git
```

Navigate to the project folder:

```bash
cd Loan-Prediction-EDA
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn notebook
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
Loan Prediction EDA.ipynb
```

---

## Future Work

The next phase of this project will include:

- Feature Engineering
- Encoding Categorical Variables
- Feature Scaling
- Train-Test Split
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Model Evaluation
- Hyperparameter Tuning
- Loan Approval Prediction

---

## Author

**Vasista Dhavala**

GitHub: https://github.com/vasista-dhavala
