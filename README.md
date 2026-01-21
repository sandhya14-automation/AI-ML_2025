# **Machine Learning with Python: Linear Regression (One Variable)**

This document provides clear, beginner‑friendly explanations for two linear regression projects:

- **Used Car Price Prediction based on car age**

- **Student Score Prediction based on hours studied**

Both projects follow the same ML workflow: data loading, visualization, model training, parameter interpretation, prediction, and regression line plotting.

### **1. Used Car Price Prediction**

Predict the price of a used car based on its age using Linear Regression.

**Project Overview**

Car prices typically decrease as the vehicle gets older. This project models the relationship between car age (years) and car price, then predicts the price for any given age.

**Dataset**

The dataset car_prices.csv contains:

| Column        | Description               |
| ------------- | ------------------------- |
| car_age_years | Age of the car in years   |
| price         | Market price of the used car |

**Steps Performed**

1. Import Libraries

NumPy, Pandas, Matplotlib, and Scikit‑learn.

2. Load Dataset

Read the CSV file and display the data.

3. Visualize Data

Scatter plot of car age vs. price to observe the trend.

4. Prepare Data

X = car_age_years (independent variable)

y = price (dependent variable)

X reshaped into 2D format.

5. Train Model

A Linear Regression model is created and trained.

6. Model Parameters

Intercept (b0): price when age = 0

Coefficient (b1): price drop per year

7. Predict Price

Example: predict price for a 4.5‑year‑old car.

8. Plot Regression Line

Scatter plot + regression line overlay.

**Output**

- Scatter plot
- Regression line
- Model parameters
- Predicted price

### **2. Student Score Prediction**

Predict a student's test score based on hours studied using Linear Regression.

**Problem Statement**

Build a machine learning model that predicts student test scores from hours studied.

**Dataset**

The dataset study_scores.csv contains:

| Column        | Description           |
| ------------- | --------------------- |
| hours_studied | Number of study hours |
| score         | Test score achieved   |

**Steps Performed**

1. Import Libraries

Pandas, Matplotlib, and Scikit‑learn.

2. Load Dataset

Read and display the dataset.

3. Visualize Data

Scatter plot of hours studied vs. score to understand the relationship.

4. Prepare Data

x = hours_studied (independent variable)

y = score (dependent variable)

x reshaped into 2D format.

5. Train Model

Linear Regression model is created and trained.

6. Model Parameters

Intercept (b0): base score when hours = 0

Coefficient (b1): score increase per hour studied

7. Predict Score

Example: predict score for a student who studied 7.2 hours.

8. Plot Regression Line

Scatter plot + regression line overlay.

**Output**

- Scatter plot
- Regression line
- Model parameters
- Predicted score

**Conclusion**

Both projects demonstrate how simple linear regression can:

- Visualize relationships between variables
- Train predictive models
- Interpret intercepts and slopes
Make real‑world predictions

These examples form a strong foundation for more advanced machine learning techniques.
