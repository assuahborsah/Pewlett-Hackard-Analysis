# Pewlett-Hackard-Analysis

# Overview


The purpose of the analysis is to determine the number of retiring employees by title and identify employees who are eligible to participate in a mentorship program. 


# Results
The first part of the analysis will cover creating a Retirement Titles Table to hold all the titles of employees born between January 1, 1952, and December 31, 1955.
 
 
 ![image](https://user-images.githubusercontent.com/96086671/168081167-f5e1c253-7ba8-4b0a-9c68-28d549b1174c.png)


 Next, DISTINCT ON statement will be used to filter out employees who may have multiple titles in the database thus creating a table that will hold the most recent titles of each employee.
 
 
 ![image](https://user-images.githubusercontent.com/96086671/168081265-00e0cdbd-3b2c-4e01-91b9-03fe601d2a38.png)

 
After, the COUNT () function would be incorporated into creating a table that has the retirement age employees by most recent job titles and excluding those employees who have already left the company.
 

![image](https://user-images.githubusercontent.com/96086671/168081407-5b973895-6d44-458d-aa5d-640a8bd8301c.png)



Last, a mentorship eligibility table will be created that would hold current employees who were born between January 1, 1965, and December 31, 1965.
 

![image](https://user-images.githubusercontent.com/96086671/168081500-9548bb1d-83d8-4251-b002-0b34d95a09b1.png)



•	The retirement_ titles table shows employees eligible for retirement, how long they have worked, and position held over the course of their career.

•	The unique_ titles table gives a clear view of the recent titles of employees eligible to retire.

•	Retiring_titles table shows that employees that have retirement age by most recent job titles fall under the senior management titles.

•	Most of the employees who are eligible for mentorship have senior titles.


# Summary
There may be as many as 90,398 employees retiring soon. This is an extraordinarily large number of vacancies to be filled.

As for the mentorship program, there will be enough qualified, retirement-ready employees to cover up. About 1600 employees .
