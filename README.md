# synent-task8-mlmodel-ayeshaasna

### 📌 Description
Machine learning model built on housing dataset with preprocessing, training, evaluation, and best model selection using regression algorithms.

---

# 📘 README.md (Task 8)

```markdown
# Task 8: Machine Learning Model

## Problem Statement
Build and evaluate machine learning models to predict housing prices.

## Dataset
- Housing dataset
- Target: median_house_value

## Approach
- Handled missing values
- Applied scaling for numeric data
- Used OneHotEncoding for categorical data
- Built pipelines for preprocessing + model
- Trained:
  - Linear Regression
  - Random Forest Regressor
- Compared models using RMSE and R²

## Results
- Model comparison table
- Best model selected based on lowest RMSE
- Model saved using joblib

## Output Files
- model_evaluation.csv
- best_model.pkl
- task8_report.txt

## How to Run (VS Code)

Step 1: Open terminal

Step 2: Run:
```bash
python task8.py
