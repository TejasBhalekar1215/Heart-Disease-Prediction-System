# Heart-Disease-Prediction-System
# Heart Disease Prediction System

A machine learning system that predicts whether a patient has heart disease based on medical attributes.

## Overview

This project uses **Logistic Regression** and **Random Forest** models to classify patients as healthy or having heart disease. The Random Forest model achieves **~98.5% accuracy** on test data.

## Dataset

**Source:** Kaggle Heart Disease Dataset  
**Samples:** 303 patients  
**Features:** 13 medical attributes including:
- Age, Sex, Chest Pain Type
- Blood Pressure, Cholesterol, Fasting Blood Sugar
- Resting ECG, Max Heart Rate, Exercise-Induced Angina
- ST Depression, Slope, Major Vessels, Thalassemia

**Target:** Binary classification (0 = Healthy, 1 = Heart Disease)

## Models

| Model | Accuracy |
|-------|----------|
| Logistic Regression | 79.51% |
| Random Forest | 98.5% |

## Features

✅ **Data exploration & missing value checks**  
✅ **Train-test split** (80-20)  
✅ **Model training & evaluation**  
✅ **Confusion matrix visualization**  
✅ **Single patient prediction** (with manual input)  
✅ **Simplified model** (6 core features)  
✅ **Batch prediction** for multiple patients  

## Quick Start

1. Load your heart disease dataset
2. Train the Random Forest model on 80% of data
3. Test on remaining 20%
4. Make predictions on new patients

## Prediction Example

```
Input: 58-year-old male, BP=100, Cholesterol=248, Max HR=122
Output: ⚠️ The Person has Heart Disease
```

## Dependencies

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Files

- `heart-disease-prediction-system.ipynb` - Full implementation notebook
