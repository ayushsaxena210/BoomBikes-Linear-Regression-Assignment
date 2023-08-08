# BoomBikes-Linear-Regression-Assignment

# Bike Sharing Demand Prediction

## Problem Statement

In the wake of the ongoing Covid-19 pandemic, BoomBikes, a US-based bike-sharing provider, has experienced a decline in revenue. To revitalize their business post-lockdown and economic recovery, BoomBikes aims to comprehend the demand for shared bikes and devise a strategic plan. The goal is to identify the key factors driving bike rental demand and develop insights to cater to the market's needs effectively.

## Task Performed

In this repository, we have conducted a comprehensive analysis and prediction of bike rental demand. The process involved the following tasks:

### Data Preparation

We handled categorical variables appropriately and created dummy variables when applicable.

### Model Building

- Calculated R-squared and adjusted R-squared to assess the model's goodness of fit.
- Calculated Variance Inflation Factors (VIFs) to identify multicollinearity issues among predictors.
- Conducted residual analysis on the training data, including plotting histograms of error terms and evaluating the spread of residuals around zero.

### Model Evaluation

Plotted y_test against y_pred to gain insights into the spread and performance of the model.

## Business Insights

Through our analysis, we derived significant business insights:

- Bike rentals are more popular on weekdays, specifically Tuesday (3), Wednesday (4), and Friday (6).
- Bike rentals are more frequent during certain seasons, notably summer (2) and fall (3).
- Increased bike rentals are observed during specific weather conditions (1: Clear, Few clouds, Partly cloudy).
- Bike rentals exhibited higher numbers in the year 2019 (1) compared to 2018 (0).

The top three features contributing significantly to explaining bike rental demand are:

1. `temp` (temperature): Higher temperatures positively impact bike rentals.
2. `yr` (year): Bike rentals have increased over the years.
3. `Light_Snow&Rain`: The presence of light snow or rain negatively affects bike rentals.

These insights provide BoomBikes with actionable strategies to enhance their bike-sharing services and meet customer demand effectively.

---
*Note: The analysis was conducted using a Jupyter Notebook included in this repository.*
