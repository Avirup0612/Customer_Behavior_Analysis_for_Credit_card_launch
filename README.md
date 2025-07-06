
# Customer Behavior Analysis for Credit Card launch

## Introduction and Situation

**UnityStar Bank** is a legacy financial institution headquartered in Hyderabad. They want to introduce a new line of credit cards, aiming to broaden its product offerings and reach in the financial market.

We came to know about this through an internal link and approached UnityStar Bank with a proposal to implement this project. However, strategy director of the Bank, is skeptical and asked us to do a pilot project with the sample data before handing us the full project.


## Description of Datasets given by the company

*\*The Bank provided a sample dataset of 4000 customers across five cities on their online spend and other details as CSV files.
This description will give us the idea about the initial structure of the data*


**Column Description for dim_customers :**

- **customer_id :** This column represents the Unique ID assigned to each customer.
- **gender :** This column represents the gender of the customer. (Male, Female)
- **age_group :** This column categorizes the customer into different age groups. (21-24, 25-34, 35-45, 45+)
- **marital_status :** This column indicates the marital status of the customer (single, married).
- **city :** This column represents the city of residence for the customer. (Mumbai, Delhi-NCR, Chennai, Hyderabad, Bengaluru)
- **occupation :** This column denotes the occupation or profession of the customer. (Salaried IT Employees, Salaried Other Employees, Business Owners, Freelancers, Government Employees)
- **average_income :** This column indicates the monthly average income of the customer, in INR currency.


**Column Description for fact_spends :**

- **customer_id :** This column represents the Unique ID of each customer, linking to the dim_customer table.
- **month :** This column indicates the month in which the spending was recorded. (May, June, July, August, September, October)
- **category :** This column describes the category of spending (Entertainment, Apparel, Electronics, etc).
- **payment_type :** This column specifies the type of payment used by the customer (Debit Card, Credit Card, UPI, Net Banking).
- **spends :** This column shows the total amount spent by the customer in the specified month, category and payment_type.


## Our Task

- Prepare and Analyze the data of 4000 customers thoroughly.
- Create dashboard/report to display the KPIs.
- Generate insights after the proper analysis.
- Give recommendations to the bank manager for the successful launch of the credit card.

## Methodology used / Workflow

- We have leveraged Power Query to clean and pre-process the data thuroughly.
- We have leveraged "Measures", "Calculated Columns", "Parameters" and "Bookmarks" for the calculations and visual interactivity and add functionality to the report.
- We have used "Pie charts", "Column Charts", "Cards", "Bar Charts" and "Matrix" to visualize the report.
- After analysis we documented the insights and recommendations to a pdf file as a final result.

## Files

**Customer_Behaviour_Analysis_of_Bank.pbix :** This contains the main Power BI report where the visualization has been done for analysis.*(Contains 4 pages, Dashboard - for overall idea about credit card utilization, Demographics - contains customer demographics related information, Spending Analysis - contains customers' spending behaviour related information, and Income Utilization - contains how customers utilize their income)*

**Customer_Behaviour_Data_Analysis.pdf :** This is the documentation of analysis, insights and recommendations as final result.

## Creator

This project is created by **Avirup Mitra**

**LinkedIn :** www.linkedin.com/in/avirupmitra06

Please feel free to DM for any suggestions and improvements or any other queries. Thank you for your time.

**This is an overview of the project. Please refer to the main project files for detailed result**