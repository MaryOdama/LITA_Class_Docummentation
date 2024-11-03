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
  
### Example can be seen below
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
   1. SELECT Queries: Fetch data from the database. Example
```SQL
SELECT *FROM EMPLOYEE
   2. INSERT Queries: Add new records to database. Example
```SQL
INSERT INTO EMPLOYEE
   









### Project Title:E commerce Sales Analysis

### Outline
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





