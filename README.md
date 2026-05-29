# Data-Cleaning-Preprocessing

## Objective

The objective of this task was to clean and prepare a raw dataset for analysis by handling missing values, removing duplicates, standardizing formats, and correcting data types.

## Dataset Used

Customer Personality Analysis Dataset (marketing_campaign.csv)

## Data Cleaning Steps Performed

1. Loaded the dataset using Pandas.
2. Inspected dataset structure using `df.info()`.
3. Identified missing values using `df.isnull().sum()`.
4. Filled missing values in the Income column using the median value.
5. Checked and removed duplicate records using `drop_duplicates()`.
6. Standardized column names by converting them to lowercase.
7. Verified data types and dataset quality.
8. Exported the cleaned dataset as `marketing_campaign_cleaned.csv`.

## Tools Used

* Python
* Pandas
* Jupyter Notebook

## Output

A cleaned and structured dataset ready for analysis and visualization.
