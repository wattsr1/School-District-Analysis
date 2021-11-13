# School District Analysis

## Overview

This analysis was completed to look into irregularities in the grades of 15 schools within the district.  The were some suspisions of grade tampering within the 9th grade students of Thomas High School (THS) within this district.  To determine the impact an analysis of the whole data set was completed and this was compared to the same analysis on the data without the suspected group. The data was then summarized to allow for the analysis of the effect on the overall evaluation of the schools within the district.

## Areas of Analysis

For this analysis a CSV sheet containing the math and reading scores of all the students was combined with a dataset containing the broader school data.  The merged data sets provided the overall data for the analysis to be completed.  From this the data was analysed to provide summararies for the following areas:

1. District summary
2. School Performance summary
3. Grouping of the Highest and Lowest performing schools
4. Math and Reading scores by grade
5. Student scores by school spending
6. Student scores by school size
7. Student scores by school type

These summaries were the focus of the analysis to determine the effect of the group of 9th grade student scores from Thomas High School had on the overall analysis of the district and the schools within it. To determine the effect of is group there scores were removed from the analysis and the performance of the school was compared to that of the other schools within the district based on the impact of the analysis with and without this group of students.  To illustrate how this was completed the image below show how the data was removed from the original data set to leave a blank score within the data set.  The analysis was completed using Pandas module in python to clean and modify the data to complete the analysis.  The original and modified analysis are included within this repository.

# Analysis Results

## School District Impact

Within the school district the impact of the s
|    |   Total Schools |   Total Students |   Total Budget |   Average Math Score |   Average Reading Score |   % Passing Math |   % Passing Reading |   % Overall Passing |
|---:|----------------:|-----------------:|---------------:|---------------------:|------------------------:|-----------------:|--------------------:|--------------------:|
|  0 |              15 |            39170 |       24649428 |                   79 |                    81.9 |               75 |                85.8 |                65.2 |

## School Summary Impact
|                       | School Type   |   Total Students | Total School Budget   | Per Student Budget   |   Average Math Score |   Average Reading Score |   % Passing Math |   % Passing Reading |   % Overall Passing |
|:----------------------|:--------------|-----------------:|:----------------------|:---------------------|---------------------:|------------------------:|-----------------:|--------------------:|--------------------:|
| Bailey High School    | District      |             4976 | $3,124,928.00         | $628.00              |              77.0484 |                 81.034  |          66.6801 |             81.9333 |             54.6423 |
| Cabrera High School   | Charter       |             1858 | $1,081,356.00         | $582.00              |              83.0619 |                 83.9758 |          94.1335 |             97.0398 |             91.3348 |
| Figueroa High School  | District      |             2949 | $1,884,411.00         | $639.00              |              76.7118 |                 81.158  |          65.9885 |             80.7392 |             53.2045 |
| Ford High School      | District      |             2739 | $1,763,916.00         | $644.00              |              77.1026 |                 80.7463 |          68.3096 |             79.299  |             54.2899 |
| Griffin High School   | Charter       |             1468 | $917,500.00           | $625.00              |              83.3515 |                 83.8168 |          93.3924 |             97.139  |             90.5995 |
| Hernandez High School | District      |             4635 | $3,022,020.00         | $652.00              |              77.2898 |                 80.9344 |          66.753  |             80.863  |             53.5275 |
| Holden High School    | Charter       |              427 | $248,087.00           | $581.00              |              83.8033 |                 83.815  |          92.5059 |             96.2529 |             89.2272 |
| Huang High School     | District      |             2917 | $1,910,635.00         | $655.00              |              76.6294 |                 81.1827 |          65.6839 |             81.3164 |             53.5139 |
| Johnson High School   | District      |             4761 | $3,094,650.00         | $650.00              |              77.0725 |                 80.9664 |          66.0576 |             81.2224 |             53.5392 |
| Pena High School      | Charter       |              962 | $585,858.00           | $609.00              |              83.8399 |                 84.0447 |          94.5946 |             95.9459 |             90.5405 |
| Rodriguez High School | District      |             3999 | $2,547,363.00         | $637.00              |              76.8427 |                 80.7447 |          66.3666 |             80.2201 |             52.9882 |
| Shelton High School   | Charter       |             1761 | $1,056,600.00         | $600.00              |              83.3595 |                 83.7257 |          93.8671 |             95.8546 |             89.8921 |
| Thomas High School    | Charter       |             1635 | $1,043,130.00         | $638.00              |              83.4183 |                 83.8489 |          93.2722 |             97.3089 |             90.948  |
| Wilson High School    | Charter       |             2283 | $1,319,574.00         | $578.00              |              83.2742 |                 83.9895 |          93.8677 |             96.5396 |             90.5826 |
| Wright High School    | Charter       |             1800 | $1,049,400.00         | $583.00              |              83.6822 |                 83.955  |          93.3333 |             96.6111 |             90.3333 |

## THS Performance Impact

## Impact of Student Scores Across the District

# Summary

