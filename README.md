# School District Analysis
Module 4:  Pandas and Jupyter Notebook

## Overview of Project
The purpose of this project is to aggregate school and student data and recalculate after the removal of Thomas High School 9th grade scores.   This information will be presented to the school board to provide them with insight on performance trends and patterns in regards to budget and standardized test scores.   The school board will use the information provided to make strategic decisions at the school and district level in regards to student funding, school budgets and priorities.   

Data Source:

schools_complete.csv
students_complete.csv

Software:
Pyton 3.7.6
Jupyter Notebook 6.0.3
Pandas 1.0.1
Numpy 1.18.1

## Results: 
- **How is the district summary affected?**

In the summary for the district, the student scores for 9th graders at Thomas High School were not included.  Therefore, the total student count was decreased in our formulas to account for this change.   The exclusion of these students altered the averages and percentages for the district.    Maria has asked to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. 

After removing the students, the district summary saw the following changes:

 - .1% decrease in average math score
 - Zero change in average reading score
 - .2% decrease in percent passing math
 - .3% decrease in percent passing reading
 - .1% decrease in percent overall passing


<img src="/Resources/New_DistrictSummary.png" width="600"> [New_DistrictSummary.png](/Resources/New_DistrictSummary.png)

<img src="/Resources/Original_DistrictSummary.png" width="600"> [Original_DistrictSummary.png](/Resources/Original_DistrictSummary.png)


- **How is the school summary affected?**

In the summary per school, the school data for Thomas High School has been adjusted.   After removing the students in the formulas for Thomas High School, the data reflected the following changes:

 - .067 decrease in average math score
 - .047 increase in average reading score
 - .086 decrease in passing math percentage
 - .290 decrease in passing reading percentage
 - .318 decrease in overall passing percentage

<img src="/Resources/New_PerSchool.png" width="600"> [New_PerSchool.png](/Resources/New_PerSchool.png)

<img src="/Resources/Original_PerSchool.png" width="600"> [Original_PerSchool.png](/Resources/Original_PerSchool.png)

- **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

Although the percentages for Thomas High School dropped slightly, the drop was not enough to affect their performance in relation to the other schools.    They continue to be one of the top performing schools for the district.


- **How does replacing the ninth-grade scores affect the following:**

  - Math and reading scores by grade - For Thomas High School, the charts are now updated to have a "NaN" value for all 9th grade scores.

<img src="/Resources/New_MathbyGrade.png" height="400"> [New_MathbyGrade.png](/Resources/New_MathbyGrade.png)

<img src="/Resources/Original_MathbyGrade.png" height="400"> [Original_MathbyGrade.png](/Resources/Original_MathbyGrade.png)

<img src="/Resources/New_ReadingbyGrade.png" height="400"> [New_ReadingbyGrade.png](/Resources/New_ReadingbyGrade.png)

<img src="/Resources/Original_ReadingbyGrade.png" height="400"> [Original_ReadingbyGrade.png](/Resources/Original_ReadingbyGrade.png)

  - Scores by school spending - There were no changes in the scores by school spending.   The effect of elimininating the 9th grade students from Thomas High School was less than .01%.

<img src="/Resources/New_SchoolSpending.png" width="600"> [New_SchoolSpending.png](/Resources/New_SchoolSpending.png)

<img src="/Resources/Original_SchoolSpending.png" width="600"> [Original_SchoolSpending.png](/Resources/Original_SchoolSpending.png)

  - Scores by school size - There were no changes in the scores by school spending.   The effect of elimininating the 9th grade students from Thomas High School was less than .01%.
  
<img src="/Resources/New_SchoolSize.png" width="600"> [New_SchoolSize.png](/Resources/New_SchoolSize.png)

<img src="/Resources/Original_SchoolSize.png" width="600"> [Original_PerSchool.png](/Resources/Original_SchoolSize.png)

  - Scores by school type - There were no changes in the scores by school type.   The effect of elimininating the 9th grade students from Thomas High School was less than .01%.

<img src="/Resources/New_SchoolType.png" width="600"> [New_SchoolType.png](/Resources/New_SchoolType.png)

<img src="/Resources/Original_SchoolType.png" width="600"> [Original_SchoolType.png](/Resources/Original_SchoolType.png)
 

## Summary: 
Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

- The district saw a .3% decrease in percent of students passing reading
- The district saw a .2% decrease in percent of students passing math
- Thomas High School's reading percentage decreased by .290%
- Thomas High School's overall passing percentage decreased by .318% 
- The 9th grade scores in the school data are now NaNs

After completing this analysis, it has been determined that removing teh 461 9th grade students from the analysis had no significant changes on the district information.   
