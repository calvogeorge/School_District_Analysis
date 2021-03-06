# School_District_Analysis
## Project Overview

The school board has evidence of academic dishonesty in testing data of a group of students, although the extent of the academic dishonesty is not known, the school board want to uphold the state testing standards. The purpose of this project is to remove the potentially dishonest data. After removing the comprise data we will perform data analysis to show the impact on student performance of the schools budget, size and type.


## Results

As a result of removing the Thomas High School 9th grade students math and reading grades from the data we can answer the following questions:

#### 1. **How is the district summary affected?**

Removing the questionable grades did not have major impact on the district schools summary. There is only a neglegible differance between the Average Scores and Passing porcentage as show in tables 1.1 and 1.2 below. We can conclude from this that the amount of students involved in the alleged academic dishonesty is not large enough tohave a signigicant impact the district wide score averages.


**Table 1.1 District School Summary** *With Thomas High School 9th Grade Results removed*
|Total Schools |	Total Students |	Total Budget |	Average Math Score |	Average Reading Score |	% Passing Math |	% Passing Reading |	% Overall Passing |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|15 |	39,170 |	$24,649,428.00 |	78.9 |	81.9 |	74.8 |	85.7 |	64.9|

**Table 1.2 District School Summary** *Complete*
|Total Schools |	Total Students |	Total Budget |	Average Math Score |	Average Reading Score |	% Passing Math |	% Passing Reading |	% Overall Passing |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|15 |	39,170 |	$24,649,428.00 |	79.0 |	81.9 |	75 |	86 |	65|


#### 2. **How is the school summary affected?**

Except for the changes to the scores and passing percentage for Thomas high school, removing the 9th grade from Thomas High School, does not any effect in each individual school. All other schools math and reading scores, as passing percentages remain unaffected.

#### 3. **How does replacing the ninth graders??? math and reading scores affect Thomas High School???s performance relative to the other schools?**

When we compare the scores and passing percentage for Thomas High School, in the original dataset with the dataset removing 9th grade students scores (table 2.1), again we do not see a significant difference in the averages nor porcentage. Therefore relative to other schools Thomas High school remains one of the top performaming schools, rank as second in the district (table 2.2)

**Table 3.1 Comparing Thomas High School Average Scores and Passing Percentage with and without 9 grade students**
|Thomas High School | Average Math Score |	Average Reading Score |	% Passing Math |	% Passing Reading |	% Overall Passing |
|:---:|:---:|:---:|:---:|:---:|:---:|
|Dataset W/O 9th Grade |	83.350937 |	83.896082 |	93.185690 |	97.018739 |	90.630324|
|Original Dataset |	83.418349 |	83.848930 |	93.272171 |	97.308869 |	90.948012|


**Table 3.2 Top 5 Schools in District**
|School | Type |	Total Students |	Total School Budget |	Per Student Budget |	Average Math Score |	Average Reading Score |	% Passing Math |	% Passing Reading |	% Overall Passing|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:
|Cabrera High School |	Charter |	1858 |	$1,081,356.00 | 	$582.00 |	83.061895 |	83.975780 |	94.133477 |	97.039828 |	91.334769|
|Thomas High School	|Charter|	1635|	$1,043,130.00|	$638.00|	83.350937|	83.896082|	93.185690|	97.018739|	90.630324|
|Griffin High School	|Charter|	1468|	$917,500.00|	$625.00|	83.351499|	83.816757|	93.392371|	97.138965|	90.599455|
|Wilson High School|	Charter|	2283|	$1,319,574.00|	$578.00|	83.274201|	83.989488|	93.867718|	96.539641|	90.582567|
|Pena High School	|Charter|	962|	$585,858.00|	$609.00|	83.839917|	84.044699|	94.594595|	95.945946|	90.540541|



#### 4. **How does replacing the ninth-grade scores affect the following: (Math and reading scores by grade, scores by school spending, scores by school size, scores by school type)**

Replacing the sthe ninth grade students score had litte to no impact of the overall scores, this suggest that the Thomas High School 9th grade students are not either enought to impact the overall scores or that their scores were in line with the general student population scores.
below are the different tables:

**Table 4.1 Overall Scores by Grade**

![Overall_Score_By_Grade](https://github.com/calvogeorge/School_District_Analysis/blob/f60278e9c7e0f1bad429b6f8b1e14dbaeb5f374b/Resources/math_reading_scores_by_grade.png "Overall Scores by Grade")


**Table 4.2 Scores By School Spending**
![School_by_budget](https://github.com/calvogeorge/School_District_Analysis/blob/f60278e9c7e0f1bad429b6f8b1e14dbaeb5f374b/Resources/scores_by_school_spending.png "Scores By School Spending")


**Table 4.3 Scores By School Size**
![School_by_size](https://github.com/calvogeorge/School_District_Analysis/blob/f60278e9c7e0f1bad429b6f8b1e14dbaeb5f374b/Resources/scores_by_school_size.png "Scores By School Size")


**Table 4.3 Scores By School Type**
![School_by_type](https://github.com/calvogeorge/School_District_Analysis/blob/f60278e9c7e0f1bad429b6f8b1e14dbaeb5f374b/Resources/scores_by_school_type.png "Score By School Type")


## Summary

Since there very changes to the overall scores and the scores for the 9th grade students seem to be in line to the scores of the general student population, the data is not supporting the academic dishonesty. The overall passing percentage was also not altered in a significant way for Thomas High School, which suggest the 9th grade students had a similar pass/fail rate as the rest of the school. In conclusion, unless there is additional evidence of academic dishonesty, the 9th grade students scores should be restored.





Module 4 Repository
