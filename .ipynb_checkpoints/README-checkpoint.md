# STAT301Project

## Introduction to the Dataset
This multivariate heart disease dataset, compiled in 1988 from Cleveland, Hungary, Switzerland, and Long Beach V, contains 76 attributes per patient, although most studies focus on a refined subset of 14 key predictors. The dataset includes both continuous variables (e.g., age, cholesterol, blood pressure) and categorical variables (e.g., chest pain type, thalassemia, number of major vessels colored by fluoroscopy), providing a balanced mix of quantitative and qualitative patient data. This combination enables comprehensive predictive analysis, with the target variable indicating heart disease presence (0 for no disease, 1 for disease), making the dataset ideal for statistical modeling and machine learning applications in cardiology.

## **Data Description**
**Number of observations:** 1025  
**Number of Variables:** 14

- `age`: Age in $\text{years}$.
- `sex`: Sex (1 = male; 0 = female).
- `cp`: Chest Pain Type (categorical: 0 to 3).
  - 0 : Typical Angina
  - 1 : Atypical Angina
  - 2 : Non-Anginal Pain
  - 3 : Asymptomatic
- `trestbps`: Adiposity index in $\text{kg}/\text{m}^2$.
- `chol`: Serum cholestrol in $\text{mg/dl}$
- `fbs`: Fasting blood sugar > 120 $\text{mg/dl}$ (1 = true; 0 = false) 
- `restecg`: Resting electrocardiographic results (0 to 2)
  - 0 : Normal
  - 1 : Having ST-T Wave Abnormalities
  - 2 : Showing Left Ventricular Hypertrophy (LVH)
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise-induced angina (1 = yes; 0 = no)
- `oldpeak`: ST depression induced by exercise relative to rest
- `slope`: Slope of the peak exercise ST segment (0 to 2)
  - 0 : Upsloping
  - 1 : Flat
  - 2 : Downsloping
- `ca`: Number of major vessels (0–4) colored by fluoroscopy
- `thal`: Thalassemia (0 to 3)
  - 0 : Normal (No thalassemia)
  - 1 : Fixed Defect (Thalassemia minor)
  - 2 : Reversible Defect (Thalassemia Intermedia)
  - 3 : Definite Defect (Thalassemia Major)
- `target`: Heart disease indicator (1 = disease; 0 = no disease)