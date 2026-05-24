# House Price Prediction using Linear Regression

This repository contains the solution for **Task 01**, which focuses on implementing a supervised machine learning algorithm using **Multivariate Linear Regression** to predict house prices based on physical and structural features.

## 📌 Project Overview
Predicting real estate prices is a classic regression problem. In this project, we implement a linear regression model that learns the relationship between independent variables (features) and the dependent variable (target price).

The model utilizes three key features for prediction:
1. **Square Footage**: The total living area of the house.
2. **Number of Bedrooms**: Total count of bedrooms.
3. **Number of Bathrooms**: Total count of bathrooms.

## 📊 Methodology

The project follows a standard predictive modeling pipeline:
1. **Data Preparation**: Loading features ($X$) and the target variable ($y$).
2. **Train/Test Split**: Dividing the dataset into an 80% training set (to train the model) and a 20% testing set (to evaluate performance on unseen data).
3. **Model Training**: Fitting the `LinearRegression` model from `scikit-learn` to calculate optimal weights (coefficients) for each feature.
4. **Evaluation**: Assessing accuracy using **Root Mean Squared Error (RMSE)** and the **$R^2$ Score** (Coefficient of Determination).

## 🚀 Getting Started

### Prerequisites
Make sure you have Python installed along with the required libraries. You can install all dependencies using `pip`:

```bash
pip install pandas numpy scikit-learn
