# 📊 NFL Win Prediction Using Linear Regression

This project applies sports analytics to build a linear regression model that predicts NFL team wins based on offensive and defensive performance. Using `nflverse` data from the 2018–2023 regular seasons, we explore how total points scored and allowed correlate with total wins.

---

![Actual vs. Predicted Wins Scatter](images/actual_vs_predicted.png)
*Actual vs Predicted Wins (2018–2023)*

## 🏈 Overview

As the sports industry embraces data-driven decision making, understanding the statistical drivers of success is crucial. Our model uses two simple yet powerful predictors:

- **Total Points Scored**
- **Total Points Allowed**

We found that scoring contributes slightly more to wins than defense, with every ~35 points scored adding a win and every ~40 points allowed costing a win.

---

![2023 Team Win Comparison](images/2023_win_comparison.png)
*Actual vs. Predicted Wins by Team (2023)*

## 📈 Key Results

- **Adjusted R²**: 0.79 — the model explains 79% of the variance in wins.
- **Standard Error**: ±1.38 wins on average.
- **Coefficients**:
  - Points Scored: +0.029
  - Points Allowed: –0.025

This allows for mid-season benchmarking, post-season review, and even pre-season forecasting.

## 🧪 Sample Insights

- **Baltimore** underperformed relative to model expectations.
- **Washington** overperformed—highlighting how game-to-game variability and external factors (e.g., weather, officiating, injuries) affect outcomes.

We also tested hypothetical team profiles to demonstrate how organizations might forecast expected wins based on expected points for/against.

## 🛠️ Tools Used

- **R**
- `nflverse`, `tidyverse`, `ggplot2`, `knitr`

## 📁 Files

- `nfl_win_prediction.Rmd` – Full code and analysis.
- `Advanced Business Applications - NFL.docx` – Final written report.

---
