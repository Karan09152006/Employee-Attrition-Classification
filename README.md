# 📊 Employee Attrition Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange?style=for-the-badge&logo=pandas)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-f7931e?style=for-the-badge&logo=scikitlearn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4c72b0?style=for-the-badge)

---

## 📌 Project Overview

Employee attrition is a major challenge for organizations because losing skilled employees increases recruitment costs, reduces productivity, and affects business growth.

This project uses **Machine Learning** to analyze employee data, identify the key factors influencing attrition, and predict employees who are at risk of leaving. The insights generated can help HR teams take proactive retention measures and improve workforce planning.

---

## 🎯 Project Objectives

- Analyze employee attrition trends.
- Perform Exploratory Data Analysis (EDA).
- Identify the major factors responsible for employee attrition.
- Build and compare multiple Machine Learning models.
- Select the best-performing model.
- Generate actionable HR recommendations for reducing employee turnover.

---

## 📂 Dataset

The dataset contains employee-related information such as:

- Age
- Department
- Job Role
- Monthly Income
- Job Satisfaction
- Work-Life Balance
- Years at Company
- Overtime
- Attrition Status

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📈 Project Workflow

```
Data Collection
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Engineering
        │
        ▼
Train-Test Split
        │
        ▼
Machine Learning Models
        │
        ▼
Model Evaluation
        │
        ▼
Employee Attrition Prediction
```

---

## 📊 Exploratory Data Analysis

The project includes visualizations for:

- Employee Attrition Distribution
- Department-wise Attrition
- Job Satisfaction Analysis
- Work-Life Balance Analysis
- Monthly Income Distribution
- Age Distribution
- Correlation Heatmap
- Feature Importance

---

## 🤖 Machine Learning Models

The following models were trained and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

> **Best Model:** Random Forest Classifier

---

## 📏 Evaluation Metrics

The models were evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

---

## 📌 Key Findings

- Employee attrition is relatively low overall but follows clear patterns.
- The **Sales Department** experiences the highest employee turnover.
- Employees with **low job satisfaction** are more likely to leave.
- Poor **work-life balance** significantly increases attrition risk.
- Salary is important, but career growth and employee engagement also strongly influence retention.
- Employees in their early years of service are more likely to resign.
- **Random Forest** delivered the best prediction performance for identifying employees at risk.

---

## 💼 Business Recommendations

- Improve employee satisfaction through regular feedback.
- Focus retention initiatives on the Sales department.
- Promote better work-life balance with flexible policies.
- Provide career development opportunities.
- Strengthen onboarding and engagement programs for new employees.
- Use predictive analytics to identify employees at high risk of attrition.

---

## 📁 Project Structure

```
Employee-Attrition-Prediction/
│
├── analysis.ipynb
├── README.md
├── requirements.txt
├── summary.pdf
├── employee_attrition.csv
│
├── charts/
    ├── department_attrition.png
    ├── job_role_attrition.png
    ├── income_vs_attrition.png
    ├── confusion_matrix_heatmap.png
    ├── feature_importance.png
    └── roc_curve.png
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Employee-Attrition-Prediction.git
```

Move into the project folder

```bash
cd Employee-Attrition-Prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

---

## 📸 Results

---

## Department Attrition

![image alt](https://github.com/Karan09152006/Employee-Attrition-Classification/blob/7b673cf244052c96ec31abbbad99c07b39dae1cd/charts/chart1_department_attrition.png)

---

## Job Role Attrition

![image alt](https://github.com/Karan09152006/Employee-Attrition-Classification/blob/328342ade7bbc239c67b15d86900f72ca03b8bbf/charts/chart1_jobrole_attrition.png)

---

## Income vs Attrition

![image alt](https://github.com/Karan09152006/Employee-Attrition-Classification/blob/328342ade7bbc239c67b15d86900f72ca03b8bbf/charts/chart2_income_vs_attrition.png)

--

## Confusion Matrix Heatmap

![image alt](https://github.com/Karan09152006/Employee-Attrition-Classification/blob/7b673cf244052c96ec31abbbad99c07b39dae1cd/charts/chart3_Confusion_Matrix_Heatmap.png)

---

## Feature Importance

![image alt](https://github.com/Karan09152006/Employee-Attrition-Classification/blob/328342ade7bbc239c67b15d86900f72ca03b8bbf/charts/chart4_feature_importance.png)

---

## ROC Curve

![image alt](https://github.com/Karan09152006/Employee-Attrition-Classification/blob/328342ade7bbc239c67b15d86900f72ca03b8bbf/charts/chart5_roc_curve.png)

```

---

## 📌 Future Improvements

- Hyperparameter tuning
- Deploy using Streamlit
- Explain predictions using SHAP
- Real-time HR dashboard
- Automated retraining pipeline

---

## 🌟 Repository Support
If you found this project useful:

⭐ Star this repository

🍴 Fork this repository

📢 Share with your friends

💬 Give feedback and suggestions
