# Loan Payment Data Cleaning Project

## Project Overview
This project focuses on cleaning a Loan Payment dataset using Python and Pandas. 
The dataset contained missing values (null values), which were identified, analyzed, and handled to create a clean dataset for further analysis.

## Dataset
The dataset used in this project is a Loan Payment dataset containing customer loan and payment information with missing values.

## Data Cleaning Process

The following steps were performed during the data cleaning process:

1. Loaded the dataset using Pandas.
2. Checked dataset information and null values.
3. Calculated percentage of missing values (approximately 7%).
4. Visualized missing values using a heatmap.
5. Dropped one column that contained a large number of null values (around 300 missing values).
6. Visualized missing values again using heatmap.
7. Removed remaining null values by dropping rows using dropna().
8. Final dataset contained no missing values and was ready for analysis.

## Libraries Used
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Files
- data-cleaning-project.ipynb → Jupyter Notebook with data cleaning steps
- loan_dataset.csv → Raw dataset
- CleanedData.csv → Final cleaned dataset (no null values)
- README.md → Project documentation

## Conclusion
After handling missing values by dropping unnecessary columns and removing rows with null values, the dataset was successfully cleaned and prepared for further data analysis or machine learning.

## Author
Himani Sharma