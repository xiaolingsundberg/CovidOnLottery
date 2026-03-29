# COVID on Lottery

Analysis of the relationship between the COVID period and lottery revenues using OLS regression, model comparison, and post-estimation inference in Python.

## Project Overview

This project builds and compares three candidate regression models to study how lottery revenues changed between the pre-COVID and COVID periods. The analysis focuses on:

- changes in predicted mean revenue across periods
- changes in the marginal effect of lagged jackpot amount
- changes in the marginal effect of unemployment rate

The final model is selected using standard model comparison metrics and then interpreted through post-estimation inference.

## Repository Structure

```text
.
├── covid_on_lottery.ipynb      # main Python analysis notebook
├── powerball_revenues.do       # earlier Stata analysis file
└── README.md
