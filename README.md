# School District Analysis

## Overview

This analysis was completed to investigate irregularities in the grades of 15 schools within the district.  There were some suspicions of academic dishonesty within the 9th grade students of Thomas High School (THS) of this district.  To determine the impact of the data including and excluding the 9th grade group of THS and the other schools, an analysis of the student grades for the district was completed to evaluate the impact of the performance of the schools by comparing the performance of this district with and without the suspected group. The data was then summarized to allow for the analysis of the effect on the overall evaluation of the schools within the district.

## Areas of Analysis

For this analysis a CSV file containing the math and reading scores of all the students within the district was combined with a dataset containing the broader school data for the district.  The merged data sets provided the overall data for the analysis to be completed.  From this the data, an analysis of the school's performance was completed to provide summaries for the following areas:

1. District summary
2. School Performance summary
3. Grouping of the Highest and Lowest performing schools
4. Math and Reading scores by grade
5. Student scores by school spending
6. Student scores by school size
7. Student scores by school type

These summaries were the focused to determine the effect of the group of 9th grade student scores from Thomas High School had on the overall analysis of the district and the schools within it. To determine the effect this group had across the district, their scores were removed from the analysis and the performance of the school was compared to that of the other schools within the district based on differences observed between the two seperate analysis completed of the students.  To illustrate how this was completed the image below show how the data was removed from the original data set to leave a blank score for the 9th grade students at Thomas High School within the data set. Using this new data set and analysis of the performance of the schools with and without the suspected group could be completed. This analysis was completed using Pandas module in Python to clean and modify the data to complete the analysis.  The [original](PyCitySchools_Challenge_Initial_Analysis.ipynb) and [modified](PyCitySchools_Challenge_revised_Analysis.ipynb) analysis are included within this repository.

### Resulting Data Set Showing the Removed 9th Grade Students at Thomas High School
<img src="Resources/Revised_student_data.png" width="1400" height="300">

---

# Analysis Results

## School District Impact

Based on the analysis of the district with and without the 9th grade students at Thomas High School, the overall impact was relatively minimal. As seen in the data below it shows a roughly 0.1% impact in the overall student performance in Math and a 0.2% overall performance in Reading compared to the overall student data within the district before the removal of the scores. Below shows the variations observed in the data between the two analyses.

### District Summaries for Initial (top) and Revised (bottom) Analysis
<img src="Resources/District_Summary_Initial_Adjusted.png" width="1200" height="500">
 
## School Summary Impact

A deeper analysis of the impact of the 9th grade students of THS across the other schools within the district to see if there was an enough of an effect to warrant further action.

Based on the impact of the removal of the performance of the 9th grade student of THS within the district, there was a minimal effect on the performance of the schools with the removal of the scores of the suspected group of students of the school regarding the percentage of students passing the math and reading requirements versus those that have passed math and reading overall.  This minimal variation was observed in the school summary developed in the analysis that was completed with and without the group of students in the analysis. Below shows the differences observed between the two DataFrames. 

### Initial Analysis Overall School Performance
<img src="Resources/School_Summary_Initial.png" width="1200" height="500">

### Revised Analysis Overall School Performance
<img src="Resources/School_Summary_Revised.png" width="1200" height="500">

## THS Performance Impact

The performance of THS was significantly impacted by the removal of the 9th grade student scores.  Looking at the overall performance of THS with the grade 9 student scores there appears to be a small reduction of the overall student performance. With the analysis excluding the 9th grade student from the overall performance of THS in the school district there was an approximate 0.09% reduction in the math scores and a 0.29% reduction in reading scores in THS with the grade 9 students removes. A summary of the data is shown below

The remove of the 9th grade students had no significant effect of the overall school performance within the district as seen in the image below

### Initial Analysis School Ranking - Top 5 and Bottom 5
<img src="Resources/Top_Bottom_performing_Schools_Initial.png" width="1400" height="500">

### Revised Analysis School Ranking - Top 5 and Bottom 5
<img src="Resources/Top_Bottom_Performing_Schools_Revised.png" width="1400" height="500">

## Impact of Student Scores Across the District

Based on the removal of the 9th grade student score for Math and Reading there was no significant effect on the ranking of THS in based on school budget school size or school type. This is shown it the images below which show the variations of the data that includes or removes the 9th grade THS data.

### Student Scores by School Spending
<img src="Resources/Spending_per_student_initial_revised.png" width="1400" height="600">

### Student Scores by School Size
<img src="Resources/Student_scores_by_school_size_Initial_Revised.png" width="1400" height="600">

### Student Scores by School Type
<img src="Resources/Student_scores_by_type_Initial_revised.png" width="1400" height="500">

---

# Summary

From this analysis, the effects of the removal of the Thomas High School 9th grade reading and math scores showed that there was little impact on the overall performance of the school within the district.  This was illustrated in the small impact (0.1%) change in overall scores and minimal effect on the math and reading scores of THS with the revised analysis.  There was no change in the ranking of the school within the district and the change had little effect on the performance of similar size and type of school with similar budgets per student.  The small effect could be due to the small number of students the 9th grade at THS makes up for in the district with this group accounting for only 421 students of the 39170 students in the district.  This group makes up approximately 1% of the student population within the district but when looking at the grades of the school without the 9th grade scores included there is again a minimal change in the overall performance of the school.

---
