# Movie Rating Prediction with Python

## Project Overview

This project predicts IMDb movie ratings using machine learning based on features such as release year, duration, genre, director, and cast information. The goal is to analyze factors influencing movie ratings and build a regression model for rating prediction.

## Dataset

* Dataset: IMDb Movies India
* Records: 5,659 movies
* Target Variable: Rating

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Scikit-learn

## Project Workflow

1. Data Cleaning and Preprocessing
2. Handling Missing Values
3. Feature Engineering
4. Exploratory Data Analysis (EDA)
5. Linear Regression Model Development
6. Model Evaluation

## Key Analysis

* Analyzed movie distribution across years.
* Examined rating trends by genre and release year.
* Studied rating distribution patterns.
* Created average rating features for genres, directors, and actors.

## Feature Engineering

Generated new predictive features:

* Genre Mean Rating
* Director Mean Rating
* Actor 1 Mean Rating
* Actor 2 Mean Rating
* Actor 3 Mean Rating

These features helped capture historical performance patterns of genres, directors, and actors.

## Model Performance

| Metric   | Score |
| -------- | ----- |
| MAE      | 0.497 |
| MSE      | 0.455 |
| R² Score | 0.760 |

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* Feature Engineering
* Data Visualization
* Regression Modeling
* Model Evaluation
* Python Programming

## Conclusion

The Linear Regression model achieved an R² Score of 0.76, indicating strong predictive performance. The project demonstrates how feature engineering and historical movie data can be used to estimate IMDb ratings effectively.
