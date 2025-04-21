# Task 1 : Data Cleaning and Pre-Processing
**Objective: Clean and prepare a raw dataset (with nulls, duplicates, inconsistent formats).**
1) Imported Libraries like numpy and pandas using the import function.
2) Loaded the CSV file using pandas to analyze the structure and content.
3) Described the dataset usind describe() function.
4) Identified the null values using the isnull() function in the dataset.
5) Filled the missing values using different methods like fillna(0),fillna(method="ffill"),fillna(method="bbill") and mean.
6) Removed the null values using the drop_na() function.
7) Removed duplicate rows using drop_duplicates().
8) Standardize text values such as gender, country names, State, Month, etc. using the Label Encoder.
9) Converted the date column to a consistent type '%y/%m/%d'.
10) Renamed the column names in the dataset to be clean and uniform. By using strip(),lower() and replace() functions.
11) Checked the Datatypes of each column using the info() function.
12) Fixed the Date datatype from object to datetime using the to_datetime() function.
13) Finally, after performing all the tasks converted dataframe into csv file using the df.to_csv() function.

**---------Thank You---------**
