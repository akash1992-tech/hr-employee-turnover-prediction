# hr-employee-turnover-prediction
# 🚗 Salifort Motors - HR Employee Turnover Prediction

## 📊 Project Overview

This project explores employee turnover at **Salifort Motors**, a multinational vehicle manufacturing company. High turnover is a growing concern, both culturally and financially. This analysis aims to:
- Identify key factors contributing to employee departure
- Build a predictive model to estimate the likelihood of an employee leaving
- Provide actionable recommendations to reduce turnover and improve employee retention

The dataset used in this project (`HR_capstone_dataset.csv`) includes 14,999 employees and 10 self-reported features related to job satisfaction, evaluation, workload, and employment status.

---

## 🧠 Goals

- Analyze the factors leading to employee turnover
- Build and compare predictive models (Logistic Regression, Decision Tree, Random Forest, XGBoost)
- Interpret model outputs and feature importance
- Recommend data-driven solutions to improve retention and employee satisfaction

---

## 📁 Dataset Overview

| Column Name         | Type   | Description                                                     |
|---------------------|--------|-----------------------------------------------------------------|
| satisfaction_level  | float  | Employee’s self-reported satisfaction level (0-1)              |
| last_evaluation     | float  | Last performance evaluation score (0-1)                        |
| number_project      | int    | Number of projects handled                                     |
| average_montly_hours| int    | Average monthly work hours                                     |
| time_spend_company  | int    | Number of years at the company                                 |
| Work_accident       | int    | 1 if the employee had a work accident, 0 otherwise             |
| left                | int    | 1 if the employee left the company, 0 otherwise                |
| promotion_last_5years | int  | 1 if promoted in last 5 years, 0 otherwise                     |
| department          | object | Employee’s department                                          |
| salary              | object | Salary level: 'low', 'medium', 'high'                         |

---

## ⚙️ Tools & Technologies

- **Python**
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Exploratory data visualization
- **Scikit-learn** – Machine learning models and evaluation
- **XGBoost** – Advanced boosting model
- **Jupyter Notebook** – Interactive analysis

---

## 🔍 Steps & Workflow

1. **Data Cleaning & Exploration**
   - Handle missing values
   - Encode categorical variables
   - Visualize relationships with target (`left`)

2. **Feature Engineering**
   - Analyze correlation & multicollinearity
   - One-hot encoding for categorical columns

3. **Modeling**
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - XGBoost

4. **Evaluation**
   - Compare models using accuracy, precision, recall, F1-score, ROC-AUC
   - Feature importance analysis

5. **Recommendation Report**
   - Present findings to leadership
   - Suggest actionable next steps to reduce employee turnover

---

## 📌 Key Insights

- Satisfaction level and number of projects are strong indicators of turnover
- High working hours and low promotions may contribute to dissatisfaction
- XGBoost and Random Forest performed best in prediction accuracy

---

## 📝 Recommendations

- Monitor and improve employee satisfaction through surveys and feedback loops
- Avoid employee overload by balancing project assignments
- Increase transparency and fairness in promotion decisions
- Focus on work-life balance, especially for long-tenured employees

---


