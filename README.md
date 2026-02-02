# Cardiovascular Disease Prediction using Ensemble Learning

## Project Overview
This graduation project focuses on predicting the presence of **cardiovascular disease** using structured medical data and applying **Ensemble Learning** techniques. The goal is to build a complete machine learning pipeline that handles data preprocessing, model building, evaluation, and interpretation.

The project demonstrates how ensemble methods can improve predictive accuracy and help identify the most influential medical indicators in healthcare.

---

## Dataset
**Cardiovascular Disease Dataset** (Kaggle):  
[https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset)

**Features include:**  
- Age  
- Gender  
- Systolic and Diastolic Blood Pressure  
- BMI  
- Cholesterol  
- Glucose  
- Smoking and Alcohol habits  
- Physical activity  
- Medical history

---

## Machine Learning Pipeline
1. **Data Exploration & Preprocessing**  
   - Handling missing values  
   - Outlier detection and treatment  
   - Normalization / Scaling  
   - Feature engineering  

2. **Model Building (Ensemble Learning)**  
   - Bagging: **Random Forest**  
   - Boosting: **XGBoost, LightGBM**  

3. **Model Evaluation**  
   - Metrics: **AUC-ROC, Precision, Recall, F1-score, Confusion Matrix**  
   - Comparison of different ensemble methods to select the best model  

4. **Model Interpretation**  
   - Feature importance analysis using built-in methods  
   - SHAP values to identify the most influential medical indicators

---

## Results
- Ensemble methods (Random Forest and XGBoost) improved predictive performance compared to single models  
- Confusion Matrix and SHAP values were used to visualize model performance and interpret feature importance  
- The pipeline is reproducible and modular for experimentation with new models or datasets

*(Optional: Include screenshots, plots, or tables here if available)*

---

## Tools & Libraries
- Python  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost, LightGBM  
- Matplotlib, Seaborn  
- SHAP

---

## How to Run
1. Clone the repository:
```bash
[git clone https://github.com/your-username/your-repo.git
](https://github.com/hatemhossamghazy)
