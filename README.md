# Implementing Linear Regression
A machine learning project that uses Linear Regression to predict house prices based on square footage, number of bedrooms, and bathrooms. 
This project demonstrates the implementation of Linear Regression to predict house prices based on three features:
Square Footage (Area) – the size of the house
Number of Bedrooms
Number of Bathrooms
Linear Regression is one of the most fundamental Supervised Machine Learning techniques. It finds the best-fit line that describes the relationship between input features (independent variables) and the target (dependent variable: house price).

Workflow of the Project:
The workflow of this project follows the standard machine learning pipeline:

Dataset Preparation:
Used a dataset of 200 housing records (house_prices_simulated.csv)
Features: area, bedrooms, bathrooms
Target: price

Data Preprocessing:
Loaded data with pandas
Handled missing values
Selected relevant features and target variable

Model Training:
Split the dataset into training (80%) and testing (20%) sets
Trained a Linear Regression model using scikit-learn

Model Evaluation:
Calculated Mean Squared Error (MSE)
Calculated R² Score (Coefficient of Determination)
R² score of 0.91 → model explains 91% of variance in house prices

Visualization:
Compared Actual vs Predicted Prices using a scatter plot
Verified the strength of the model visually

Regression Equation:
The trained regression model produced the following equation:

Price = 1995.41 + 251.99 × (Area) + 4000.04 × (Bedrooms) + 9454.82 × (Bathrooms)

Area: Each additional square foot increases price by ≈ $252
Bedrooms: Each additional bedroom increases price by ≈ $4000
Bathrooms: Each additional bathroom increases price by ≈ $9455
