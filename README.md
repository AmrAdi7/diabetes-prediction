# Diabetes Prediction (AI Research)
Machine learning project for predicting diabetes risk using health indicators, data analysis, and predictive modeling techniques.

This project focuses on predicting diabetes risk using **machine learning models** based on health indicators such as BMI, blood pressure, glucose levels, age, and lifestyle factors. The project combines **data preprocessing, feature selection, and classification algorithms** to identify high-risk individuals and provide preventive healthcare insights.

##  Project Overview
- Designed and implemented predictive models using **Random Forest, Decision Tree, and AdaBoost** classifiers.  
- Dataset: [Diabetes Binary Health Indicators Dataset (BRFSS 2015)]. 
- Applied **feature selection (SelectKBest, Random Forest importance)** and normalization techniques.  
- Evaluation metrics included **Accuracy, Precision, Recall, and F1-score**.  
- Random Forest achieved the best performance with **85% accuracy, 0.82 precision, and 0.85 recall**.  

##  Key Results
- **Important Features**: BMI, High Blood Pressure, and Age were found to be the most significant predictors.  
- **Model Comparison**:  
  - Random Forest: Best overall performance.  
  - AdaBoost: High accuracy but weaker recall.  
  - Decision Tree: Moderate results, less robust.  

##  Technologies Used
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)  
- Jupyter Notebook  
- CSV dataset for structured health indicators  

##  Project Structure
- `CRP.ipynb` → Main Jupyter Notebook with preprocessing, model training, and evaluation.  
- `diabetes_binary_health_indicators_BRFSS2015.csv` → Dataset used for model training/testing.  
- `Report_AmrAdi.docx` → Detailed research report and findings.  

##  Future Work
- Apply **SMOTE or class weighting** to handle class imbalance.  
- Experiment with **deep learning models (ANN, CNN, LSTMs)** for better prediction.  
- Use **Explainable AI methods (SHAP, LIME)** to improve model interpretability for healthcare professionals.  
- Expand dataset with **real-time health records and wearable device data** for more generalizable results.  

---
Developed by **Amr Adi**  

