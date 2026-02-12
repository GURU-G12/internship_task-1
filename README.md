Task 1: Data Cleaning & Preprocessing – Summary

The raw dataset was cleaned and prepared using Python (Pandas) to ensure data quality and consistency for further analysis. The following steps were performed:

Missing Value Handling

Identified missing values using df.isnull().sum().

Filled missing values in categorical columns such as Director, Cast, and Country with "Unknown".

Converted the Date-Added column to datetime format and removed rows with invalid or missing dates.

Filled missing values in Rating and Duration using the mode (most frequent value).

Duplicate Removal

Checked for duplicate records using df.duplicated().sum().

Removed duplicate rows using drop_duplicates() to ensure data uniqueness.

Column Name Standardization

Cleaned column headers by removing extra spaces and formatting them consistently.

Text Standardization

Standardized categorical text columns by converting values to consistent case (lowercase/uppercase) and removing extra spaces.

Data Type Correction

Converted Release-Year to integer type.

Converted Date-Added to datetime format for proper date handling.

Final Validation

Verified that no missing values remained.

Confirmed correct data types and dataset shape.

Exporting Cleaned Data

Saved the cleaned dataset as cleaned_dataset.csv for further analysis.
