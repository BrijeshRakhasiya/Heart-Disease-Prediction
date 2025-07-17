# Heart Disease Prediction

## Overview
This project implements a machine learning model to predict the likelihood of heart disease based on various medical attributes. Using patient health data, our model provides early detection and risk assessment for heart disease, which remains one of the leading causes of death in the United States.

## Model Performance and Feature Selection
- Evaluated 10 different machine learning models
- **Random Forest** with entropy criterion emerged as the best performing model:
  - Initial Accuracy: **90.63%**
  - Accuracy after feature selection: **89.36%** (less than 1% drop)

### Feature Selection Process
Implemented a majority vote feature selection technique comprising:
- Two filter-based methods
- One wrapper-based method
- Three embedded feature selection methods

### Key Features
Top 3 most contributing features based on importance:
1. **Cholesterol**
2. **Maximum Heart Rate**
3. **ST Depression**

## Statistics of Heart Disease in US
According to the Heart Disease and Stroke Statistics—2019 Update from the American Heart Association:
- Heart Disease (including Coronary Heart Disease, Hypertension, and Stroke) is the No. 1 cause of death in the US, accounting for **874,613 deaths**
- Someone in the United States has a myocardial infarction approximately every 40 seconds
- In 2019, stroke accounted for about 1 of every 19 deaths in the United States
- In 2019, someone died of a stroke every 3 minutes 30 seconds in the United States
- The average annual expenditure on heart disease (2017-2018) was **$228.7 billion** in the United States

## Dataset Description
The project uses the Heart Disease Dataset (Comprehensive) from Kaggle, containing 11 features and 1 target variable:

### Features
1. **Age:** Patient's age in years (Numeric)
2. **Sex:** Gender of patient (Male – 1, Female – 0) (Nominal)
3. **Chest Pain Type:** Categories (Nominal)
   - 1: Typical
   - 2: Typical angina
   - 3: Non-anginal pain
   - 4: Asymptomatic
4. **Resting BP:** Blood pressure at rest in mm/HG (Numeric)
5. **Cholesterol:** Serum cholesterol in mg/dl (Numeric)
6. **Fasting Blood Sugar:** > 120 mg/dl (1 = true; 0 = false) (Nominal)
7. **Resting ECG:** (Nominal)
   - 0: Normal
   - 1: ST-T wave abnormality
   - 2: Left ventricular hypertrophy
8. **Max Heart Rate:** Maximum heart rate achieved (Numeric)
9. **Exercise Angina:** Exercise-induced angina (1 = yes; 0 = no) (Nominal)
10. **Oldpeak:** ST depression induced by exercise relative to rest (Numeric)
11. **ST Slope:** The slope of the peak exercise ST segment (Nominal)
    - 0: Normal
    - 1: Upsloping
    - 2: Flat
    - 3: Downsloping

### Target Variable
- **Target:** Heart disease diagnosis (1 = present; 0 = absent)

## Required Libraries
- Python 3.8+
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Seaborn
- XGBoost

## Installation

```bash
# Clone the repository
git clone https://github.com/BrijeshRakhasiya/Heart-Disease-Prediction.git

# Navigate to the project directory
cd Heart-Disease-Prediction
```

## 📄 License

This project is licensed under the MIT License.

---
**Made ❤️ by Brijesh Rakhasiya**
