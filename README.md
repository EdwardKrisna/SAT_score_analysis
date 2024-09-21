# SAT Score Analysis Project

## Overview
This project analyzes factors influencing SAT scores across different regions in the United States. Using a dataset with educational and demographic information, we perform a multiple linear regression analysis to understand the relationships between various factors and SAT scores.

## Dataset
The dataset includes the following variables:
- region: Geographical region (categorical)
- csat: Mean composite SAT score (dependent variable)
- percent: Percentage of high school graduates taking the SAT
- expense: Per-pupil expenditures in primary and secondary education
- income: Median household income (in thousands of dollars)
- high: Percentage of adults with a high school diploma
- college: Percentage of adults with a college degree

## Analysis Performed
- Data preprocessing and encoding
- Correlation analysis
- Multiple linear regression
- Homoskedasticity testing
- Multicollinearity check
- Normality testing
- F-test for joint significance
- Feature importance visualization

## Files in this Repository
- `econometry_4.ipynb`: Jupyter notebook containing the Python code for the analysis
- `linreg1.dta`: The dataset used for the analysis
- `SAT Score Analysis.pdf`: Detailed interpretation and findings of the analysis

## Requirements
- Python 3.12.2
- Libraries: pandas, numpy, matplotlib, seaborn, statsmodels, scipy

## How to Run
1. Clone this repository
2. Install the required libraries: `pip install -r requirements.txt`
3. Open and run the `SAT_analysis.ipynb` notebook in Jupyter

## Note to Readers
For a comprehensive understanding of the analysis and interpretation of results, please read the 'SAT Score Analysis.pdf' file in this repository. This document provides in-depth insights into our findings, methodologies, and conclusions from the data analysis.
