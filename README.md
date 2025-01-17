# Health Insurance Data Analysis

This project analyzes a health insurance dataset to uncover insights and predict medical insurance charges using machine learning models.

## Dataset Description

The dataset contains the following columns:

| Column     | Description                                      |
|------------|--------------------------------------------------|
| `age`      | Age of the individual                           |
| `sex`      | Gender of the individual                        |
| `bmi`      | Body Mass Index (BMI)                          |
| `children` | Number of dependents covered by the insurance   |
| `smoker`   | Smoking status (`yes` or `no`)                  |
| `region`   | Residential region (`northwest`, `southeast`, etc.) |
| `charges`  | Medical insurance cost (target variable)        |

## Project Features

1. **Exploratory Data Analysis (EDA)**:
   - Distribution of charges.
   - Impact of BMI, age, and smoking on charges.
   - Correlation between features.

2. **Data Preprocessing**:
   - Encoding categorical variables (`sex`, `smoker`, `region`).
   - Feature scaling and normalization.

3. **Predictive Modeling**:
   - Linear Regression
   - Ridge Regression
   - Random Forest Regression

4. **Evaluation**:
   - Mean Squared Error (MSE)
   - R-squared (R²)

## Tools and Libraries

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## Results

| Model               | R-squared | RMSE   |
|---------------------|-----------|--------|
| Linear Regression   | 0.75      | 4600   |
| Ridge Regression    | 0.76      | 4500   |
| Random Forest       | 0.87      | 3200   |

## How to Run

1. Clone
