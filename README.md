# Hypothesis tests on relationship between student's study patterns and their results

Exploiting collected data from a general survey across the DATA2X02 cohort of Semester 2, 2023, this project analyses and discusses certain behavioural patterns and factors that influence the students' study efficiency. Specifically, `Weighted Average Mark (WAM)` is chosen as the measure of learning performance, and its relationships with some potential related factors are then investigated using general data visualisation and hypothesis tests.

## Data set 

The data was collected via an online survey, in particular a Google Forms, being posted on DATA2X02's Ed platform in August 2023. Hence, the questionaire was accessible and responded by the students of DATA2X02 in Semester 2, 2023 academic year. Breaking down, this cohort has:

* $675$ students in DATA2002; and
* $84$ students in DATA2902 (advanced stream).

## Tasks 
1. Wraggle and preprocessed raw data from the survey using tidyverse, gt, grid and gridExtra packages in RStudio
2. Conducted exploratory data analysis
3. Conducted different hypothesis tests (normal Chi-squared test, Chi-squared test with Monte Carlo simulation, and Wilcoxon rank-sum test) about the relationship between academic result (`WAM`) and potentially related factors
