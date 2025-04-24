# CFS Analysis

This project analyzes 911 Calls for Service (CFS) patterns in San Antonio using public datasets and linear regression modeling.

It explores the relationship between socioeconomic variables (such as unemployment and education) and the volume of police call activity, with the goal of identifying underlying community needs and service gaps.

## Project Contents

- `index.html` — Interactive HTML version of the Jupyter Notebook (rendered via GitHub Pages)
- `911_Call_Patterns_Analysis_Eduardo_Medina.ipynb` — Full notebook with data loading, preprocessing, and regression modeling
- `Data_Sets/` — Raw datasets including SAPD Calls for Service (tracked with Git LFS)

## Key Features

- Ordinary Least Squares (OLS) regression to examine predictors of call volume
- Data cleaning, feature engineering, and correlation analysis
- Visualizations using Seaborn and Matplotlib
- Analysis scaled by working-age population (WAP)

## View the Report

View the rendered notebook in your browser:  
https://eduardomedina0.github.io/cfs_analysis/

## Technologies Used

- Python (Pandas, NumPy, Seaborn, Matplotlib, Statsmodels)
- Jupyter Notebook
- Git and Git LFS
- GitHub Pages

## Notes

- The file `SAPD_Calls_for_Service.csv` is tracked using Git LFS due to its large size (approximately 437 MB).
- All analysis is intended for exploratory and academic purposes only.
