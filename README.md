# DEBUGGIN A SALES DATA WORKFLOW

## Project Description
In this project, you will work to fix the start of a sales workflow. You will need to read an already-written code, understand where the problem is, and come up with a solution so things will run smoothly again.

## INSTRUCTIONS
1.-Run the load_and_check() function first. Look for any error messages in the output - these will point you to what needs fixing. You should aim for exactly two success messages: "Data loaded successfully" and "Data integrity check was successful!"

2.-Review the load_and_check() function code, paying special attention to the two integrity checks:
    The first check validates the column count.
    The second check validates data integrity based on Condition_1 (Total values) and Condition_2 (Tax calculations at 5%)
Your task is to identify and fix issues within the load_and_check() function itself, not by modifying the raw sales.csv dataset. You are permitted and expected to correct any columns within the function. Ensure the function only returns two success messages when completed.

## Key Features
- Connect to a .csv data file
- Extract and transform sales data
- Data manipulations with pandas

## Files
- 'Debugging-a-sales-data-workflow.ipynb' → main Jupyter notebook with the code and analysis
- README.md file
- .csv file called "sales", related to this project

## Author
Argenis Enrique Velasquez Duarte
