# Cardiovascular Diseases Prediction
![p-6](p-6.png)

## Problem Statement
Cardiovascular diseases are a major global cause of death, emphasizing the need to understand their causes and develop an effective system for early detection of heart attacks. The goal of this project is to predict the risk of heart attacks using machine learning models and explore the factors that contribute to cardiovascular health.

## Dataset
The dataset used in this project contains the following variables:

- Age: Age in years
- Sex: Gender (1 = male, 0 = female)
- cp: Chest pain type
- trestbps: Resting blood pressure (in mm Hg on admission to the hospital)
- chol: Serum cholesterol in mg/dl
- fbs: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
- restecg: Resting electrocardiographic results
- thalach: Maximum heart rate achieved
- exang: Exercise induced angina (1 = yes, 0 = no)
- oldpeak: ST depression induced by exercise relative to rest
- slope: Slope of the peak exercise ST segment
- ca: Number of major vessels (0-3) colored by fluoroscopy
- thal: Thalassemia type (3 = normal, 6 = fixed defect, 7 = reversible defect)
- Target: Presence of heart disease (1 = yes, 0 = no)

## Steps Performed
1. **Preliminary Analysis**
   - Inspected the data structure, identified missing values, duplicates, etc.
   - Removed duplicates (if any) and treated missing values using an appropriate strategy.

2. **Data Exploration**
   - Conducted a statistical summary of the data, analyzing measures of central tendencies and spread.
   - Explored categorical variables using count plots.
   - Studied the occurrence of cardiovascular diseases across different age categories.
   - Analyzed the composition of patients based on gender.
   - Examined the relationship between resting blood pressure and the occurrence of heart attacks.
   - Investigated the relationship between cholesterol levels and the target variable.
   - Explored the association between peak exercising and heart attack occurrence.
   - Examined the impact of thalassemia on cardiovascular diseases.
   - Explored the influence of other factors on the occurrence of cardiovascular diseases.
   - Used a pair plot to understand the relationship between all the given variables.

3. **Model Building**
   - Built baseline models using logistic regression and random forest to predict the risk of heart attacks.
   - Explored the results using correlation analysis and logistic regression for feature selection, considering standard error and p-values from statistical models.

## Conclusion
Through this project, we successfully predicted the risk of heart attacks using machine learning models and gained insights into the factors influencing cardiovascular health. The findings can contribute to early detection and prevention of cardiovascular diseases.

For more details, please refer to the Jupyter Notebook [here](link_to_notebook.ipynb).

