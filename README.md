# School District Analysis

School District Analysis using 'Anaconda', 'Jupyter Notebook, 'Pandas' & 'Python'

## Overview of Project

This school district analysis looks at reading and math scores for district schools. It organizes the data by grade, school type, budget, and size. In addition, this analysis pulled out data from Thomas High School's 9th grade class and reevaluated again. Both math and reading scores were replaced with "NaN", which represents a "Not-a-Number" value, for 461 student records. Although this may seem like a significant number, these score replacements did not alter data summaries tremendously overall.

## Results

### When the math and reading grades for 9th grade students from Thomas High School were replaced with NaN, the district summary changed very little. The Average Math score dropped by 0.1, from 79.0 to 78.9.

- Original District Summary

![Original Distric Summary](original_district_summary.png)

- Updated District Summary

![Distric Summary No THS](district_summary_noTHS.png)

### By comparing above two school summary result, we came to conclusion that there is no significant changes of school summary result except Thomas High School results.

- Original School Summary

![Original School Summary](original_school_summary.png)

- Updated School Summary

![School Summary No THS](school_summary_noTHS.png)


### After the removal of the math and reading scores for Thomas High School the impact to the school's performance relative to other schools in the district was not material. Thomas High School maintained its second-place position in the top five schools for the district. However, the average math score the Thomas High school decreased -0.1% and the average reading score increased by <0.1%. Additionally, the percentage of students with passing math, passing reading and overall passing scores at Thomas High Shcool decreased by -0.1%, -0.3% and -0.3%, respectively.

- Original Overall

![Original Overall](original_overall.png)

- Updated Overall

![Overall No THS](overall_noTHS.png)

## Summary

Four changes in the updated school district analysis after reading and math scores at Thomas High School have been replaced with NaNs are as follows:

- Math Average decreased from 83.42 to 83.35
- Reading Average increased from 83.85 to 83.90
- Math Percent Passed decreased from 93.27 to 93.19
- Reading Percent Passed decreased from 97.31 to 97.02