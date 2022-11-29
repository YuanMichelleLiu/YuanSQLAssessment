# YuanSQLAssessment
In this assessment I have used MySQLWorkbench as my working envrionment.

## Q1
![Image text](https://github.com/YuanMichelleLiu/YuanSQLAssessment/blob/main/MySQL%20Output/Q1.png)

This is the total clicks.

## Q2
![Image text](https://github.com/YuanMichelleLiu/YuanSQLAssessment/blob/main/MySQL%20Output/Q2.png)

This is the revenue of each store.

## Q3

Please see the full table in MySQL Output file.
It just simply joined the two tables together using LEFT JOIN, RIGHT JOIN and UNION.

## Q4 Subquery
![Image text](https://github.com/YuanMichelleLiu/YuanSQLAssessment/blob/main/MySQL%20Output/Q4.png)

In this question I firstly join the two tables as I did in the last question, then calculate the click rate(total number of clicks/total number of impressions) and the profitability of the impression(total revenue/total number of impressions).

After comparing the output, MN has a relatively higher click rate and CA has the highest profit. Hence, I have got my conclusion: CA store is the most sufficient one.

## Q5.1 Using ORDER BY method
![Image text](https://github.com/YuanMichelleLiu/YuanSQLAssessment/blob/main/MySQL%20Output/Q5.1.png)

This is a simple order by and limit solution.

## Q5.2 Using RANK() method
![Image text](https://github.com/YuanMichelleLiu/YuanSQLAssessment/blob/main/MySQL%20Output/Q5.2.png)

This solusion uses the RANK() function to get the ranking of the store revenues.

## Remarks:
For Question #4, I have only considered the scenario that there are only 1 store in each state. I may need more information and more detail to know the exact relationship between the two tables.
Thank you so much for giving me this opportunity and I have gained a lot from the assessment itself.
