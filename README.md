# Sweden_Auto_Insurance
Linear Regression Model

📌 Project Overview
This project performs a simple linear regression analysis on Sweden’s auto insurance dataset.
The goal is to understand the relationship between:

X → Number of claims

Y → Total payment amount

Using Python and scikit‑learn, the project builds a regression model to predict insurance payouts based on claim counts.

🎯 Objectives
Explore the distribution of insurance claim data

Visualize the relationship between claims and payments

Split data into training and testing sets

Train a Linear Regression model

Evaluate model performance using RMSE and R²

Visualize regression lines for both training and test sets

📂 Dataset Description
The dataset contains 64 records, each with:

Column	Description
X	Number of insurance claims
Y	Total payment amount (in SEK)


Both columns contain complete, non‑null values.

🧹 Data Exploration
Key steps performed:

Loaded dataset using pandas

Displayed first few rows (df.head())

Checked data types and null values (df.info())

Plotted histograms for X and Y

Created a scatter plot to visualize correlation

The scatter plot shows a non‑linear and noisy relationship, indicating that predictions may have high variance.

🧠 Model Development
A Linear Regression model was trained using:

python
from sklearn.linear_model import LinearRegression
Train/Test Split
Training size: 80%

Test size: 20%

Random state: 3

Model Training
The model was fitted on the training data:

python
lr.fit(x_train, y_train)
Predictions
Predictions were generated and rounded for readability.

📈 Model Performance
Evaluation metrics:

RMSE: 179.14

R² Score (Test): 0.23

R² Score (Train): 0.24

These scores indicate that the relationship between X and Y is weak, and linear regression does not capture the variance well — a realistic outcome for noisy real‑world insurance data.

📊 Visualizations
The notebook includes:

Histogram plots for X and Y

Scatter plot of claims vs. payments

Regression line on training data

Regression line on test data

Bar chart for selected sample values

These visualizations help interpret model behavior and dataset characteristics.

🚀 Key Features of This Project
End‑to‑end regression workflow

Real insurance dataset

Clear evaluation metrics

Visual explanation of model performance

Demonstrates practical use of scikit‑learn

├── Sweden data.csv
├── Linear_Regression.ipynb
└── README.md

👤 Author

Asmi Panigrahi  
Machine Learning & Data Analysis
Focused on building interpretable models for real‑world datasets.
