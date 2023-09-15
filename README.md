09/15/23

# Description
This Python script generates general completess metrics for any dataset. In order to execute properly, the data must be in CSV format and named "dataset.csv". Furthermore, the dataset.csv file will need to be in the same root directory as the completess_script.ipynb file. The script is programmed in a scalable way, therefore it will calculate metrics based on the number of columns and number of rows found in the CSV file.

## Tools
Libraries used:
- NumPy
- Pandas

# Methodology
The script will auto-generate a folder named "exports" in the root directory. In this folder you will find three files:
1. completeness_tabular_results - contains the following metrics:
    * Count of null values in each column
    * Count of non-null values
    * Percent of null values
    * Percent of present values
    * Count of distinct values found in each column
2. full_null_cols_list - contains the following metrics:
    * List of columns where all records are null
3. nonvarying_cols_list - contains the following metrics:
    * List of columns with unvarying values
    * The unvarying value found in each column

# Demonstration
A file named dataset.csv is included. This dataset is derived from the well-known iris flower dataset by Sir Ronald Aylmer Fisher. It includes extra custom columns that serve to demonstate the methodology.


