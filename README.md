# Dissecting Californian SAT Test Results

## Problem Statement

**California is the largest state of the union. Can we predict what schools will perform better on the SATs from their state’s publicly accessed data collection?**

Data sources:

SAT (2019): https://www.cde.ca.gov/ds/sp/ai/ <br>
Expenses (2019): https://www.cde.ca.gov/ds/fd/ec/currentexpense.asp <br>
AP Testing (2019): https://www.cde.ca.gov/ds/sp/ai/ <br>

## Data Dictionary

| Field                    	| Description                                    	| Data Type 	|
|--------------------------	|------------------------------------------------	|-----------	|
| sname                  	| School name                                   	| object     	|
| dname                 	| District of school                            	| object    	|
| cname                  	| County of school                              	| object    	|
| enroll                  	| Totalseniors enrolled                         	| float64   	|
| pctbothbenchmark      	| Percent of test meeting both SAT benchmarks   	| float64      	|
| dailyexpense             	| Amount spent on student per ADA yearly           	| float64   	|
| numpass               	| Number of AP tests receiving AP credit           	| float64   	|

## Analysis

Counties' SAT results vary widely due to population size of counties among financial, cultural, and geographical reasons <br>
Positive correlation between SAT scores and AP classes <br>
Negative correlation between SAT scores and SAT participation <br>
Not enough data on school expenses to make an assertion <br>

## Data to consider

Comparing cities of similar population sizes would reduce data noise <br>
How will ACT benchmark scoring be affected by Californian schools removing standardized test scores?
