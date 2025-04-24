# Predicting-Alzheimer-s
This project focuses on developing predictive models to classify patients as either diagnosed with Alzheimer's Disease or not, using a comprehensive dataset containing patient demographics, medical history, cognitive assessments, and lifestyle factors. Accurate early diagnosis can significantly enhance treatment strategies and patient care.

Team Name: Peush (G 108)
Final Kaggle Rank: 115

## Dataset
- Source: Kaggle: Classification of Alzheimer’s Disease
- Size: 1,504 observations, 35 features
- Key Features:
  - Demographics
  - Lifestyle Factors (e.g., Physical Activity, Diet Quality)
  - Medical History
  - Clinical Measurements (e.g., BMI, Cholesterol)
  - Cognitive and Functional Assessments (e.g., MMSE, FunctionalAssessment)

## Methodology
### Exploratory Data Analysis (EDA)
- Analyzed feature distributions (Age, BMI, Cognitive scores).
- Removed irrelevant features (PatientID, DoctorInCharge).
- Assessed relationships between predictors (pair plots, boxplots).
### Modelling Approaches
1. Logistic Regression
  - Full model with all predictors.
  - Stepwise selection (AIC-based).
  - Interaction terms between cognitive features (MMSE × FunctionalAssessment).
2. Decision Trees
  - Initial tree model with 13 terminal nodes.
  - Pruned tree to 8 nodes for performance tuning.
3. Random Forest
  - Ensemble of 500 trees to reduce overfitting.
  - Variable importance analyzed.
