# Data-Analysis-Project-Fraud-Detection
#Stepwise Data Cleaning Process (Pandas) for Fraud Detection
Step 1: Load the Dataset
  Import Pandas & load the CSV file
  Check data types and missing values
Step 2: Handle Missing Values
  Fill missing numerical values with median/mean
  Fill missing categorical values with "Unknown"
Step 3: Convert Data Types
  Convert Timestamp to datetime format
  Convert categorical columns to category type
  Convert binary flags to integer
Step 4: Feature Engineering
  Extract hour, weekday, and weekend flag from timestamp
  Create risk-based flags (High Amount, High Frequency, etc.)
Step 5: Handle Outliers (Using IQR Method)
  Remove extreme outliers in Transaction_Amount, Account_Balance, and Transaction_Distance
Step 6: Final Cleanup & Save Processed Data
  Drop unnecessary columns
  Save the cleaned dataset for Power BI
