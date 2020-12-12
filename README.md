# Pewlett-Hackard-Analysis
## Analysis Overview
The purpose of this analysis is to create two tables: one to determine the number of retiring employees and their position titles, and the other to identify employees who are eligible to participate in a mentorship program. Within the first table, we included information such as employee number, first and last name, position title, and start and end date. In the second, we added employee number, first and last name, birth date, start and end date, and position title. 

## Results
The first table that determines the number of retiring employees and their position titles can be viewed here: [retiring_titles.csv](https://github.com/caseychen3605/Pewlett-Hackard-Analysis/blob/main/Data/retiring_titles.csv)

The second table that identifies employee who are eligible for the mentorship program can be viewed here: [mentorship_eligibility.csv](https://github.com/caseychen3605/Pewlett-Hackard-Analysis/blob/main/Data/mentorship_eligibility.csv)

From these tables, we can see that there are four key takeaways:
1.) Almost a third of the retirees are Senior Engineers, while another third includes the rest of the Senior Staff.
2.) As a result, Senior Engineer and Senior Staff positions have the greatest priority when it comes to deciding which roles the company would like to fill.
3.) Among those that are retiring, there are 1,549 employees that qualify for the mentorship program.
4.) There are more people retiring than there are potential mentors, which means that the company would have to create an efficient program that can cover the disparity between the number of people retiring and the number of people who can be trained to fill these positions.

## Summary
To determine how many roles will need to be filled as the "silver tsunami" begins to make an impact, we can create a graph to categorize the retirees into age groups. For each year, the company can hire (internally or externally) the amount of people that would be retiring, assuming that the retirement age is 65. Currently, we have a list of people who were born between 1952 and 1955. Therefore, we would have a different hiring quota for each of the following four years.

If we look at the current projection of potential mentors and the amount of people retiring, we do not have enough retirees to mentor the next generation of employees. Moving forward, we can create a query that gives us a list of people who are retiring at the end of the current year (and for each following year). From there, the company can prioritize how many younger employees need to be trained to fill up the retired positions. It would also be beneficial if we created a query that grouped mentor-eligible employees into position titles. With this table, the company can plan the mentorship program, specifically, how many mentees a mentor can take on to fulfill the retired roles. 