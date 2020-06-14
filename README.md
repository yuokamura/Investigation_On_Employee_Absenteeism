# Invetigation_On_Employee_Absenteeism
## General description
These files are from assignment I worked on as a part of course "The Data Science Course 2020: Complete Data Science Bootcamp" by 365 Careers.
In this case study, I explored whether a person presenting certain characteristics is expected to be away from work at some point in time or not.
Absenteeism was defined as: absence from work during normal working hours, resulting in temporary incapacity to execute regular working activity.

## Data Set
Data set was provided by the course. \
There are 700 obesrvations with following attributes:

- ID
- Reason for Absence  
Specific numbers given depends on the nature of the absence.  (28 reasons in total)
- Date
- Transportation Expense
- Distance to work
- Age
- Daily work load average
- Body mass index
- Education
Employee's education level.  (1-highschool, 2-graduate, 3-postgraduate, 4-doctor)
- Children
- Pets
- Absenteeism time in hours

## Method of analysis
### Preprosessing data
There were 28 reasons for absence, and these were grouped into 4 categories. \
Date were put into two new attributes, namely "Month value" and "Day of the Week" \
Education categories had four different entries depends on the


The logistic regression model was deployed
