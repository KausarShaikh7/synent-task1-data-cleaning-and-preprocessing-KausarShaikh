# synent-task1-data-cleaning-and-preprocessing-KausarShaikh
Data cleaning and preprocessing of the Titanic dataset using Python and Pandas, including missing value handling, duplicate removal, data type conversion, and column renaming.

# Task 1: Data Cleaning & Preprocessing

## Problem Statement

The objective of this task is to clean and preprocess the raw Titanic dataset so that it can be used effectively for further analysis. The preprocessing includes handling missing values, removing duplicate records, converting appropriate data types, and renaming selected columns.

## Dataset Details

- **Dataset:** Titanic Dataset
- **Source:** Kaggle
- **File:** `Titanic.csv`
- **Domain:** Passenger and survival information

The dataset contains information about Titanic passengers, including passenger class, name, gender, age, ticket details, fare, cabin, embarkation point, and survival status.

## Approach

The following steps were performed using Python and Pandas:

1. Loaded the Titanic dataset and examined its shape, structure, and missing values.
2. Handled missing values in the `Age` column using the median.
3. Handled missing values in the `Embarked` column using the mode.
4. Checked missing values in the `Cabin` column and removed it due to excessive missing values.
5. Verified the missing values after cleaning.
6. Removed duplicate records from the dataset.
7. Converted `Pclass`, `Sex`, and `Embarked` columns to categorical data types.
8. Renamed selected columns to make them more readable and descriptive.
9. Saved the cleaned dataset as `Titanic_Cleaned.csv`.

## Output

The cleaned dataset was successfully generated after preprocessing and saved as `Titanic_Cleaned.csv`.

The final dataset is ready for further analysis after handling missing values, removing duplicate records, converting selected data types, and improving column names.

## Tools & Technologies

- Python
- Pandas
- Jupyter Notebook

## Files

- `Titanic.csv` – Original Titanic dataset
- `Task_1_internship.ipynb` – Jupyter Notebook containing the complete preprocessing process
- `Titanic_Cleaned.csv` – Cleaned and preprocessed dataset
