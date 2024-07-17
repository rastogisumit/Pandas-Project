

# Financial Data Analysis with Pandas

This repository contains Python scripts for analyzing financial data using Pandas library. The scripts focus on tasks related to customer spending, repayment, profitability, and interest calculations. Below is a brief overview of each task implemented:

## Tasks Overview

1. **Task 1: Monthly spend of each customer**
   - Calculates monthly spending of each customer based on provided spend data.

2. **Task 2: Monthly repayment of each customer**
   - Computes monthly repayment amounts made by each customer using repayment data.

3. **Task 3: Highest paying 10 customers**
   - Identifies the top 10 customers who made the highest total repayments.

4. **Task 4: People in which segment are spending more money**
   - Determines which customer segment has the highest total spend based on merged data.

5. **Task 5: Which age group is spending more money**
   - Analyzes spending patterns across different age groups to identify the group with the highest spending.

6. **Task 6: Which is the most profitable segment**
   - Calculates profitability for each customer segment by comparing spending and repayment data.

7. **Task 7: In which category the customers are spending more money**
   - Identifies the spending trends across different spending categories.

8. **Task 8: Impose an interest rate of 2.9% for each customer for any due amount**
   - Calculates and applies an interest rate on overdue amounts for each customer.

9. **Task 9: Monthly profit for the bank**
   - Computes monthly profit for the bank considering spending, repayment, and interest earned.

## Data Source
- The analysis uses Excel files (`task.xls`) containing multiple sheets (`Customer Acquisition`, `Spend`, `Repayment`) which are loaded using Pandas.

## Usage
- Ensure Python environment with Pandas is set up.
- Modify `file_path` variable in scripts to point to the correct location of `task.xls`.
- Run each script (`task1.py` to `task9.py`) to execute individual tasks.

## Dependencies
- Python 3.x
- Pandas

