# School_District_Analysis
## Project Overview

The school board has evidence of academic dishonesty in testing data of a group of students, although the extent of the academic dishonesty is not known, the school board want to uphold the state testing standards. The purpose of this project is to remove the potentially dishonest data. After removing the comprise data we will perform data analysis to show the impact on student performance of the schools budget, size and type.


## Results

As a result of removing the Thomas High School 9th grade students math and reading grades from the data we can answer the following questions:

* **How is the district summary affected?**

Removing the questionable grades did not have major impact on the district schools summary. There is only a neglegible differance between the Average Scores and Passing porcentage as show in tables 1.1 and 1.2 below. We can conclude from this that the amount of students involved in the alleged academic dishonesty is not large enough tohave a signigicant impact the district wide score averages.


**1.1 District School Summary** *With Thomas High School 9th Grade Results removed*
|Total Schools |	Total Students |	Total Budget |	Average Math Score |	Average Reading Score |	% Passing Math |	% Passing Reading |	% Overall Passing |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|15 |	39,170 |	$24,649,428.00 |	78.9 |	81.9 |	74.8 |	85.7 |	64.9|

**1.2 District School Summary** *Complete*
|Total Schools |	Total Students |	Total Budget |	Average Math Score |	Average Reading Score |	% Passing Math |	% Passing Reading |	% Overall Passing |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|15 |	39,170 |	$24,649,428.00 |	79.0 |	81.9 |	75 |	86 |	65|


* **How is the school summary affected?**

Except for the changes to the scores and passing percentage for Thomas high school, removing the 9th grade from Thomas High School, does not any effect in each individual school. All other schools math and reading scores, as passing percentages remain unaffected.

* **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

When we compare the scores and passing percentage for Thomas High School, in the original dataset with the dataset removing 9th grade students scores (table 2.1), again we do not see a significant difference in the averages nor porcentage. Therefore relative to other schools Thomas High school remains one of the top performaming schools, rank as second in the district (table 2.2)

**2.1 Comparing Thomas High School Average Scores and Passing Percentage with and without 9 grade students**
|Thomas High School | Average Math Score |	Average Reading Score |	% Passing Math |	% Passing Reading |	% Overall Passing |
|:---:|:---:|:---:|:---:|:---:|:---:|
|Dataset W/O 9th Grade |	83.350937 |	83.896082 |	93.185690 |	97.018739 |	90.630324|
|Original Dataset |	83.418349 |	83.848930 |	93.272171 |	97.308869 |	90.948012|


**2.2 Top 5 Schools in District**
|School | Type |	Total Students |	Total School Budget |	Per Student Budget |	Average Math Score |	Average Reading Score |	% Passing Math |	% Passing Reading |	% Overall Passing|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Cabrera High School |	Charter |	1858 |	$1,081,356.00 |	$582.00 |	83.061895 |	83.975780 |	94.133477 |	97.039828 |	91.334769|
|Thomas High School	|Charter|	1635|	$1,043,130.00|	$638.00|	83.350937|	83.896082|	93.185690|	97.018739|	90.630324|
|Griffin High School	|Charter|	1468|	$917,500.00|	$625.00|	83.351499|	83.816757|	93.392371|	97.138965|	90.599455|
|Wilson High School|	Charter|	2283|	$1,319,574.00|	$578.00|	83.274201|	83.989488|	93.867718|	96.539641|	90.582567|
|Pena High School	|Charter|	962|	$585,858.00|	$609.00|	83.839917|	84.044699|	94.594595|	95.945946|	90.540541|


Module 4 Repository
