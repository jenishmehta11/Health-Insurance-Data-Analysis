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
   - Polynomial Regression
   - Random Forest Regression

4. **Evaluation**:
   - Mean Squared Error (MSE)
   - R-squared (R²)
   - Cross Validation

## Tools and Libraries

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## Results

| Model                                  | R-squared |
|--------------------------              |-----------|
| Linear Regression                      | 0.62      |
| Linear Regression(cross validation)    | 0.74      |
| Polynomial Regression                  | 0.83      |
| Random Forest                          | 0.88      |

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/jenishmehta11/Health-Insurance-Data-Analysis.git

2. Install dependencies
   If using pip:
    ```bash
    pip install -r requirements.txt
    ```

3. Execute the main analysis Python script:
```bash
python analysis.py
```

4. View results and make changes:

The analysis outputs (e.g., plots, predictions) will be saved in the output directory or displayed in the terminal/Jupyter Notebook.
To suggest or implement changes, create a new branch and commit your modifications (see the Contribution section).

Suggest changes or enhancements:
Open an issue on GitHub if you have an idea or found a bug.
Provide detailed descriptions of the changes or features you’re proposing.

To implement changes:
Fork the repository and follow the Contribution guidelines outlined in the Contribution section.



     
   
   
   
