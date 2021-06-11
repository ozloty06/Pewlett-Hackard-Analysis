# Pewlett-Hackard-Analysis

## Project Overview
The "silver tsunami" is a metaphore used to describe the expected increase in the senior population. As Pewlett-Hackard conducts a strategic review of their workforce, it is important for the company to understand the impact of this increase in seniors as numorous employees will be reaching retirement age in similar timeframes. This is especially critical if the retiring workforce represents at Pewlett-Hackard represents an exit of business acumen, knowledge and expertise, potentially leaving a cricical knowledge gap in the remaining workforce.

## Resources
- Queries on CSV stored employee data using SQL
- PG Admin 4 v5.2 with PostgreSQL v11
- Python v.3.8.3

## Data Summary
For this analysis, we created a summary table counting the number of current employees approaching retirement age listed by job title. Current employees were filtered by distinct employee number to avoid duplicates and employees with birthdates between 1952 and 1955 were pulled into the analysiss. The count of employees who fit this criteria were sorted by job title. The following insights were identified:
- A totel of 90,398 employees will be approaching retirement age, representing approximately 30% of the workforce (assumes 300k current employees).
- Over 60% of the employees reaching retirement age hold senior positions, including Senior Engineer (33%) and Senior Staff(31%).
- The least impacted group is the Manager level employee representing less than 1% of the retirement eligible group.
- The role of the Assistant Engineer and Techinique Leader may be ideally suited for a mentorship program as this group only represents 7% of the retirement eligible group.

![Image of Retirement Count by Title](https://github.com/ozloty06/Pewlett-Hackard_Analysis/blob/main/Image_of_Retirement_Count_by_Title.png)
##### Fig. 1 - Number of Current Employees Approaching Retirement by Title.

An additional analysis was performed to create a summary table of mentorship program eligibility pulling current employees who born in 1965. The following insights were identified:
- Only about 1500 employees meet this criteria.
- There are no management employees that are included in our summary table.
- Aside from management roles, the remaining job titles are similar to the job titles seen in retiring employees.
- Approximately 1100 employees in this age group already hold positions as Senior Engineers or Senior Staff, reducing the possibility of mentorship program involvement leading to promotion opportunities.


## Additional Analysis Recommendations

One large gap in the existing data is management level employees who are approaching retirement are not well represented in the existing tables and queries. Additionally, prior analysis identified a possible gap in the data as management was not represented in all of the departments. 

An additional query can be made to pull current management employees and sort by age to ensure the data is accurate and confirm that tenured staff are represented in management.

Additionally, the query for a mentorship program could be expanded to a larger group to better fill the gap of existing employees and increase the number of employees eligible to participate. 
