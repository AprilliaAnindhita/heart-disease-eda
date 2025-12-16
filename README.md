## Heart Disease Exploratory Data Analysis & Prediction

### Project Overview
This project focuses on exploratory data analysis (EDA) and machine learning
modeling of a heart disease dataset. The objective is to identify demographic
and clinical factors associated with heart disease and to build a baseline
classification model for prediction.

This project is designed as a beginner-to-intermediate level data analysis
portfolio using real-world healthcare data.

### Dataset
- **Name**: Heart Disease Prediction Dataset
- **Source**: Kaggle
- **Format**: CSV
- **Records**: 270 patients
- **Features**: 14 demographic and clinical variables

### Target Variable
- **Heart Disease**
  - `0` → Absence
  - `1` → Presence
 *The target variable was encoded for modeling purposes.*

### Tools & Technologies
- Python
- Google Colab
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- Tableau Public

### Analysis Workflow
The project follows a structured data analysis pipeline:

1. Data loading and inspection
2. Exploratory Data Analysis (EDA)
3. Feature encoding and preprocessing
4. Train-test split and feature scaling
5. Logistic Regression model training
6. Model evaluation (Accuracy, Confusion Matrix, ROC-AUC)
7. Feature importance analysis and interpretation
8. Interactive data visualization using Tableau

### Key Findings
- Patients with heart disease tend to be older
- Male patients show a higher proportion of heart disease
- Maximum heart rate (Max HR) shows a strong negative relationship with heart disease
- The number of vessels detected by fluoroscopy is the most influential predictor

### Model Performance
- **Model**: Logistic Regression
- **Accuracy**: ~85%
- **AUC Score**: ~0.87

The model demonstrates good discriminatory power and serves as a strong baseline
for further predictive modeling.

### Interactive Dashboard
An interactive Tableau dashboard was created to visualize key findings from the
EDA and model insights.

🔗 **Tableau Public Dashboard**  
https://public.tableau.com/app/profile/aprillia.anung.anindhita/viz/HeartDiseasePatientAnalysisDashboard/Dashboard1

### Project Structure
heart-disease-eda/
###### ├──heart_disease_eda.py
###### ├── heart_disease_prediction.py
###### ├── Heart_Disease_Prediction.csv
###### ├── README.md


### Future Work
- Experiment with additional classification models (Random Forest, XGBoost)
- Perform hyperparameter tuning
- Apply cross-validation for more robust evaluation
- Explore explainability methods such as SHAP values
  
### Author
**Aprillia Anung Anindhita**  
Informatics Engineering Student  
*Beginner Data Analyst Portfolio Project*
