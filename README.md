# Paisabaaz Credit Score Classification

This project builds a machine learning model to classify individuals' credit scores based on various financial and demographic features. It is designed for use by financial institutions like Paisabazaar to assess credit risk and improve loan decision processes.

---

## 📌 Problem Statement

**Business Context**  
Paisabazaar is a financial services company that assists customers in finding and applying for various banking and credit products. One key offering is evaluating creditworthiness. The goal of this project is to accurately classify credit scores of individuals to:

- Enhance credit assessment processes
- Minimize the risk of loan defaults
- Provide better personalized financial services

---

📁 Repository Structure 

<pre lang="markdown"><code> ``` Paisabaaz-Project/ ├── myCode.ipynb # Main Jupyter notebook with full ML pipeline ├── original_dataset.csv # Original raw dataset ├── cleaned_dataset.parquet # Cleaned data after preprocessing ├── catboost_info/ # CatBoost training logs and metrics │ ├── learn_error.tsv │ ├── time_left.tsv │ └── catboost_training.json ├── problem_statement.pptx # Project scope and business context ├── sample_submission.ipynb # Sample predictions/output └── README.md # Project documentation ``` </code></pre>


---

## ⚙️ ML Techniques Used

- **Data Preprocessing**: Null handling, encoding, and feature selection
- **Modeling**: CatBoost, Random Forest Classifier
- **Evaluation Metrics**: Accuracy, Balanced Accuracy, Confusion Matrix
- **Explainability**: SHAP summary plots for model interpretation

---

## 📊 Key Results

- **Best Model**: Random Forest with ~83% Accuracy
- **Feature Importance**: Identified income, loan amount, and credit history as key factors
- **SHAP Analysis**: Revealed how features contribute to good vs bad credit scores

---

## 💡 Future Improvements

- Hyperparameter tuning with Optuna
- Trying additional models like XGBoost, LightGBM
- Building a Streamlit app for real-time prediction
- Exporting models using `joblib` or `pickle`

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Devil9816/Paisabaaz-Project.git
   cd Paisabaaz-Project
