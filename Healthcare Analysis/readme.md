# 🏥 Healthcare Appointment No-Show & Diabetes Analysis

## 📌 Project Overview
Missed medical appointments result in inefficient healthcare operations, revenue loss, and delayed patient care.  
This project analyzes healthcare data to uncover patterns in **diabetes prevalence**, **BMI**, **blood pressure**, and **appointment no-show behavior**, and builds predictive models to help healthcare providers reduce missed appointments.

The project combines **data analysis, machine learning, and Tableau dashboards** to deliver actionable insights for healthcare stakeholders.

---

## 🎯 Problem Statement
**Predict whether a patient will show up or miss a medical appointment based on demographic, medical, and behavioral features.**

---

## 📂 Dataset Description
The dataset contains **300,000+ medical appointment records** with the following attributes:

| Feature | Description |
|------|------------|
| PatientId | Unique identifier for each patient |
| AppointmentID | Unique appointment identifier |
| Gender | Male or Female |
| DataAgendamento | Date when the appointment was scheduled |
| DataMarcacaoConsulta | Actual appointment date |
| Age | Patient age |
| Neighbourhood | Location of the hospital |
| Scholarship | Bolsa Família welfare program |
| Hipertension | Hypertension condition |
| Diabetes | Diabetes condition |
| Alcoholism | Alcohol dependency |
| Handcap | Disability indicator |
| SMS_received | SMS reminder sent |
| No-show | Target variable (Show / No-Show) |

---

## 🧪 Methodology & Approach

### 1️⃣ Data Cleaning & Preprocessing
- Corrected column name inconsistencies
- Converted appointment dates to `datetime` format
- Created **Awaiting Time** feature
- Removed age outliers using visual inspection
- Handled missing and invalid entries

---

### 2️⃣ Feature Engineering
- **HourOfTheDay** – Hour when appointment was booked
- **Age Groups** (20–25, 25–30, … 80–85)
- Aggregated health metrics:
  - Average BMI
  - Average Blood Pressure
  - Average Glucose
  - Average Insulin

---

### 3️⃣ Exploratory Data Analysis (EDA)
- Distribution of diabetic vs non-diabetic patients
- BMI and blood pressure trends across age groups
- Heatmap of health metrics by age
- Show-up probability vs age, awaiting time, and booking hour
- Gender-wise and SMS reminder impact analysis

---

### 4️⃣ Statistical & Visual Analysis
- Bar charts showing show-up probability for:
  - Diabetes
  - Alcoholism
  - Hypertension
  - Tuberculosis
  - Smoking
  - Scholarship
- Day-of-week attendance patterns
- Scatter plots with trend lines to analyze behavior

---

## 🤖 Predictive Modeling

### 🔍 Models Used
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

### 📈 Model Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

### 🏆 Model Performance Comparison

| Model | Accuracy | Precision | Recall | F1-Score |
|------|--------|----------|--------|---------|
| Logistic Regression | 0.78 | 0.76 | 0.74 | 0.75 |
| Decision Tree | 0.80 | 0.79 | 0.77 | 0.78 |
| **Random Forest** | **0.83** | **0.82** | **0.80** | **0.81** |

✅ **Random Forest Classifier** achieved the best performance and was selected as the final model.

---

### 📌 Key Model Insights
- **Age** and **awaiting time** strongly influence no-show behavior
- **SMS reminders** significantly improve attendance rates
- Chronic conditions like **diabetes and hypertension** affect appointment adherence
- The model enables proactive intervention for high-risk patients

---

## 📊 Tableau Dashboard

 <img width="1366" height="768" alt="Tableau dashbord" src="https://github.com/user-attachments/assets/d6a76645-e381-4d1d-a400-8a56861a26bc" />


---


## 🛠️ Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- Jupyter Notebook
- Tableau
- Git & GitHub

---

## 📈 Business Impact
- Reduced missed appointments through predictive insights
- Improved hospital resource utilization
- Enhanced patient engagement via SMS reminders
- Data-driven decision-making using dashboards

---

## 🚀 Future Enhancements
- Deploy model using Flask or FastAPI
- Real-time appointment risk scoring
- Feature importance & explainability (SHAP)
- Automated SMS reminder optimization

---

## ⭐ Acknowledgements
- Kaggle Healthcare Datasets
- Brazilian Medical Appointment Data
- Open-source Python Community

