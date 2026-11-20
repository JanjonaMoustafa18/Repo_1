# Repo_1
Week 1 — Linear Regression Pipeline

A robust, end-to-end Machine Learning pipeline implementing Linear Regression to predict continuous targets from scratch and using Scikit-Learn.

📌 Project Overview

This project demonstrates the core theoretical and practical principles of continuous target estimation:

Exploratory Data Analysis (EDA): Inspecting feature correlations and scatter plots with the target.

Data Preprocessing: Handling missing values, duplicate removal, and categorical encoding.

Model Training: Fitting a Linear Regression model ($y = mx + b$) using Ordinary Least Squares (OLS).

Manual vs. Library Metric Evaluation: Computing and interpreting regression metrics (MAE, MSE, RMSE).

Visualization: Plotting the fitted regression line against actual test data distributions.

🗂️ Workflow & Architecture

Data Ingestion & Cleaning: Load tabular dataset with pandas, verify missing values, and clean records.

EDA & Visualizations: Correlation matrices and scatter plots (e.g., BMI / Blood Pressure vs Target).

Train / Test Split: Partition dataset (80% Train, 20% Test) to validate model generalization.

Model Training & Inference: Fit LinearRegression(), extract learned coefficients ($m$) and intercept ($b$).

Evaluation Metrics:

MAE (Mean Absolute Error): $\frac{1}{n}\sum \vert{}y - \hat{y}\vert{}$ (Robust to outliers).

MSE (Mean Squared Error): $\frac{1}{n}\sum (y - \hat{y})^2$ (Penalizes larger mistakes).

RMSE (Root Mean Squared Error): $\sqrt{\text{MSE}}$ (Interpreted in original target units).

Regression Line Visualization: Plotting actual observations alongside the fitted regression line ($y = mx + b$).

📊 Summary of Results

The fitted model extracted optimal weights using Least Squares optimization.

Baseline metrics demonstrate balanced performance across training and test splits without severe underfitting or overfitting.

🚀 How to Run

Clone this repository:

git clone https://github.com/<your-username>/<your-repo-name>.git cd <your-repo-name> 

Install required dependencies:

pip install numpy pandas matplotlib scikit-learn 

Open and run the notebook:

jupyter notebook notebook_1_linear_regression.ipynb 

(Or open directly in Google Colab and run all cells).

