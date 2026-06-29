# 🧠 Employee Attrition Prediction using Machine Learning

> A machine learning project that analyzes 1,470 employee records to predict attrition risk and deliver actionable HR retention strategies.

**Submitted by:** SRIDHAR S  
**Internship Project — Week 2**  
**Submission Date:** 30/06/2026

---

## 📁 Project Structure

```
EmployeeAttrition_SRIDHAR/
├── HR_Attrition.csv              # Dataset (1,470 employees, 35 features)
├── analysis.ipynb                # Main Jupyter Notebook (7 Tasks)
├── HR_Director_Summary.md        # Executive Summary (Markdown)
├── HR_Director_Summary.docx      # Executive Summary (Word Document)
└── charts/
    ├── chart1_dept_jobrole_attrition.png
    ├── chart2_income_boxplot.png
    ├── chart3_confusion_matrix.png
    ├── chart4_feature_importance.png
    └── chart5_roc_curves.png
```

---

## 📊 Dataset

- **Source:** IBM HR Analytics Employee Attrition Dataset
- **Size:** 1,470 rows × 35 columns
- **Target Variable:** `Attrition` (Yes / No)
- **Attrition Rate:** ~29.7%

---

## 🔬 Tasks Covered

| Task | Description |
|------|-------------|
| Task 1 | Data Loading & Exploration |
| Task 2 | Data Cleaning & Preprocessing |
| Task 3 | Exploratory Data Analysis (EDA) |
| Task 4 | Model Training (LR, RF, GBT) |
| Task 5 | Model Evaluation & Best Model Selection |
| Task 6 | Visualizations (5 Charts) |
| Task 7 | HR Insights & Business Recommendations |

---

## 🤖 Models Used

| Model | ROC-AUC |
|-------|---------|
| Logistic Regression | **0.620** ✅ Best |
| Random Forest | 0.594 |
| Gradient Boosting | 0.575 |

---

## 🔑 Key Findings

1. **Job Satisfaction** is the #1 predictor of attrition
2. **Overtime / Burnout** is the #2 predictor
3. **Sales (34.9%) & HR (34.4%)** departments have the highest attrition rates
4. **Salary alone is NOT the root cause** — role fit and satisfaction matter more

---

## 📈 Charts

| Chart | Description |
|-------|-------------|
| Chart 1 | Attrition Rate by Department & Job Role |
| Chart 2 | Monthly Income vs Attrition (Box Plot) |
| Chart 3 | Confusion Matrix — Best Model |
| Chart 4 | Top 10 Feature Importances |
| Chart 5 | ROC Curve Comparison — All 3 Models |

---

## 🛠️ Tech Stack

- **Python 3.x**
- **pandas**, **numpy** — Data manipulation
- **matplotlib**, **seaborn** — Visualization
- **scikit-learn** — Machine Learning

---

## ✅ HR Recommendations

1. **Launch "Stay Interviews"** in Sales & HR departments targeting employees with low satisfaction scores
2. **Implement an Overtime Monitoring Alert** — flag employees logging >20% overtime in a rolling month

---

## ⚠️ Limitation

This model is an **early warning tool**, not a definitive predictor. Always combine model output with a human HR conversation before taking action.
