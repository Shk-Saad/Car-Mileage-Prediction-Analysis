# Car-Mileage-Prediction-Analysis
Analyze a Car Mileage

This project aims to analyze a car mileage dataset to understand the relationship between horsepower and speed in kilometers per hour (KMPH) and build predictive models using linear regression and polynomial regression techniques.

The dataset is loaded using the pandas library, and unnecessary columns are dropped to clean the data. Correlation analysis is performed to explore the relationships between different variables.

First, a simple linear regression model is built using horsepower as the predictor and speed as the target variable. The model is trained on the entire dataset, and the coefficients of the linear equation (slope and intercept) are computed.

Next, a scatter plot is created to visualize the relationship between horsepower and speed, with the regression line overlayed.

Then, polynomial regression is applied to capture non-linear relationships between horsepower and speed. A quadratic polynomial transformation is performed on the horsepower feature, and a new regression model is trained on the transformed features.

Another scatter plot is created to visualize the polynomial regression model's predictions, showing the curve that best fits the data points.
