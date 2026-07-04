# World Happiness Score Prediction

A machine learning project using **Support Vector Regression (SVR)** to predict global happiness scores based on socioeconomic features.

## Key Results
- **Model:** Support Vector Regression (SVR)
- **Best Parameters:** `{'C': 0.25, 'degree': 2, 'gamma': 0.3, 'kernel': 'poly'}`
- **10-Fold Cross-Validation (R²):** 0.759
- **Test Set Performance (R²):** 0.846

## Features Used
`Region`, `Economy (GDP per Capita)`, `Family`, `Health (Life Expectancy)`, `Freedom`, `Trust (Government Corruption)`, `Generosity`

## How to Run
1. Install dependencies:
```bash
   pip install numpy pandas matplotlib scikit-learn
   
