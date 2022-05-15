# Pewlett-Hackard-Analysis

## Overview of the Analysis

- Initially, the Pewlett-Hackard company was looking to make a centralized database of their employes from several smaller databases. For the first deliverable, I made three data tables to show who was retiring, the retirees current titles, and the titles of those retiring. The second deliverable uses deliverable 1's work to determine who is eligible for the mentorship program. The purpose of all these analyses is to determine who is retiring in the next few years and who is in a position to find someone to fill their role (mentorship program).

## Results
- For the retire_titles data table, I found the information on the employees who are of the age to retire soon

- For the unique_titles data table, I found the employees, and their current titles, so that there were no duplicates of employees. I did this by using the "SELECT DISTINCT ON" statement.

-For the retiring_titles, I counted how many retirees were under each title and ordered them by descending order.

- For the mentor-elig data table, I joined three tables on the employee number to get the data on each employee that will be retiring in the next year. We need these employees in the worker mentor program to replace their position.

## Summary
- Over the next three years, 72,458 positions will need to be filled, based on on the unique_titles table.

- Based on the mentor_eligibility table, there are only 1,549 employees that are eligible for the mentor program, which is clearly not enough to find and replace prospective employees.

- I have made two additional tables, mentor_group and department_number. Mentor_group divides aggregates each mentor into their title so we can understand how many employees hold each title. From there we can assign them to mentoring a group of prospective employees. The second table, department_number, groups all employees by their department. From these numbers we can calculate about 10% of each department should become a part of the mentorship program and train new employees.