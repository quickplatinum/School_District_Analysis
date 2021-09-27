# School_District_Analysis
Module 4: PyCitySchools with Pandas

## Overview of the school district analysis
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked me to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.

## Objectives
The goals of this challenge are for the schoolboard and Maria to do the following:
- Filter DataFrames using logical operators.
- Replace the incorrect values with NaN.
- Explain how your PyCitySchools analysis changes after you handle the incorrect data.

## Results: Using bulleted lists and images of DataFrames as support:

### How is the district summary affected?
- The district summary is shown below without any data cleanup
![District Summary Before](https://user-images.githubusercontent.com/88692025/134841400-e6e2cbbd-bc0e-49a0-8ecd-fc7aa24f00c6.PNG)
- The district summary is shown below without any data cleanup
![District Summary After](https://user-images.githubusercontent.com/88692025/134841456-a6b0fc9e-d833-4473-98ae-628c9e6688fd.PNG)
- The district summary can be seen to have a small change in averages, namely lower than before after cleaning the dishonest results. 

### How is the school summary affected?
We can observe that after data cleanup the overall passing percentage number decreased from a very high 95.3% to an slighly lower 90.6%.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- The school is not impacted compared to other schools. It has not been greatly effected, this can be seen the most when checking the ranking of the Thomas high school, originally they were amongst the top 5 in the district and after cleaning the data they remained second overall.

## How does replacing the ninth-grade scores affect the following:

### Math and reading scores by grade
- As observed above math and reading scores by grade are changed slighty by removing the 9th grade students
- Overall does not affect the position og the school in the top 5 in the ditrrcit as it remains in 2nd place
- Changes in grade passing percentages are downward

### Scores by school spending
- The Thomas high school remains in the bracket of $630-$644
- However there is a change in the budget per student, since the 9th graders were removed the bottom figure of division by the budget is changed
- Spending per student  went from $639 to $889 after the cleanup.

### Scores by school size
- When removing the 9th grade results, the scores by shcool size, THomas High School remains in the same Medium 1000-2000 bucket
- Scores are trending downards slightly after celanup.

### Scores by school type
- When removing the 9th grade results, the scores by shcool size, THomas High School remains in the same Charter category
- Scores are tredning downwards slightly due to cleanup.

## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs:
1- First Change: Percentage of students that passed reading and maths. 
2- Second Change: Average reading and average math scores.
3- Third Change: Overall passing perenctage.  
4- Fourth Change: Slight change in budget per student and spending, with it being higher.
