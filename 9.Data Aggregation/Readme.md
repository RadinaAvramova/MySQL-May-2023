Summary : 

-Grouping

-Aggregate Functions

-Having

SELECT

SUM(e.`salary) AS 'TotalSalary'

FROM `employees` AS e

GROUP BY e.`department_id`

HAVING SUM(e.`salary`) < 25000;
