# Project 1


### Contents:
- [Problem Statement](#Problem-Statement)
- [Data Dictionary](#Data-Dictionary)
- [Brief Summary of Analysis](#Brief-Summary-of-Analysis)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)


## Problem Statement

Mathnasium is a private tutoring company, and currently has a new SAT/ACT Test Prep Program which they are looking forward to roll out this year. For the year 2020, they would like to target several states and dedicate a significant amount of their funds to advertising in these states. The goal is to increase sales for the SAT/ACT Test Prep Program. This project aims to identify ten states, which have had the lowest SAT/ACT scores in 2019, highest participation rates in 2019, states where the SAT and/or ACT is mandatory, so that these states can be targeted for advertisement and marketing.

## Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|ACT/SAT|The name of the state for which data was recorded.| 
|act_participation|float|ACT|The percent of high school graduates who took the test in the given state.| 
|composite|float|ACT|The average composite score for the given state.| 
|sat_participation|float|SAT|The percent of high school graduates who took the test in the given state.| 
|erw|int|SAT|The average score in English/Reading/Writing for all students who took the test.| 
|math|int|SAT|The average score in Math for all students who took the test.|
|total|int|SAT|The sum of erw and math.|
|act_free|int|ACT|Shows if the ACT exam is free in the state.|
|sat_free|int|SAT|Shows if the SAT exam is free in the state.|
|act_required|int|ACT|Shows if the ACT exam is mandatory in the state.|
|sat_required|int|SAT|Shows if the SAT exam is mandatory in the state.|

## Brief Summary of Analysis

We looked at score data for the ACT and SAT exams for the year 2019, by state. In addition we included flags to mark whether a state provided the exam for free, and whether the exam was mandatory in that state. We cleaned the data, saved it, then performed statistical analysis on it to identify trends and to provide answers to questions relevant to our problem statement. 

Sample questions:  
Which states have the lowest scores for the ACT exam?  
Which states have the lowest scores for the SAT exam?  
Is there a correlation between the SAT Math score and the SAT ERW score?  

We included visualizations to gain more insight into the data, and finished with conclusions and recommendations for the given problem.

## Conclusions and Recommendations

**Conclusions:**  

1. There is a strong positive correlation between SAT Math and SAT ERW scores, meaning students who score high/low on the Math section are likely to score high/low on the ERW section as well.
2. There is a weak negative correlation between ACT participation and SAT participation, meaning a state where ACT participation is high will most likely have lower participation in the SAT.
3. Most students scored between 19 and 20 on the ACT.
4. Most students scored between 1075 and 1100 on the SAT.
5. Students tend to score between 525 and 550 on the SAT Math section.
6. Students tend to score between 530 and 550 on the SAT ERW section.
7. States with the lowest SAT scores: Colorado, Arkansas, South Dakota, Tennessee, Wyoming.
8. States with the highest participation in SAT: Alabama, Lousiana, Kentuky, Kansas, Arkansas.
9. States where the SAT is free and mandatory, and report lowest SAT scores: District of Columbia, Delaware, Michigan, Idaho, Maine.
10. States with the lowest ACT scores: District of Columbia, Pennsylvania, Colorado, Virginia, Delaware.
11. States with the highest participation in ACT: Colorado, New Jersey, Washington, Connecticut, New York.
12. States where the ACT is free and mandatory, and report lowest ACT scores: Nevada, Mississippi, Louisiana, Alabama, North Carolina.  


**Recommendations:**

1. Higher SAT Math scores are linked to higher SAT ERW scores.
2. ACT is more popular and mandatory in more states.
3. ACT Prep Programs should be emphasized in the following states: Nevada, Mississippi, Louisiana, Alabama, and North Carolina.
4. SAT Prep Programs should be emphasized in the following states: District of Columbia, Delaware, Michigan, Idaho, and Maine.