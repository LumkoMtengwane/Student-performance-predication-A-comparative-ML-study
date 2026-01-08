# Student-performance-predication-A-comparative-ML-study
Overview:
For this project I wanted to compare four ML models(Linear Regression, Random Forest, XGBoost, and Support Vector Regression (SVR))—to predict student academic performance based on demographic, behavioural, and academic data. My goal was to identify the most accurate and interpretable model for early intervention in educational settings, enabling institutions to implement timely interventions for at-risk students.

---
Dataset 
Source: Kaggle – Student Performance Prediction Dataset by Amr Maree

---
Features:
- Size: 708 records
- Academic (past exam scores, study hours, attendance)
- Demographic (gender, parental education)
- Socioeconomic (internet access, extracurricular activities)
- Target Variable: Final Exam Score (regression) / Pass-Fail (classification)
  
---
Models Compared:

Model	Type	Key Characteristics:

Linear Regression	Baseline	Interpretable, assumes linearity

Random Forest	Ensemble	Robust to outliers, feature importance

XGBoost	Gradient Boosting	High accuracy, regularization, handles missing values

Support Vector Regression (SVR)	Kernel-based	Non-linear relationships, robust to outliers

---
Methodology:
Data Preprocessing – Handling missing values, encoding, scaling

Exploratory Data Analysis (EDA) – Visualizations, hypothesis testing

Model Training & Tuning – Hyperparameter optimization, cross-validation

Evaluation – Metrics: R², MAE, MSE, RMSE, ROC-AUC, F1-score

---
Results:
Best Performing Model: XGBoost
- R²: 0.81
- MAE: 1.71
- MSE: 8.07
- RMSE: 2.84

  ---
Key Findings & Predictors:
Findings:
- XGBoost outperformed all other models in accuracy and generalization
- Random Forest showed slight overfitting
- Linear Regression was limited due to non-linear relationships in data
- SVR offered moderate accuracy with higher computational cost

Predictors:  Past exam scores, attendance rate, weekly study hours

---
Lessons Learned
- Data preprocessing greatly impacts model performance
- Interpretability is crucial for stakeholder adoption
- Comparative modeling provides deeper insights into algorithmic trade-offs
- Collaboration tools (GitHub, Jupyter) enhance reproducibility

Recommendations
- Incorporate additional behavioral/psychological features
-Use explainable AI tools (SHAP, LIME) for model transparency
-Expand dataset across multiple institutions for generalizability
-Implement real-time dashboards for educators
-Ensure ethical AI practices—audit for bias and ensure data privacy

References
See full references in Deliverable 6 document. Key citations include:

Chen & Guestrin (2016) – XGBoost

Ahmad et al. (2020) – ML in education

Lundberg & Lee (2017) – SHAP

UNESCO (2021) – AI ethics in education

License
This project is for academic purposes. Dataset usage must comply with Kaggle’s terms and ethical guidelines.

