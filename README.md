# COVID on Lottery

This repository studies the impact of the COVID period on U.S. lottery outcomes using Python. The analysis focuses on **PowerBall** and **MegaMillions**, with separate notebooks for **revenues** and **estimated ticket sales**.

## Project Goal

The main goal is to compare lottery performance **before COVID** and **during COVID**, and to examine how ticket sales or revenues respond to factors such as:

- COVID period
- lagged jackpot amount
- unemployment rate
- draw day effects

## Study Period

The analysis uses the following period split:

- **Pre-COVID:** May 2016 to March 3, 2020  
- **COVID period:** March 4, 2020 to March 2022

## Repository Structure

### Program
Contains the Jupyter notebooks used for data preparation, exploration, modeling, model comparison, and post-model inference.

- `powerball_revenue_florida.ipynb`
- `powerball_tickets_florida.ipynb`
- `powerball_tickets_texas.ipynb`
- `powerball_tickets_colorado.ipynb`
- `megamillions_revenue_florida.ipynb`
- `megamillions_tickets_florida.ipynb`
- `megamillions_tickets_texas.ipynb`
- `megamillions_tickets_colorado.ipynb`

### Data
Contains the source data files used in the notebooks.

## Methods

The workflow in each notebook generally includes:

1. Data loading and preparation  
2. Period creation (pre-COVID vs COVID)  
3. Exploratory data analysis  
   - summary statistics
   - histograms
   - scatter plots
   - boxplots
   - time-series plots
4. Outlier and skewness assessment  
5. Log transformation when appropriate  
6. Model estimation using OLS regression  
7. Model comparison using:
   - Adjusted R-squared
   - AIC
   - BIC
8. Post-model inference

## Ticket Sales

Ticket sales are estimated from prize winner counts and prize-winning probabilities, following the original project setup.

## Tools Used

- Python
- pandas
- numpy
- matplotlib
- statsmodels
- Jupyter Notebook

## Notes

- Revenue and ticket-sales analyses are organized in separate notebooks.
- Some final models are estimated on the **log scale** due to skewness and extreme values.
- Conclusions are reported separately for each game and state.

## Author

Xiaoling Sundberg
