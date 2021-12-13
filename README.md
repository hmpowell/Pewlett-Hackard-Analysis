# Pewlett-Hackard-Analysis

## Overview of the Analysis

The purpose of this analysis was to help a company to prepare for a significant retirement influx with the use of SQL and pgAdmin. This will be necessary for the company to maintain appropriate levels of staff in the future.

## Results
1. Based on the criteria given, there are 1,549 employees eligible to be mentors.
![This is a photo of the code and results to get the number of eligible mentors](https://github.com/hmpowell/Pewlett-Hackard-Analysis/blob/main/mentorship_eligibility.png)
2. There are 90,398 employees nearing retirement.
![This is a photo of a table displaying the number of employees nearing retirement, broken down by job title](https://github.com/hmpowell/Pewlett-Hackard-Analysis/blob/main/retiring_staff.png)
3. There are 2 managers who will be retiring soon.
4. Senior Engineers and Senior Staff are the job titles that will have the most employees retiring.

## Summary
- Over the course of the next several years, there will be at least 90,398 employees needed to fill the positions that will be vacated by the retirees. 
- With the current criteria, there aren't enough employees eligible to be mentors for the new staff members. Each mentor would have just under 60 mentees, which would not be feasible under the assumption that their work loads would remain the same. However, the criteria for mentor selection was only based on birthdates from one year and did not take into account how long a person had been at the company or their job title. There may be more, and potentially better, candidates taking more factors into consideration.
-In addition to the analysis done above, there are two more queries that might help Pewlett-Hackard prepare for the upcoming influx of retirements:
    -The salaries of the outgoing staff would provide input into the financial preparations that would need to go into replacing the staff. It is interesting to note some of the discrepancies between the job titles. For example, an Engineer making more than a Senior Engineer might cause problems in the future when hiring.
![This is a photo of a table displaying the retiring employees and their titles and salaries](https://github.com/hmpowell/Pewlett-Hackard-Analysis/blob/main/retiring_salaries.png)
    -The departments that the potential mentors are in would be helpful if the company would like to expand the pool of mentors and make sure it is distributed in a way that makes sense for the program.
![This is a photo of a table displaying the eligible mentors and their departments](https://github.com/hmpowell/Pewlett-Hackard-Analysis/blob/main/mentors_by_department.png)