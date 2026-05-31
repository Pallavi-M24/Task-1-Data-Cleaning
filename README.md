# Mall Customers Data Cleaning Project

## Objective
To clean and preprocess the Mall Customers dataset by handling missing values, duplicate records, and invalid data.

## Dataset
The dataset contains customer information such as:
- CustomerID  
- Gender  
- Age  
- Annual Income (k$)  
- Spending Score (1-100)

## Steps Performed
- Loaded the dataset using pandas
- Checked dataset information
- Identified missing values
- Identified duplicate rows
- Filled missing values using mean
- Removed duplicate records
- Removed invalid values (negative age if present)

## Results
### Before Cleaning
- Missing values were present
- Duplicate rows existed

### After Cleaning
- No missing values
- No duplicate rows

## Tools Used
- Python
- Pandas
- Jupyter Notebook

## Output
Cleaned dataset saved as `Mall_Customers_Cleaned.csv`
