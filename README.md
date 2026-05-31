# Heart Disease EDA & Feature Selection

Exploratory data analysis and feature selection on the Heart Disease dataset
to identify the most significant features for predicting heart disease.

##  View Notebook
GitHub may not render the notebook preview directly.
To view the full notebook with outputs, open it in Google Colab:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Yugal25/heart-disease-eda/blob/main/heart_disease_eda.ipynb)
## Objective
Identify the most relevant features that influence heart disease
using statistical methods before building a prediction model.

## Dataset
- **Source:** [Heart Failure Prediction Dataset - Kaggle](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)
- **Rows:** 918 patients
- **Target:** `HeartDisease` (0 = No, 1 = Yes)

##  What's Inside
- Data cleaning & preprocessing
- Feature engineering (IsOld, HeartWork, CholesterolLevel, etc.)
- Encoding categorical variables
- **Pearson Correlation** — for numeric features vs target
- **Chi-Square Test** — for categorical features vs target
- Final feature selection based on both tests

## Selected Features
`ST_Slope_Up`, `ST_Slope_Flat`, `ExerciseAngina_Y`, `ChestPainType_ATA`,
`MaxHR`, `Oldpeak`, `Sex_M`, `FastingBS`, `IsOld`, `Age`,
`ChestPainType_NAP`, `HeartWork`

## Libraries Used
- pandas, numpy
- scipy
- matplotlib, seaborn
- scikit-learn
