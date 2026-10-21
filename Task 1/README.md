# Adult Income Dataset — Data Cleaning and Preprocessing

## Project Overview
This project focuses on cleaning and preprocessing the publicly available Adult Income Dataset using Python and Pandas.

## Objectives
- Identify and handle missing values.
- Remove duplicate records.
- Check and correct data types.
- Inspect potential outliers using boxplots.
- Document data-cleaning assumptions.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Cleaning Steps
1. Loaded and inspected the dataset.
2. Checked missing values and duplicate records.
3. Removed extra spaces and converted `?` markers into missing values.
4. Imputed missing categorical values using the mode.
5. Removed exact duplicate rows.
6. Inspected numerical data using summary statistics and boxplots.
7. Exported the cleaned dataset to CSV.

## Results
- Original rows: 32,560
- Cleaned rows: 32,536
- Columns: 15
- Missing values after cleaning: 0
- Duplicate rows after cleaning: 0

## Files
- `Adult_Income_Data_Cleaning.ipynb` — Notebook containing the code and results.
- `cleaned_adult_income.csv` — Cleaned dataset.

## Dataset Source
UCI Machine Learning Repository: https://archive.ics.uci.edu/dataset/2/adult

## Note
Potential outliers were inspected but not automatically removed. Missing-value imputation and duplicate removal were performed based on the assumptions documented in the notebook.