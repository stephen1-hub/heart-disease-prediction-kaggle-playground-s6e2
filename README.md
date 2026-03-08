# heart-disease-prediction-kaggle-playground-s6e2
# Heart Disease Prediction

## 🏆 Overview
Predicting the likelihood of heart disease using clinical and diagnostic features. The project focuses on maximizing **AUC-ROC**, the primary metric for model evaluation.

- **Final AUC-ROC:** 0.94219
- **Model:** Random Forest Classifier

---

## 📊 Dataset
- Training set with clinical features and Heart Disease target
- Test set for predictions/submission
- Features include Age, Sex, Chest Pain Type, BP, Cholesterol, Max HR, ST Depression, Number of Vessels, Thallium, etc.

---

## 🔍 Methodology
1. **EDA & Feature Analysis**: Analyzed feature correlations with the target  
2. **Feature Selection**: Selected features with strong positive/negative correlation  
3. **Model Training**: Random Forest classifier with hyperparameter tuning  
4. **Evaluation**: Used **AUC-ROC** for model validation

---

## 📈 Results
- Local validation AUC: ~0.87  
- Test AUC: 0.94219  

### Key Insights
- Features with high correlation (positive or negative) carry most predictive power  
- Probability-based predictions are essential for AUC evaluation  
- Random Forest performs strongly on structured medical data

---

## 🛠 Tools & Technologies
- Python, Jupyter Notebook  
- Pandas, NumPy, Scikit-Learn  
- Tableau / Power BI for visualizations  

---

## 📂 Repository Structure
