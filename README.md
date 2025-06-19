# Call-Centre-Report-Excel-
****Call Centre Report****

It is a dynamic report.
There are 2-Tables:
1-Calls Table   2-Customer Table

Created data model by establishing relationship between both the tables using column “Customer_id”.
Used DAX measures (gets enabled when you create a data model) to perform calculations.
1-	Call Count= COUNTROWS(calls)
2-	Total Amount= SUM(calls[Purchase Amount])
3-	Total Duration= SUM(calls[Duration])
4-	Avg. Rating= AVERAGE(calls[Satisfaction Rating])
5-	5* Calls= CALCULATE([Call Count], calls[Rating Rounded]=5)
These are not physical columns but are calculations on top of the table.
(Press Ctrl+1 to open ‘Format Shape’)

Description:
•	This report provides a detail overview of the call centre representatives, highlighting their individual contribution to the revenue and customer feedback.  
•	Call Trend Analysis of the call count distributed over month.
•	Bar Charts representing the number of calls taken by each representative and the revenue earned.
•	Male Vs Female callers’ distribution based on different cities.
•	Important KPIs have been used to assess representatives' performance based on factors including revenue contribution, call duration, average rating, and customer satisfaction.

Key Insights:
•	High Revenue Months: As per the call trend, Mar Apr & Oct are the most profitable months having highest number of callers.
•	Rating: The most frequently received rating was 4, with 5 being the second most common.

