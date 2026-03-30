# COVID on Lottery

Analysis of the relationship between the COVID period and lottery revenues using OLS regression, model comparison, and post-estimation inference in Python.

## Project Overview

This project builds and compares regression models to study how lottery revenues changed between the pre-COVID and COVID periods.

The current analyses focus on:

- Florida PowerBall revenues
- Florida MegaMillions revenues

The analysis examines:

- changes in predicted mean revenue across periods
- changes in the marginal effect of lagged jackpot amount
- changes in the marginal effect of unemployment rate

The final model is selected using standard model comparison metrics and then interpreted through post-estimation inference.

## Repository Structure

```text
.
├── .gitignore
├── README.md
├── powerball_revenues_florida.ipynb
└── megamillion_revenues_florida.ipynb
