# Analysis-and-Prediction-of-Heart-Disease-using-Patient-Classification-Data
A comprehensive statistical classification and data analysis project conducted in RStudio. This study evaluates clinical parameters to predict the presence of heart disease in patients based on various physiological indicators.
Key Features
Statistical Classification Framework: Developed a robust binary classification model in RStudio to determine heart disease status (0 or 1) based on 13 clinical variables.
Generalized Linear Models (GLM): Utilized the glm() function with a Binomial distribution and Logit link function to model the relationship between patient health metrics and cardiac risk.
Evidence-Based Variable Analysis:
Hemodynamic Indicators: Analyzed the impact of resting blood pressure (trestbps) and max heart rate achieved (thalach).
Biochemical Assessment: Evaluated serum cholesterol (chol) and fasting blood sugar (fbs) against clinical thresholds like 120 mg/dl.
Diagnostic Markers: Integrated complex indicators such as the number of major vessels colored by fluoroscopy (ca) and thalassemia types (thal).
Data Exploration & Visualization: Comprehensive EDA using R to identify patterns in demographic data (age, sex) and clinical symptoms (chest pain types 0-3).
Model Performance & Sensitivity: achieved a high sensitivity of 86.2%, effectively identifying high-risk patients and reducing the likelihood of false-negative results.
Variable Selection: Employed Stepwise methods and Akaike Information Criterion (AIC) to identify the most significant clinical predictors, such as chest pain characteristics and vascular health
