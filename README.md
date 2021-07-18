# School_District_Analysis
Analysis of Math and Reading Scores for a City School District
## Overview and Purpose
This analysis shows a breakdown of different schools in the city, both public district schools and charter schools, their reading and math scores, and their respective budgets and spending per student. It became apparent that the scores for 9th graders in Thomas High School had been altered, and so the dataframes were recreated without those scores.
## Results for the District
This image is the district summary with the altered scores:
![image](https://user-images.githubusercontent.com/84299125/126067368-aaf4cf24-99d0-47b1-b534-957472d4e9c2.png)

This image is the district summary with the altered scores removed from the data:
![image](https://user-images.githubusercontent.com/84299125/126067388-69abc1c6-c7ca-4244-a3c7-e8f980066328.png)

As you can see, the dataframe has been affected in the following ways:

-Decrease in the Total Student Count

-Math scores went down, along with the percentage of students passing math

-Reading scores also went down, along with the percentage of students passing reading

-The percentage of students passing both math and reading went down.

## Results for each School
Thomas High School was the only school affected directly by the changes in the data. Other schools were only affected regarding their ranking relative to Thomas High School.

The percentages of students passing math and reading were profoundly affected for Thomas High School after the altered grades were removed. Before removing the 9th grade scores, THS had averages of 66.9% for Math, 69.6% for Reading, and 65.1% of students passing both, as seen below:

![image](https://user-images.githubusercontent.com/84299125/126068441-c31421ed-9dc2-4790-81e0-c3ed4d08f943.png)


After removing the affected data, the percentage of students passing math went up to 93.2%, for reading 97% and for both 90.6%. This is in spite of the fact that the average scores for math and reading did not change:

![image](https://user-images.githubusercontent.com/84299125/126068480-992f1992-a4c9-4860-a4da-e6ddd4c72d66.png)

These changes made THS the second highest performing school, whereas with the original percentages THS would have been on the low end for performance.
![image](https://user-images.githubusercontent.com/84299125/126068566-48f768f4-407a-4670-9932-a6bca8c48190.png)

The math and reading scores for 9th graders at THS were removed entirely. No other grades were affected.

### Scores by school spending
![image](https://user-images.githubusercontent.com/84299125/126068774-0be7ea4d-cafc-4f12-8e0c-a895cd58ae00.png)

As the above chart shows, there is no simple or direct correlation between higher spending and higher scores. In fact, the highest performing schools have the lowest spending levels. This indicates that other factors are affecting scores.

### Scores by school size
![image](https://user-images.githubusercontent.com/84299125/126068886-4b039c23-bb97-4da8-80ed-7f05ecf552b6.png)

The small and medium schools are quite close in their scores, but the larger schools are far lower. 

### Scores by school type
![image](https://user-images.githubusercontent.com/84299125/126068982-688a97d7-4997-49d6-b49e-f189cc5dd6df.png)

Charter schools score far higher than the district schools.

Based on the above data, it may be possible to raise scores in the district schools by spending more money, but district officials should take care how that money is allocated. Before any financial decisions are made, it is necessary to look at other criteria differentiating the district schools from the charter schools, such as curriculum or classroom size. In addition, I would recommend retesting the 9th graders at Thomas High School to even more accurately reflect that school's performance.

## Summary

Removing the 9th grade scores at Thomas High School made four distinct changes in the analysis. Thomas High School is a medium-sized charter school.

-More consistently high performance in charter schools

-Medium sized schools became the highest performing group of schools

-Thomas High School is now the 2nd highest performing school

-Overall district performance is slightly lower







