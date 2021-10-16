# School-Analysis

## Overview of the school district analysis: Explain the purpose of this analysis.

The school board of a certain district wants to analyze the performance of its schools. The necessary data for this task has been aggregated, although after the first analysis it was discovered that academic dishonesty was discovered in students in 9th grade from Thomas High School. The summary must be redone after removing and changing the data related to the students in question.

## Results: 
Using bulleted lists and images of DataFrames as support, address the following questions.

1. How is the district summary affected?

From the original analysis and into the modified version, except for the average reading score, all metrics go slightly down. This is consistent with a case of academic dishonesty where grades are artificially increased.

Original district summary
![Original District summary](../main/Resources/OG_district_summary.png)
******
Modified district summary
![Modified District Summary](../main/Resources/New_District_summary.png)

2. How is the school summary affected?

Since the academic dishonesty was discovered only in one school, only this is displayed here: Thomas High School.

The original summary shows metrics slightly under 30% higher than the modified version

![Original School summary](../main/Resources/OG_School_summary.png)
****
Modified school summary
![Modified School summary](../main/Resources/New_School_summary.png)


3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Both before and after the modification in the data Thomas High School placed second in the top 5 ranking, but all metrics, except for _Average reading score_ go down a fraction.

Original top performers:
![Original top summary](../main/Resources/OG_top_performance.png)

****
Modified top performers:
![Modified top summary](../main/Resources/New_top_performance.png)

4. How does replacing the ninth-grade scores affect the following:


- Math and reading scores by grade

  Since the academic dishonesty was detected with students in 9th grade the relevant scores were deleted. Both math and reading scores are abscent from the modified summaries.
  
  
Math scores:
  
![Original math scores by grade](../main/Resources/OG_math_by_grade.png)
  
![Modified math scores by grade](../main/Resources/New_math_by_grade.png)
  
*********  
  Reading scores:
  
  ![Original reading scores by grade](../main/Resources/OG_reading_by_grade.png)
  
  ![Modified reading scores by grade](../main/Resources/New_reading_by_grade.png)
  
  
  
- Scores by school spending


![Original scores by school spending](../main/Resources/OG_School_spending.png)
  
 
***

![Modified scores by school spending](../main/Resources/New_School_spending.png)
- Scores by school size

![Original scores by school size](../main/Resources/OG_size.png)
  
 
***

![Modified scores by school size](../main/Resources/New_size.png)


- Scores by school type

![Original scores by school type](../main/Resources/OG_type.png)
  
 
***

![Modified scores by school type](../main/Resources/New_type.png)


## Summary:
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.


1. The most notable change is the summary of metrics from Thomas High School, where averages and percentages go significantly down after the modification.
2. As evidence of the change, when the information is filtered by grade we can see that all of 9th grade in THS is replaces with NaNs, both in reading and math scores.
3. While looking at the top performers we can see THS's metrics go down, even if its overall place in the ranking remains stable.
4. Finally, in the district summary we can see that metrics go down. This change is not very drastic considering only 1 of 15 schools change, but it is a testament to the change in the data.
