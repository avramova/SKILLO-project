# SKILLO-project
# Project Summary: The University Managements Dashboard
The project involves the development of a comprehensive data analysis dashboard for university management using MySQL and Microsoft Power BI.
Initially, a relational database named "The University Managements" was created in MySQL, consisting of 12 tables. The key tables used for visualization included Payments, Students, Grades, and Professors. These were imported into Power Query, where preliminary data transformations were applied—such as renaming columns for clarity and setting appropriate data types (e.g., decimal for payments, text for names and emails, date formats for dates, and integers for primary keys).
Once data cleansing and transformation were complete, the dataset was loaded into Power BI for visualization.
## •	Page 1: Overview
o	Contains three Cards showing the total number of students, faculties, and programs.
o	A Slicer allows filtering by grade range.
o	A Line Chart displays the average grade per year, calculated using a DAX measure:
average grade = AVERAGE(grades[grade])
o	A Column Chart shows the number of enrolled students per year based on enrollment year.
## •	Page 2: Financial Insights
o	Two Cards display the total payments in euros and the number of transactions.
o	A Clustered Column Chart visualizes total payments by payment method, using the DAX measure:
total payments = SUM(payments[amount])
o	A Slicer is used to filter the payment data by a selected time period.
## •	Page 3: Tabular View
o	A data table with five columns is provided, alongside five slicers for interactive filtering.
o	A restricted view is created through the Modeling menu to enhance user navigation and analysis.
This project demonstrates the ability to integrate data modeling, transformation, and visualization to support university decision-making with dynamic and interactive insights.

