# Medical Insurance Cost Prediction Using Linear Regression

## Project Overview

This project focuses on predicting medical insurance charges using Linear Regression, a supervised machine learning algorithm. The goal is to analyze the factors affecting insurance costs and build a model to estimate individual medical insurance charges.

## Objectives

* Explore and understand the medical insurance dataset.
* Perform Exploratory Data Analysis (EDA).
* Clean and preprocess the data.
* Analyze relationships between features and insurance charges.
* Build and train a Linear Regression model.
* Evaluate model performance using regression metrics.

## Dataset

The project uses the Medical Cost Personal Dataset (`insurance.csv`), which contains information about individuals and their medical insurance charges.

### Features

| Feature  | Description                                 |
| -------- | ------------------------------------------- |
| age      | Age of the individual                       |
| sex      | Gender                                      |
| bmi      | Body Mass Index                             |
| children | Number of children covered by insurance     |
| smoker   | Smoking status                              |
| region   | Residential region                          |
| charges  | Medical insurance charges (target variable) |

## Technologies and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Workflow

### 1. Data Loading and Exploration

* Import the required libraries.
* Load the dataset using Pandas.
* Explore the dataset structure and dimensions.
* Inspect data types and descriptive statistics.
* Check for missing values and duplicates.

### 2. Exploratory Data Analysis (EDA)

* Analyze numerical and categorical features.
* Visualize feature distributions.
* Examine relationships between independent variables and insurance charges.
* Use statistical plots and a correlation heatmap to identify patterns.

### 3. Data Preprocessing

* Handle missing values and duplicate records, where applicable.
* Separate independent features and the target variable.
* Encode categorical variables.
* Split the dataset into training and testing sets.
* Apply feature scaling where appropriate.

### 4. Model Building

* Import Linear Regression from Scikit-learn.
* Train the model using the training dataset.
* Generate predictions using the testing dataset.

### 5. Model Evaluation

Evaluate the model using the following metrics:

* **MAE (Mean Absolute Error):** Measures the average absolute difference between actual and predicted values.
* **MSE (Mean Squared Error):** Measures the average squared prediction error.
* **RMSE (Root Mean Squared Error):** Measures the square root of the average squared error.
* **R² Score:** Measures how much of the variance in insurance charges is explained by the model.

## Results

The model's performance is assessed using MAE, MSE, RMSE, and R² Score on the test dataset.

Actual evaluation results can be added after executing the notebook.

## Conclusion

This project demonstrates the application of Linear Regression to a real-world regression problem. It covers the machine learning workflow, from data exploration and preprocessing to model training and evaluation.

## Future Improvements

* Compare Linear Regression with other regression algorithms.
* Perform feature engineering.
* Investigate nonlinear relationships between variables.
* Apply hyperparameter tuning to alternative models.
* Improve predictive performance through model comparison.

## Repository Structure

```text
insurance-cost-prediction-linear-regression/
│
├── Linear_Regression_Insurance_Prediction.ipynb
├── insurance.csv
└── README.md
```

## Author

**Soha Elzelaky**

## Topics

`machine-learning` `linear-regression` `python` `data-science` `exploratory-data-analysis` `scikit-learn` `regression` `insurance-cost-prediction`
