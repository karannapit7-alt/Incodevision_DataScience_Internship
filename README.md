# Incodevision_DataScience_Internship

#Data Cleaning and Preprocessing Pipeline
  This project was completed as part of my Data Science Internship at @IncodeVision.
#Project Overview
  The goal of this task was to clean a raw "Student Internship Dataset" that contained several inconsistencies, missing values, and duplicate records. Clean data is the foundation of any successful data science       project.
#Tech Stack
  Language: Python
  Libraries: Pandas, NumPy
  Tool: Jupyter Notebook
#Key Steps Performed
  1. Identifying Missing Values: Used .isnull().sum() to locate gaps in the data.
  2. Data Imputation: Filled missing 'City' entries with "Not Disclosed" and 'Department' with "General".
  3. Duplicate Removal: Identified and removed duplicate rows to maintain data integrity.
  4. Standardization: Converted text data to a consistent format and cleaned column headers.
#File Structure
  1_Internship_Data_Cleaning.ipynb: The main Python script with the cleaning logic.
  1_internship_data_csv.csv: The raw input dataset.
  Cleaned_Data_Final.csv: The final processed and clean dataset.
