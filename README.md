# Bank_Loan_Analysis_Dashboard
Project Objective
The Bank Loan Analysis Dashboard project aims to provide comprehensive insights into the bank's loan portfolio. By integrating data from MS SQL Server, Excel, and Power BI, this project helps in monitoring key performance indicators (KPIs), understanding trends, and analyzing loan data to make data-driven decisions. The dashboards are designed to assist in assessing the bank's lending performance, borrower profiles, and the health of the loan portfolio.

# Dataset Source
The dataset used in this project is sourced from a CSV file that contains detailed loan application data. It is imported into MS SQL Server for querying and analysis. The columns included in the dataset are as follows:

id: Unique identifier for each loan record.
address_state: State where the borrower is located.
application_type: Type of loan application (e.g., individual, joint).
emp_length: Length of time the borrower has been employed.
emp_title: Title or position of the borrower at their place of employment.
grade: Credit grade assigned to the loan.
home_ownership: Status of the borrower’s home ownership (e.g., own, mortgage, rent).
issue_date: Date when the loan was issued.
last_credit_pull_date: Date when the borrower’s credit was last pulled.
last_payment_date: Date of the borrower’s last payment.
loan_status: Current status of the loan (e.g., fully paid, charged off).
next_payment_date: Date of the next payment due.
member_id: Unique identifier for the borrower.
purpose: Purpose of the loan (e.g., debt consolidation, home improvement).
sub_grade: More granular credit grade assigned to the loan.
term: Length of the loan (e.g., 36 months, 60 months).
verification_status: Status of the borrower’s income verification.
annual_income: Borrower’s annual income.
dti: Debt-to-income ratio of the borrower.
installment: Monthly installment payment for the loan.
int_rate: Interest rate charged on the loan.
loan_amount: Total loan amount.
total_acc: Total number of credit accounts the borrower has.
total_payment: Total payment made by the borrower.

# Steps
1. Data Import: Imported CSV data into MS SQL Server and created a database for storing and managing the data.
2. Query Writing: Developed SQL queries to retrieve, filter, and aggregate data for analysis.
3. Business Problem Solving: Fired SQL queries to solve business problems, analyzing loan performance, trends, and KPIs.
4. Excel and Power BI Comparison: Compared the results from SQL queries with data in Power BI and Excel for validation and cross-checking.
5. Dashboard Creation: Connected Power BI to MS SQL Server and created three distinct dashboards:

1.Bank Loan Report | Summary
2.Bank Loan Report | Overview
3.Bank Loan Report | Detail

## Dashboards
# Dashboard 1: Bank Loan Report | Summary
Key Performance Indicators (KPIs):
Total Loan Applications: Displays the total number of loan applications, along with Month-to-Date (MTD) and Month-over-Month (MoM) comparisons. 
Total Funded Amount: Visualizes the total loan amount funded, with MTD and MoM analysis.
Total Amount Received: Tracks loan repayments and their changes over time (MTD and MoM).
Average Interest Rate: Shows the average interest rate across all loans, MTD, and MoM variations.
Average Debt-to-Income Ratio (DTI): Displays the average DTI for borrowers, helping assess their financial health.
Good vs. Bad Loan Metrics:
Good and Bad Loan Applications, Funded Amount, and Total Received Amount
Good and Bad Loan Percentages
Loan Status Grid View:
Provides an overview of metrics categorized by loan status, including loan applications, funded amounts, received amounts, MTD analysis, interest rates, and DTI.

# Dashboard 2: Bank Loan Report | Overview
Charts:
Monthly Trends by Issue Date (Line Chart): Identifies seasonality and long-term trends in lending.
Regional Analysis by State (Filled Map): Displays regional lending activity and identifies disparities.
Loan Term Analysis (Donut Chart): Shows loan distribution by term length.
Employee Length Analysis (Bar Chart): Visualizes lending data across different employment lengths, highlighting its impact on loan applications.
Loan Purpose Breakdown (Bar Chart): Breaks down loan metrics based on the stated purposes.
Home Ownership Analysis (Tree Map): Displays the relationship between home ownership and loan metrics.
Metrics:
Total Loan Applications, Total Funded Amount, Total Amount Received

# Dashboard 3: Bank Loan Report | Details

To provide a comprehensive and user-friendly view of all critical loan data, including borrower profiles and loan performance metrics.
Acts as a one-stop solution for detailed loan analysis and performance monitoring.

# Insights :


# Action Items: 
1. Regularly update the loan data in the MS SQL database for the most current insights.
2. Continuously monitor the KPIs and trends to assess lending performance and adjust strategies accordingly.
3. Use the insights from the dashboards to make data-driven decisions for improving loan processes, targeting high-performing regions, and evaluating borrower profiles.

