**Dev:** *VaneC*
**Date:** *May31,2022* 
# Title 
## Foundations of Database & SQL Programming 
Assignment 07 - Functions

## Introduction 
This week we learned how to use below built-in MS SQL functions to retrieve information from a database. 
1)	Selecting with common functions: like CAST, CONVERT, STR, CONCAT, FORMAT, IIF, CASE, ISNull, ISNumeric, ISDate, Left and Right, LTrim and RTim, REPLACE, PATINDEX, SUBSTRING Date/Time and Soundex().   
2)	Partitioned or Window function, over(partition col): using Over-Partition function let us group by only some of the columns.
3)	Ranking Functions, RANK( ): return a ranking value for each row in a partition.   
4)	Lag and Lead: shows the previous or following values based on a giving group of values. 
5)	Using functions for reporting: start off with a simple select statement and build on it by adding more and more detailed code to finally get what we expect. When the code is too complex, we can create a reporting view to save the code for reuse. 
6)	User Defined Functions (UDF): except above MS SQL built-in functions, we can create custom functions, it called User Defined Functions or UDFs. There are 2 basic functions, one returns a single value and another one returns a table value.    
## When you would use a SQL UDF 
SQL UDFs prevent us from writing the same logic multiple times, 
we can create the method once, and reuse number of times and help us to separate the complex calculations from the regular query, when we need to create a complex report, we can use SQL UDFs to help us.  Also, we can use WHERE clause to filter data in UDF, when we need to send report to clients, we can use the created UDF and WHERE clause to limit the data we would like to present.  
The differences between Scalar, Inline, and Multi-Statement Functions
Scalar Function: there are 2 types of scalar function, deterministic and nondeterministic. 
•	Deterministic: returns the same result with the same set of input parameters, 
           for example: MONTH( ), DAY( ) and ISNull(). 
•	Nondeterministic: returns a different value each time, for example: RANK (), GETDATE () and  @@CONNECTIONS.  
Inline Function: It returns a table data type based on a single SELECT Statement. 
Multi-Statement Function: it returns the result of multiple statements. We can execute multiple queries within the function and aggregate results into the returned table and enclosed in Begin-End blocks.  
## The differences between Scalar, Inline, and Multi-Statement Functions
Scalar Function: there are 2 types of scalar function, deterministic and nondeterministic. 
•	Deterministic: returns the same result with the same set of input parameters, 
           for example: MONTH( ), DAY( ) and ISNull(). 
•	Nondeterministic: returns a different value each time, for example: RANK (), GETDATE () and  @@CONNECTIONS.  
Inline Function: It returns a table data type based on a single SELECT Statement. 
Multi-Statement Function: it returns the result of multiple statements. We can execute multiple queries within the function and aggregate results into the returned table and enclosed in Begin-End blocks.  
😎
