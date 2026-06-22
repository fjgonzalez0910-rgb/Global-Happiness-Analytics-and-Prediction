# 🌎 Global Happiness Analytics and Prediction

## Project Overview

This data science project analyzes the World Happiness Report dataset from 2015 to 2019 to identify the key socioeconomic factors that influence happiness levels around the world.

The project applies data cleaning, exploratory data analysis (EDA), visualization techniques, and machine learning regression models to predict the Happiness Score of different countries.

The objective is to understand how economic, social, and health indicators contribute to global happiness and evaluate different predictive modeling approaches.

---

## Dataset

Source: World Happiness Report Dataset - Kaggle

The dataset includes happiness indicators from countries worldwide between 2015 and 2019.

Main features analyzed:

- Country
- Year
- Happiness Score
- GDP per Capita
- Social Support
- Healthy Life Expectancy
- Freedom
- Trust / Government Corruption
- Generosity

---

## Project Workflow

### 1. Data Cleaning and Preprocessing

The dataset preparation included:

- Combining multiple yearly datasets
- Standardizing column names
- Handling missing values
- Checking duplicate records
- Reviewing data types

---

### 2. Exploratory Data Analysis (EDA)

The EDA process explored:

- Happiness Score distributions
- Global happiness trends over time
- Top-ranked countries
- Outlier analysis
- Feature relationships
- Correlation analysis

Visualizations were created to better understand patterns between socioeconomic indicators and happiness levels.

---

### 3. Machine Learning Models

Three regression techniques were developed and compared:

### Linear Regression
Used as a baseline model to predict Happiness Score.

### Polynomial Regression
Implemented to capture possible non-linear relationships.

### Ridge Regression
Applied L2 regularization to improve model generalization and reduce overfitting.

---

## Model Evaluation

Models were compared using:

- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score

Both single-variable and multiple-variable approaches were evaluated.

---

## Hyperparameter Optimization

GridSearchCV was used to tune the Ridge Regression alpha parameter.

The tuning process identified the optimal regularization strength to improve model performance.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook
- GitHub

---

## Key Insights

The analysis showed that:

- Economic indicators strongly influence happiness levels.
- Social Support and Health are important predictors.
- Multiple-variable regression models provide better predictions than single-variable models.
- Machine Learning can identify meaningful patterns in global well-being data.

---

## Author

Francisco Javier González Pérez

MBA - Data Science
