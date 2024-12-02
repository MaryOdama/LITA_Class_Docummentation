# LITA_Class_Docummentation

By Odama-Mary-Yegraowo

### Project Title:Microsoft Excel Data Analysis

### Outline
[Foundation of data](#foundation-of-data)

[Data generation](#data-generation)

[Data structure](#data-structure)

[Data storage](#data-storage)

[Data analysis](#data-analysis)

[Statistics](#statistics)

[Data driven dicision making](#data-driven-dicision-making)

### Project Overview
---
Microsoft Excel is a powerful spreadsheet tool used for data analysis, financial modeling, and much more.

### Data generation
This has to do with the collection or capturing of sets of data for easy analysis, how data is propelled,example participant gender, locations etc are set of data. Data generation is stringent by virtue of the tools we use to generate our business processes e.g gender, age, building and vehicles. 
Example of data generation,
https://github.com/MaryOdama/LITA_Class_Docummentation/blob/main/Excel%201.PNG

### Data structure
Is use to analyze data in business

## Key tools to run analysis
  1. Operational system- Is use in executing business processes e.g zoom, sap,oracle etc
  2. Analytic system- Is use in evaluating business processes e.g Excel, powerBi.

### Data storage--Data is stored in
  1. Premises- this type of data is used within the organisation e.g Microsoft excel.
  2. Cloud- Data can be retrieved the way it is stored,this data type is not only use within the organization but publicly.
### Ways to retrieve data
    - Structure data:Data in tabular format
    - Semi-structure data: Data in javascript object notation (Json) format,this data type are not in tabular format, are usually in pairs and cannot be easily analyze e.g Xml
    - Unstructure data: Data usually in audio and vidoe format.
    - ETL: Is an acronims that transform data from a particular structure to structue ready for analysis
    - Extract:Connectiong to data set either on cloud or in premises
    - Transformation: Data set not needed are transform to a desire data
    - Load: When a data set is loaded and ready for usage.

### Data analysis
   1. Data analysis: To injest data into tool for analysis by connecting to data souurce, adding some coloumns or removing coloumns.
   2. Modelling: This is when data from different source communicata with each other
   3. Virsualization: Turning data into chart and graphs

### Three major business owners 
   1. What is working
   2. What is not working
   3. What you should focus on.

### Here is a super quick rundown:
### Cells, Rows, and Columns:This are building blocks of any spreedsheet.Cells are individual boxes where you enter data,rows run horizontally, while columns run vertically.eg
https://github.com/MaryOdama/LITA_Class_Docummentation/blob/main/Spreedsheet.PNG

### Formulas and Functions:These are used for calculations for instance
- SUM: Adds up a range of cells. E.g.,
  =Sum(A1:A10)
- AVERAGE: Calculate the Average of a range. E.g., =AVerage(A1:A10)
- IF:Performs a logical test. E.G =If(A1>10, "Yes", "NO")
- VLOOKUP: Searches for a value in a table. E.G.,=VLOOKUP(B2, A1:D10,3,FALSE)
- CONCATENATE:Joins several text strings into one. E.G., =CONCATENATE(A1, " ", B1)
- COUNT: Counts the number of cells with numbers.E.G =Count(B2:B10)
- MAX and MIN:Finds the highest and the lowest values.E.G=MAX(B2:B10)and=MIN(B2:B10)
- SUMIF: Adds up cells that meet a condition.Example:=SUMIF(A2:A10, ">100)
- COUNTIF: Counts cells that meet a condition. Examples:=LEFT(A2"A10, "YES")
- LEFT/RIGHT/MID:Extract part of text. Examples:=LEFT (A2,3),=RIGHT(A2,2), =MID(A2,2,4) e.g
  https://github.com/MaryOdama/LITA_Class_Docummentation/blob/650aa79494052758672b6691da3254e6d62d5efe/Text%20extraction1%20excel.PNG
- MATCH: Searches for a value and returns its position.Example: =MATCH(50, B2:B10,0)
- INDEX:Returns the value at a given position in a range.Example.=INDEX(B2:B10,4)
  
### Examples can be seen below
https://github.com/MaryOdama/LITA_Class_Docummentation/blob/main/My%20excel%202.PNG
https://github.com/MaryOdama/LITA_Class_Docummentation/blob/main/My%20excel%203.PNG
https://github.com/MaryOdama/LITA_Class_Docummentation/commit/7cf6fc208615b3058ec6cc0167b28105971ce7b7#diff-0ae90d7837ac78495b34e3b70721d01884d5f03ea120e0072e0db951458dc015

### Charts and Graphs:Excel can create various types of charts (like bar,line,pie charts) to represent your data.
https://github.com/MaryOdama/LITA_Class_Docummentation/blob/main/Pivot%20table.PNG

### Pivot Tables: These are used for data summarisation, making it easy to analyze large set of datasets by grouping and calculating data in a flexible way.E.g
https://github.com/MaryOdama/LITA_Class_Docummentation/blob/main/Data%20use%20to%20create%20pivot%20table.PNG
https://github.com/MaryOdama/LITA_Class_Docummentation/blob/main/mi%20pivot.PNG

### Formattinging: Excel allows you to format cells tomake data easier to read. you can change fonts, colors, borders, and number formaats (like currency or percentage).

### STRUCTURE QUERY LANGUAGE(Sql)

### Outline
[What is Sql](#what-is-sql)

[Sql Query](#sql-query)

[Sql Operators and Clause](#sql-operators-and-clause) 

[Basic Sql command](#basic-sql-command)

[Sql Keys](#sql-key)

Structure query language (sql): These is an essential language of databases. it stands for structured Query Language and it is used to communicate with and manupulate databases. With SQL, you can
-  Retrieve Data: Pull specific data points using SELECT statements.
-  Manipulate Data: Insert new record(INSERT), update existing ones(UPDATA), or remove them (DELETE).
-  Combine Data: Use joins to merge data from different tables, making your analysis more comprehensive.
-  Run Functions: Perfom calculations and aggregations like finding sums averages,or counts.
-  In a nutshell,SQL is the tool that makes databases useful, enabling you to turn a set of data into meaningful information

SQL Query:These are requests made to a database to retreive or manipulate data. they act as a commands that tell the database exactly what you want it to do.Here are some basic functions:
   1. CREATE TABLE:Sets up a new table.Example
```SQL
Creat Table Employee(
Staffid Varchar (255) Not Null,
Firstname Varchar (255) Not Null,
Secondname Varchar (255) Not Null,
Gender Varchar (10)Not Null,
Date_of_birth Date,
Hiredate Datetime,
Primary key (staffid)

   
   2. SELECT Queries: Fetch data from the database. Example
```SQL
SELECT *FROM EMPLOYEE

  3. INSERT Queries: Add new records to database. Example
```SQL
INSERT INTO EMPLOYEE (staffid,firstname,secondname,gender,Date_of_birth,hiredate)

https://github.com/MaryOdama/LITA_Class_Docummentation/blob/main/SQL1.PNG

  4.DROP TABLE: Deletes a table from the database.Example
```SQL
------to drop table-------
Drop table employee

  5.DELETE Query: Remove record from the database.E.g
```SQL
------delete sql command------
Delete from employee
Where staffid='ab281'

  6.TRUNCATE: Is like taking a big eraser to yourtable,it removes all rows quickly and efficiently but keeps structure intact,it is different from delete.
------Truncate sql command-------
Truncate table empolyee

  7. SUM:Adds up values in a numeric column.Example
----SUM Sql command------------
```SQL
SELECT SUM(Salary) AS TOTALSALARY FROM Salary

  8. AVERAGE:Calculate the average value of a numeric column.Exaple
----AVERAGE---------
```SQL
SELECT AVG(Salary) AS AVERAGESALARY FROM Salary

  9. COUNT:Count the number of rows that match a specific condition.Example
```SQL
SELECT COUNT(Staffid) AS EmployeeCount FROM EMPLOYEE

  10. UPDATE: Is used to modify existing records in a table
update employee
set secondname = 'Endurance'
where staffid = 'AB405'

  11. ALTER:Is used to change the structure of an existing table in the database.you can add, delete,or modify columns.E.g
ALTER TABLE EMPLOYEE
ADD State_of_Origin varchar (50)

  12. MAX: Finds the highest value in a column.E.g
select max(salary) from Salary

  13. MIN: Finds the lowest value in a column.E.g
select min(salary) as min_salary from Salary

  14. GROUP BY: Is used to arranged identical data into groups.it is super handy for summarizing data
```SQL
select * from employee
select count(staffid),state_of_origin from employee
GROUP BY STATE_OF_ORIGIN

   15. HAVING: These is an SQL Clause,is like the filter for groups created by the GROUP BY clause.it is used to set conditions on groups created by GROUP BY, similar to how the WHERE clause sets conditions on individual rows.
```sql
select count(staffid) as StaffPerSate, state_of_origin 

from Employee

GROUP BY State_of_Origin

HAVING COUNT(staffid) >=3


   16.JOIN: Allows you to combine rows from two or more tables based on a related column between them.E.g
select employee.staffid, employee.firstname, employee.gender,
			 employee.hiredate,employee.state_of_origin, Salary.department,
			 Salary.salary
from employee
join Salary
on salary.Staffid = employee.staffid


  17. LEFT JOIN: Returns all records from the left table and the match records from the right table.If there is no match, NULLs are returned for columns from the right table.
select employee.staffid, employee.firstname, employee.gender,
			 employee.hiredate,employee.state_of_origin, Salary.department,
			 Salary.salary
from employee
left join Salary
on salary.Staffid = employee.staffid

  18. RIGHT JOIN:Returns all records from the right table and the matched records from the left table.If there is no match, NULLs are returned for columns from the left table.
select employee.staffid, employee.firstname, employee.gender,
			 employee.hiredate,employee.state_of_origin, Salary.department,
			 Salary.salary
from employee
Rigt join Salary
on salary.Staffid = employee.staffid

  20. FULL JOIN: Combines the results of both LEFT JOIN and RIGHT JOIN. It returns all records from both tables, filling in NULLs when there is no match.E.g
select employee.staffid, employee.firstname, employee.gender,
			 employee.hiredate,employee.state_of_origin, Salary.department,
			 Salary.salary
from employee
full join Salary
on salary.Staffid = employee.staffid

    21. INNER JOIN:Returns records with matching values in both tables.E.g
select employee.staffid,
           employee.firstname, 
		   employee.gender,
		   employee.hiredate,
			employee.state_of_origin,
			Salary.department,
			 Salary.salary,
			 Payment.Account_No,
			 Payment.Bank,
			 Payment.Payment_Method
			 from employee
inner join Salary
on salary.Staffid = employee.staffid
inner join Payment
on Payment.staffid = salary.Staffid

  22.UNION:Removes duplicate.E.g
select  customerID, Customer_gender, transaction_amount
from LITA_Store_Lekki
union 
select customerID, Customer_gender, transaction_amount
from LITA_Store_Marina

   23. UNION ALL:Keep all duplicate records.E.g
select * from LITA_Store_Lekki
	union all 
	select * from LITA_Store_Marina


### SQL VIEWS
A Structured Query Language View is essentially a virtual table based on the result set of a query. It doesn't store data itself but rather displays data stored in other tables.Views can simplify complex queries,enhance security by limiting data access, and make your database schema more flexible and maintainable.

select * from [dbo].[vw_LITA_Store_Transaction_tbl2]

create view vw_LITA_Employee_Info 
as
select employee.staffid,
        employee.firstname, 
	employee.secondname,
        employee.gender,
	employee.hiredate,
	employee.state_of_origin,
	Salary.department,
	Salary.salary,
	Payment.Account_No,
	Payment.Bank,
	Payment.Payment_Method
from employee
inner join Salary
on salary.Staffid = employee.staffid
inner join Payment
on Payment.staffid = salary.Staffid

select * from [dbo].[vw_LITA_Employee_Info]


-------SQL CASE WHEN-------------------------
SQL CASE WHEN: The CASE statement in SQL is a powerful way to implement conditional logic within your queries.It allows you to create more dynamic and complex queries by including conditions directly in the SQL. 
SELECT * FROM EMPLOYEE

ALTER TABLE EMPLOYEE
ADD AGE AS DATEDIFF(YEAR, Date_of_Birth, Hiredate) -
   CASE
       WHEN MONTH(Hiredate) < month(Date_of_birth)
	   OR (MONTH(Hiredate) = month(Date_of_birth)
	   AND DAY(Hiredate) < DAY(Date_of_birth))
	THEN 1
	ELSE 0
END

-------------
ALTER TABLE EMPLOYEE
ADD AGE AS datediff( year, Date_of_Birth, Hiredate)




PORTFOLIO BUILDING

Project Title:E commerce Sales Analysis

Outline

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools used](#tools-used)

[Exploratory Data Analysis](#exploratory-data-analysis)

[DATA ANALYSIS](#data-analysis)


### Project Overview
---

This Data Analysis project aims to generate insight into the sales performance of the E commerce project over the past years. By analysing the various parameters in the data received we seek to gather enough insight to make reasonable decisions which then enable us to tell compelling stories around our data from the insight gotten and to know the best performance from our data.

### Data Sources
The primary sources of data used here is Data Sale.csv and this is an open source data that can be freely downloaded from an open source online such as as kaggle or FRED or any other Data repository site.

### Tools used
- Microsoft Excel [Download Here](https://www.microsoft.com)
  1. for Data cleansing
  2. for Analysis
  3. for virtualisation
- Sql-Structured Query Langauge for Quering of Data
- Github for portfolio Building.

### Exploratory Data Analysis
EDA involves the exploring of data to answer some questions about the Data such as;
- What is the overall sales trend
- which products are top sellers
- what are the products on peak sales

### DATA ANALYSIS
This is where we include some basic lines of code or queries or even some of the DAX expressions used during your analysis;

```SQL
SELECT *FROM TABLE1
WERE CONDITION = TRUE
```

|HEADING 1|HEADING 2|HEADING 3|
|---------|---------|---------|
|TABLE 1|TABLE 2|TABLE 3|


### MICROSOFT POWER BI
Power Bi is a business analytics tool developed by Microsoft that lets you visualize your data and share insights across your organisation. It is designed to data interactive and virsually appealing.

### Key Features:

    1. Data Connectivity: Connects to a wide variety of data sources, including Excel, SQL Server and many cloud-based sources like Azure and Google Analytics.
    2. Data Transformation: With power Query, you can,transfom, and mash up data from multiple sources.
    3. Virtualizations: Offers a range of virtualizations including charts,graphs,maps and more.You can costomize these to create compelling report
    4. Report and Dashboards: Build interactive report and dashboards that allow users to drill down into the data.
    5. Sharing and Collaboration: Share your insights with others through Power Bi service, collaborate on dashboards,and publish reports to the web or apps.

### How to Get Started:

    1.Download and Install: Start by dowloading and installing Power BI Desktop from the Microsoft website.
    2.Connect Data Sources: Open Power BI Desktop and use the Get Dta feature to connect to your data sources.
    3.Transform Data: Use Power Query to clean and transform your data as needed.
    4.Create Virtualizations: Drag and drop fields into  the virtualization pane to create charts, graphs,and other visual elements.
    5.Build Reports: Combine multiple virtualization into a report.Add interactivity with slicers and drill-through functionality.
    6.Publish and Share: Publish your reports to the Power BI service to share them with others in the organisation.

### Use Cases:

    - Sales and Marketing: Track sales performance,customer behavior, and marketing campaign effectiveness.
    - Finance: Monitor financial performance,budget analysis and forecasting.
    - Operations: Improve operational effifiency with data on supply chain, inventory and production processes.
    - HR: Analyze employee performance,attrition rates and recruitment metrics.


data cleaning in Power Bi involves transforming raw data into a refined and accurate form, making it ready for analysis. Here is a step-by-step guide to help you clean your data using power Bi:
   1. Get Data
      - Open power BI Desktop and click on Get Data to connect to your data source (Excel, SQL,etc).

   2. Load Data into Power Query Editor
      - After selecting your data source, click on Transform Data to open Power Query Editor, Where you will perfom data cleaning.
        
   3. Remove Unnecessary Columns
      - In Power Query Editor, identify and remove colomns that are not requred for your analysis.
      - Right-click on the column header and select Remove or Remove Columns.
     
   4. Remove Duplicate Rows

      - Ensure you data is unique by removing duplicate rows.
      - Select the columns you want to consider for duplication, then go to the Home Tab and click on Remove Duplicates.
     
   5. Filter Data

      - Apply filters to include only the relevant data.
      - Click on the dropdown arrow in the column header,uncheck unwanted values, and click OK.
     
   6. Handle Missing Values

      - Replace or remove missing values as needed.
      - Select the column with missing values, then go to the Transform Tab and use options like replace values or Remove Rows.
     
   7. Change Data Types

      - Ensure that each columns has the correct data type(e.g,text,number,date).
      - Select a column, go to the Transform Tab, and click on Data Type to choose the appropriate type.

   8. Split Columns

      - Split columns with combined data into seperate columns.
      - Select the column, go to the Transfom Tab, and click on the Split Column to choose your split criteria.
     
   9. Merge Queries

      - Combine data from different tables using joins.
      - In the Home Tab, click on merge Queries to combine tables based on a common column.
     
   10. Add Custom Columns

       - Create new columns to derive additional insights.
       - Go to the Add Column Tab and click Custom Column to define your own formulas.
      
   11. Pivot/Unpivot Columns

       - Reshape your data for better analysis.
       - Use the Transform Tab to pivot or unpivot columns, which can help in organizing your data.
      
   12. Apply Changes

       - Once your data is cleaned and transformed, click Close & Apply in the Power Query Editor to load the data back into Power BI.


  Creating conditional and custom help you derive new insights from your data.
  ### Adding a conditional column

  Conditional columns are useful when you want to categorise data based on specific conditions.

   1. Open Power BI Desktop and load your dataset.
   2. Go to Home tab and click on TRANSFORM DATA.
   3. In the PowerQuery Editor, click on Add Column.
   4. Select Conditional Column from the dropdown menu.
   5. Define the new column name(e.g Sales category).
   6. Add your conditions:
      - Choose the columns to test(e.g SalesAmont)
      - Select the operator (e.g, greater than).
      - Set the value(e.g, 1000).
      - Enter the output of this condition (e.g,High).

   7. Add more clauses if needed by clicking Add Clauses
   8. Click OK to apply the changes.

### Creating a Custom Column

Custom columns allow you to create new columns based on fprmulas. 

   1. Open Power BI Desktop and load your dataset.
   2. Go to Home tab and click on TRANSFORM DATA.
   3. In the PowerQuery Editor, click on Add Column.
   4. Select Custom Column from the dropdown menu.
   5. Enter your formula in the formula bar. E.G (If [SalesAmount] >1000 then "High" else "Low").





 


   
      

    
    







