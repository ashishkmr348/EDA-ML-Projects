# 📘 Loan Repayment Prediction Using Machine Learning

This project focuses on predicting whether a borrower will **fully repay a loan** or **default**, using machine learning classification models.  
The analysis includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation.  

This repository serves as a complete reference for understanding loan risk assessment using modern ML techniques.

---

## ⭐ Key Features

- Comprehensive **data exploration & visualization**
- Feature preprocessing and transformations
- Training multiple ML algorithms:
  - Logistic Regression  
  - Decision Trees  
  - Random Forest  
  - Gradient Boosting Classifier  
- Model comparison using accuracy, classification reports, and ROC–AUC
- Clean, reproducible Jupyter Notebook workflow
- Suitable for academic, portfolio, and real-world ML use cases

---

## 📂 Project Structure

├── loan_data.csv # Dataset used for prediction

├── Loan_Repayment_Prediction.ipynb # Main notebook containing analysis + ML modeling

└── README.md # Project documentation


---

## 📊 Dataset Description

The dataset contains loan application records with financial and personal details.  
Target Variable: **`not.fully.paid`**  
- **1 = Borrower defaulted / did not fully pay**  
- **0 = Borrower successfully repaid**  

### **Main Columns Include:**

| Feature | Description |
|--------|-------------|
| `credit.policy` | Meets credit underwriting (1 = yes, 0 = no) |
| `purpose` | Purpose of the loan (credit card, debt consolidation, etc.) |
| `int.rate` | Interest rate of the loan |
| `installment` | Monthly loan payment |
| `log.annual.inc` | Log-transformed annual income |
| `dti` | Debt-to-income ratio |
| `fico` | FICO credit score |
| `revol.bal` | Revolving credit balance |
| `inq.last.6mths` | Number of inquiries in past 6 months |
| `delinq.2yrs` | Number of recent delinquencies |
| `not.fully.paid` | **Target label** |

---

## 🎯 Objectives of the Project

1. Understand the relationship between borrower characteristics and loan repayment.  
2. Perform EDA to identify important patterns.  
3. Preprocess data and encode categorical variables.  
4. Train various machine learning classification models.  
5. Evaluate model performance and choose the best one.  

---

## 🧠 Machine Learning Workflow

### ✔ 1. Data Loading & Cleaning
- Handling missing values  
- Data type corrections  
- Exploratory statistics  

### ✔ 2. Exploratory Data Analysis (EDA)
- Distribution plots  
- Correlation heatmaps  
- Loan purpose frequency  
- FICO score distribution  

### ✔ 3. Preprocessing & Feature Engineering
- Label encoding for categorical features  
- Train–test split  
- Handling imbalanced classes (if needed)  

### ✔ 4. Model Training
Trained classification models include:
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- Gradient Boosting  

### ✔ 5. Model Evaluation
Metrics used:
- Accuracy  
- Precision & Recall  
- Confusion Matrix  
- ROC Curve & AUC Score  

### ✔ 6. Model Comparison
The notebook includes a final comparison to determine the most effective model for predicting defaults.

---

## 📈 Sample Insights (Replace with your actual findings)

- Borrowers with **low FICO scores** have a much higher probability of default.  
- Higher **interest rates** significantly increase the default risk.  
- Loans for **small business purposes** show higher non-repayment rates.  
- Ensemble methods (Random Forest, Gradient Boosting) outperform basic models.  

---

| Model               | Accuracy | ROC–AUC | Notes                       |
| ------------------- | -------- | ------- | --------------------------- |
| Logistic Regression | 0.78     | 0.84    | Baseline performance        |
| Decision Tree       | 0.82     | 0.80    | Slight overfitting observed |
| Random Forest       | 0.86     | 0.91    | Strong, stable performance  |
| Gradient Boosting   | 0.88     | 0.93    | Best model overall          |

---

## 📬 Contribution

Contributions are encouraged!
Feel free to open a pull request or report an issue.



