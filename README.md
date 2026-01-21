### **Used Car Price Prediction Based on Age of Car**

This project demonstrates how to predict the price of a used car based on its age using Linear Regression. The workflow includes data loading, visualization, model training, parameter interpretation, and prediction.

**Project Overview**

Car prices typically decrease as the vehicle gets older. Using a simple linear regression model, this project analyzes the relationship between car age (in years) and car price, then predicts the price of a car of any given age.

**Dataset**

The project uses a CSV file named car_prices.csv containing:

| Column Name   | Description               |
| ------------- | ------------------------- |
| car_age_years | Age of the car in years   |
| price         | Market price of the used car |

Ensure the CSV file is placed in the same directory as the script.

**Libraries Used**

NumPy – numerical computations

Pandas – data loading and manipulation

Matplotlib – data visualization

Scikit-learn – linear regression model

**Steps Performed**

1. Import Libraries

All required Python libraries are imported to handle data, visualization, and modeling.

2. Load Dataset

The dataset is loaded and displayed using Pandas.

3. Visualize the Data

A scatter plot is created to observe how car price changes with age.

4. Prepare Data for Modeling

X → independent variable (car_age_years)

y → dependent variable (price)

X is reshaped into 2D format as required by Scikit-learn.

5. Train the Linear Regression Model

A Linear Regression model is created and trained using the dataset.

6. View Model Parameters

Intercept (b0): Estimated price of a brand-new car

Coefficient (b1): Price drop per additional year of age

7. Predict Price

Example: Predicting the price of a 4.5-year-old car.

8. Plot Regression Line

A regression line is drawn over the scatter plot to visualize the model fit.

**Output**

- Scatter plot of car age vs. price
- Regression line
- Model intercept and coefficient
- Predicted price for a given car age

**Conclusion**

This project successfully:

- Visualizes the relationship between car age and price
- Trains a linear regression model
- Computes model parameters
- Predicts car prices based on age

It serves as a simple and effective introduction to machine learning regression techniques.
