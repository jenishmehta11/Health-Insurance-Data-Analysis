# Health-Insurance-Data-Analysis
This project involves analyzing a health insurance dataset to extract meaningful insights, perform statistical analyses, and build predictive models. The dataset contains information about individuals' medical insurance costs, demographics, and habits.

Dataset Description

The dataset contains the following columns:

Column

Description

age

Age of the individual

sex

Gender of the individual

bmi

Body Mass Index (BMI)

children

Number of children covered by the insurance

smoker

Smoking status (yes or no)

region

Residential region (northwest, southeast, etc.)

charges

Medical insurance cost (target variable)

Project Objectives

Perform exploratory data analysis (EDA) to understand the data.

Visualize the relationships between variables.

Build and evaluate predictive models to estimate medical insurance costs.

Fine-tune models using hyperparameter optimization.

Tools and Libraries

The following Python libraries are used in this project:

Data Analysis and Visualization:

pandas

numpy

matplotlib

seaborn

Modeling:

scikit-learn

statsmodels

Key Steps

1. Data Preprocessing

Handle missing values (if any).

Convert categorical variables to numerical formats.

Normalize or scale numerical features if required.

2. Exploratory Data Analysis

Summarize data to identify trends and patterns.

Visualize:

Age distribution

BMI vs. charges

Smoking status impact on charges

3. Predictive Modeling

Implement regression models such as:

Linear Regression

Ridge Regression

Random Forest

Evaluate model performance using metrics like R-squared, Mean Squared Error (MSE), and cross-validation scores.

4. Hyperparameter Tuning

Use techniques like Grid Search and Randomized Search to optimize model parameters.

Example Results

Model

R-squared

RMSE

Linear Regression

0.75

4600

Ridge Regression

0.76

4500

Random Forest

0.87

3200

Installation

To run this project, ensure you have Python 3.7+ installed. Install the required libraries using:

pip install -r requirements.txt

Usage

Clone this repository:

git clone https://github.com/your_username/health-insurance-analysis.git

Navigate to the project directory:

cd health-insurance-analysis

Open the Jupyter Notebook:

jupyter notebook Medical_Insurance.ipynb

Run the cells step-by-step to analyze the dataset and build models.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Contributions

Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request.

