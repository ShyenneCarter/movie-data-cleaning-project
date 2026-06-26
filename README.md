Movie Data Cleaning Project
Overview

This project focuses on cleaning and preparing a movie dataset containing 9,837 records. The original data included inconsistent formats, missing values, incorrect data types, and unstandardized text fields. The goal was to transform the raw dataset into a clean, reliable version suitable for analysis, visualization, or further modeling.

The work reflects real-world data cleaning practices and demonstrates the ability to handle imperfect data systematically and efficiently.

Data Cleaning Steps

1. Data Type Corrections
Converted Release_Date from object to datetime.

Converted Vote_Count and Vote_Average from object to numeric.

Ensured Popularity remained numeric.

2. Handling Missing Values
   
Filled missing text fields (Title, Overview, Genre, Original_Language, Poster_Url) with "Unknown".

Filled missing numeric fields (Popularity, Vote_Count, Vote_Average) with 0.

3. Text Standardization
Trimmed whitespace across all string columns.

Standardized capitalization for titles and genres.

Lowercased language codes.

Cleaned and normalized text fields for consistency.

4. Outlier and Error Removal
Removed invalid ratings outside the 0–10 range.

Removed negative values in popularity or vote counts.

Ensured all rows were logically valid.

5. Final Validation
Confirmed zero duplicate rows.

Confirmed zero missing values after cleaning.

Verified correct data types across all columns.

Ensured the dataset maintained its full shape (9,837 rows × 9 columns).

Files Included
cleaned_movies.csv — final cleaned dataset.

movie_cleaning_notebook.ipynb — Kaggle notebook containing the full cleaning process.

raw_dataset.zip — original uncleaned dataset (optional).

Tools Used
Python

Pandas

Kaggle Notebooks

Summary
This project demonstrates the ability to work with raw, messy data and transform it into a structured, analysis-ready dataset. It highlights skills in data wrangling, cleaning, validation, and documentation—core responsibilities in data analytics and data science workflows.
