# Car-price-prediction
This project applies Machine Learning techniques to predict car prices based on their characteristics (make, fuel type, body style, engine size, horsepower, etc.).

We compare multiple regression models such as:

Linear Regression

Random Forest Regressor

XGBoost Regressor

The goal is to evaluate which model gives the most accurate predictions and visualize the results.

     Technologies Used

Python 3.x

Pandas

NumPy

Scikit-learn

Matplotlib / Seaborn

XGBoost

    Workflow

Data Loading & Cleaning

Handle missing values

Encode categorical features (One Hot Encoding)

Normalize numerical features (StandardScaler / MinMaxScaler)

Exploratory Data Analysis (EDA)

Visualize distributions

Correlation analysis

Scatter plots of price vs features

Model Training

Train Linear Regression, Random Forest, and XGBoost models

Compare performance using evaluation metrics

Evaluation Metrics

RMSE (Root Mean Squared Error)

MAE (Mean Absolute Error)

R² (Coefficient of Determination)

Visualization

Plot predicted vs actual prices

Compare models side by side

    📈 Results

The baseline Linear Regression model provides a simple benchmark.

Random Forest and XGBoost generally give better performance (lower RMSE, higher R²).

Visualizations show predictions close to the ideal diagonal line (y = x).


