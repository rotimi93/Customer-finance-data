# Customer_finance_data

📂 Dataset: customer_finance_data.csv
This dataset contains financial information of 1,000 fictional customers. Each record includes personal details (like gender, marital and employment status), financial data (income, expenses, savings), account type, and loan approval status. You’ll explore the data using foundational tools in Pandas.

🎯 Objective
The goal is to practice data analysis skills using Pandas by applying filtering, indexing, grouping, value counting, and basic visualization—using a real-world inspired finance dataset.

📌 Tasks Overview
🔍 1. Load and Preview the Data
Load the CSV file into a DataFrame.

View the first 5 and last 5 rows.

Display column names, shape, and data types of the dataset.

🔎 2. Filtering and Indexing
Filter customers who are Married and whose Loan_Approved status is "Yes".

Use .iloc[] to display the Customer_ID, Monthly_Income, and Loan_Approved of the first 10 customers.

📊 3. Descriptive Statistics
Calculate the average Monthly_Income.

Use .describe() to generate summary statistics for all numeric columns.

Find the minimum and maximum value of Monthly_Savings.

🔢 4. Value Counts and Sorting
Use .value_counts() to count occurrences of each Employment_Status.

Identify the most common Account_Type.

Sort the entire dataset by Monthly_Income in descending order.

📈 5. Grouping and Aggregation
Group by Gender and find the average Monthly_Savings.

Group by Marital_Status and count how many customers have Loan_Approved = 'Yes'.

Group by both Gender and Employment_Status, then compute the average Monthly_Expenses.

📆 6. Date-Based Insights
Convert the Join_Date column to datetime format.

How many customers joined in 2023?

What is the average income of customers who joined after January 1, 2024?

✅ 7. Boolean Filtering
Select customers with Monthly_Income > ₦300,000 and Monthly_Savings > ₦100,000.

Use .isin() to find customers whose Employment_Status is either "Unemployed" or "Self-employed".

🧠 8. Bonus Challenge
Create a new column: Income_to_Expense_Ratio = Monthly_Income / Monthly_Expenses.

Use .query() to find customers with a savings rate > 50% of their income (i.e. Monthly_Savings / Monthly_Income > 0.5).
