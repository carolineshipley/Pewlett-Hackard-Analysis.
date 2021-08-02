# Pewlett-Hackard-Analysis.

## Analysis Overview
The purpose of this project is to create two tables: 
1. To determine the number of retiring employees and their position titles 
2. To identify employees who are eligible to participate in a mentorship program

In the first table information such as employee number, first name, last name, position title, and start and end date was included. 

In the second table information such as employee number, first name, last name, birth date, start and end date and position title was included.

## Results
Here is the first table, that determines the number of retiring employees and their position titles: [retiring_titles.csv]()

Here is the second table, that identifies employees who are eligible for the mentorship program: [mentorship_eligibility.csv]()

From the results of these two tables, we can conclude that: 
1. Almost a third of the employees reaching retirement are Senior Engineers, while another third includes the Senior Staff 
2. Senior Engineer and Senior Staff positions should have higher priority to refill 
3. From the employees that are retiring, there are 1,549 employees that qualify for the mentorship program. 
4. There are more employees retiring than potential mentors, so most likely each mentor will be training multiple people to fill these new positions.

## Summary
To determine how many roles will need to be filled as the "silver tsunami" starts to impact the company, we can create a query to group the employees reaching retirement age by birth year. With that said, the company can have more visibility on how many positions they will need to fill each year. We already created a list of people who were born between 1952 and 1955, considering retirement age as 65. As a result we would have a hiring quota for each of the following four years.

Considering the number of potential mentors and the amount of people retiring, there's not enough mentors for training the next generation of employees. One suggestion to help with this situation is to create a query that gives a list of people who are retiring at the end of each year so the company can prioritize how many employees will need to be trained to fill up the retired positions. Another suggestion would be create a query to group eligible mentors and position titles, so the mentorship program can be suited to accomodate this gap.
