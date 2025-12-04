# 🧠 Employee Wellness Prediction

### 📌 Problem Overview  
XYZ Technical Solutions recently faced a tragic loss of a valuable employee due to health concerns. To prevent future situations, the company aims to identify employees who may require mental health treatment using historical workplace and personal attributes.  

This project builds a **machine learning classification model** that predicts whether an employee needs treatment based on various demographic and workplace-related features.

---

### 🎯 Objective  
- To analyze employee wellness-related data
- To build a predictive model that classifies whether an employee **needs treatment**
- To help organizations design early intervention and wellness programs

---

### 📂 Dataset Description  
The dataset contains the following important features:

| Feature | Description |
|--------|-------------|
| Age | Age of the employee |
| Gender | Employee gender identity |
| Country | Country of residence |
| Self_employed | Whether the employee is self-employed |
| Family_history | Family history of mental illness |
| Work_interfere | If mental health affects work |
| No_employees | Company size |
| Remote_work | Works remotely? |
| Tech_company | Works in a tech organization? |
| Benefits | Employer mental health benefits |
| Care_options | Awareness of mental healthcare options |
| Wellness_program | Mentally-focused wellness initiatives |
| Seek_help | Resources to seek help available? |
| Anonymity | Anonymity protected? |
| Leave | Medical leave flexibility |
| Mental_health_consequence | Perceived negative consequences |
| Phys_health_consequence | Physical health consequences |
| Coworkers | Comfort discussing issues with coworkers |
| Supervisor | Comfort discussing issues with supervisors |
| Mental_health_interview | Discuss mental health during interview? |
| Phys_health_interview | Discuss physical health during interview? |
| Mental_vs_physical | Employer priority comparison |
| Obs_consequence | Negative consequences observed |
| Comments | Additional notes (text) |
| Treatment (Target) | Whether employee needs treatment |

---

### 🏗️ Methodology  
✔ Data Cleaning & Pre-processing  
✔ Categorical Encoding  
✔ Feature Engineering  
✔ Model Training (multiple ML models tested)  
✔ Evaluation using **Accuracy** metric  
✔ Best model used for test prediction  
✔ CSV submission file generated

---

### 🧪 Evaluation Metric  
**Accuracy**  
> Higher accuracy = better prediction performance

---

### 📁 Project Structure
```
├── data/
│   ├── train.csv
│   ├── test.csv
├── notebooks/
│   ├── EDA_and_Model_Training.ipynb
├── models/
│   ├── best_model.pkl
├── submissions/
│   ├── submission.csv
├── README.md
└── requirements.txt
```

---

### 🚀 How to Run This Project

#### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/employee-wellness-prediction.git
cd employee-wellness-prediction
```

#### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

#### 3️⃣ Open & Run Notebook
```bash
jupyter notebook
```
Run the training notebook to generate predictions and model outputs.

---

### 📌 Results  
The final accuracy achieved on evaluation data:  
**📊 Model Accuracy:

| Model | Accuracy (%) |
|--------|:-----------:|
| Logistic Regression | **70.95** |
| AdaBoost | 70.47 |
| Naive Bayes | 67.14 |
| Random Forest | 64.76 |
| Decision Tree | 62.85 |
| SVM | 55.23 |

⭐ **Best Performing Model → Logistic Regression (70.95%)**

---

### 🛡 Ethical Considerations  
- Mental health predictions should support employees, not discriminate against them.  
- Organizations must ensure confidentiality and consent while using this data.  

---

### 🧑‍💻 Author
**Ashish Kumar**  
📧 Contact: ashishkmr348@email.com  
🔗 GitHub: github.com/ashishkmr348 

---

### ⭐ Support  
If you find this project helpful, please give a ⭐ to support the work!
