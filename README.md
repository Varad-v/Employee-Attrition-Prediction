# 👥 Employee Attrition Prediction

A Machine Learning project that predicts employee attrition using HR analytics data. The objective is to identify employees who are likely to leave an organization, enabling proactive and data-driven workforce management.

---

## 📌 Project Overview

Employee attrition is a significant challenge for organizations as it affects productivity, recruitment costs, and employee morale.

This project applies machine learning techniques to analyze employee-related factors and predict whether an employee is likely to leave the company.

The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), model development, evaluation, and interpretation of results.

---

## 🎯 Objectives

- Analyze employee data to identify factors influencing attrition.
- Perform data cleaning and preprocessing.
- Visualize trends and relationships within the dataset.
- Train multiple machine learning classification models.
- Compare model performance using various evaluation metrics.
- Generate actionable insights for HR decision-making.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📂 Dataset

- IBM HR Analytics Employee Attrition Dataset
- Employee Records: 1,470
- Features: 35
- Target Variable: Attrition

---

## 📊 Exploratory Data Analysis

The project includes several visualizations and analyses, including:

- Employee Attrition Distribution
- Department-wise Attrition
- Job Role Analysis
- Monthly Income vs Attrition
- Work-Life Balance Analysis
- Correlation Heatmap
- Years at Company Analysis

---

## 🤖 Machine Learning Models

The following models were implemented and compared:

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

---

## 📈 Model Performance

| Model | Accuracy | ROC-AUC |
|---------|---------:|--------:|
| Logistic Regression | 76% | 0.804 |
| Random Forest | 84% | 0.775 |
| Gradient Boosting | **85%** | 0.794 |

---

## 🔍 Key Insights

- Employee attrition is influenced by multiple workplace and personal factors.
- Salary, work-life balance, years at the company, and job role significantly impact employee retention.
- Gradient Boosting achieved the highest classification accuracy.
- Logistic Regression demonstrated the strongest ROC-AUC score.

---

## 📁 Project Structure

```
Employee-Attrition-Prediction/
│
├── Employee_Attrition_Prediction.ipynb
├── README.md
├── requirements.txt
├── images/
│   ├── correlation_heatmap.png
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   └── feature_importance.png
└── data/
```

---

## 🚀 Future Improvements

- Hyperparameter tuning
- Model deployment using Streamlit or Flask
- Explainable AI using SHAP
- Cross-validation and model optimization

---

## 📚 Key Learnings

- Importance of thorough data preprocessing.
- Understanding class imbalance in classification problems.
- Comparing models using multiple evaluation metrics.
- Translating model outputs into business insights.

---

## 👨‍💻 Author

**Varad Khatavkar**

Artificial Intelligence & Data Science Engineer

GitHub: https://github.com/Varad-v

LinkedIn: *(Add your LinkedIn profile URL)*

---

## ⭐ Acknowledgement

This project was completed as part of the **XYlofy AI Internship Program** to gain practical experience in applying machine learning techniques to solve real-world business problems.
