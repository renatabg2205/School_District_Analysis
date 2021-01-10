# School_District_Analysis
Analyze school district data and showcase trends in school performance.

## Overview of the school district analysis
The purpose of this analysis is to help the City School District Board to make strategic decisions regarding future school budgets and priorities based on test scores and current school funding. This analysis takes into consideration that the School Board has asked the Chief Data Scientist to replace the math and reading scores for Thomas High School ninth graders with NaNs while keeping the rest of the data intact. The outcome is a comparison between the school district analysis based on the math and reading scores for Thomas High School and the school district analysis after replacing the scores for Thomas High School ninth graders. 



## Results

### Resources
- Data Source: schools_complete.csv and students_complete.csv
- Software: Jupyter Notebook 6.1.4 running on Python 3.7.9

### |||||||||||Using bulleted lists and images of DataFrames as support, address the following questions|||||||||||

- How is the district summary affected?
After replacing the 9th graders scores for Thomas High School, the new results are slightly lower.

![District Summary including 9th graders' scores](./analysis/district_summary_1.PNG)

![District Summary excluding 9th graders' scores](./analysis/district_summary_2.PNG)


- How is the school summary affected?

![School Summary including 9th graders' scores](./analysis/school_summary_1.PNG)

![School Summary excluding 9th graders' scores](./analysis/school_summary_2.PNG)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

![Top 5 schools including 9th graders' scores](./analysis/top_five_1.PNG)

![Top 5 schools excluding 9th graders' scores](./analysis/top_five_2.PNG)


- How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade

![Math scores by grade including 9th graders' scores](./analysis/math_scores_by_grade_1.PNG)

![Math scores by grade excluding 9th graders' scores](./analysis/math_scores_by_grade_2.PNG)


![Reading scores by grade including 9th graders' scores](./analysis/reading_scores_by_grade_1.PNG)

![Reading scores by grade excluding 9th graders' scores](./analysis/reading_scores_by_grade_2.PNG)



Scores by school spending

![Scores by school spending including 9th graders' scores](./analysis/scores_by_spending_1.PNG)

![Scores by school spending excluding 9th graders' scores](./analysis/scores_by_spending_2.PNG)

Scores by school size

![Scores by school size including 9th graders' scores](./analysis/scores_by_size_1.PNG)

![Scores by school size excluding 9th graders' scores](./analysis/scores_by_size_2.PNG)

Scores by school type

![Scores by school type including 9th graders' scores](./analysis/scores_by_type_1.PNG)

![Scores by school type excluding 9th graders' scores](./analysis/scores_by_type_2.PNG)

## Summary
|||||||||||Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.|||||||||||
The results will show these changes affected the overall analysis. 
Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once you’ve replaced the math and reading scores, Maria would like you to repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.
