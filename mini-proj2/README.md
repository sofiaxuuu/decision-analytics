# Innovation at Colleges 

## Background
Innovation is the act of bringing new ideas, methods, or things. Why innovation is critical? It is important because technological advances have played a key role in facilitating radically improved standards of living. In particular, scientific-technological innovations play an increasingly prominent role in the growth of leading industrial economies. 

## Business Question 
Therefore, this leads to my business question of: 
_Who Becomes an Inventor? The Importance of Exposure to Innovation_

This question is meaningful because it can help educators and the government to figure out factors that foster innovation, thereby providing a better environment to generate more innovation. 

## Data Question 
_How did parents’ income, students’ income after graduation, college ranking (elite, selective, nonseletive) influence the college’s rate of inventors?_

## List of Data Source 
To answer the above question, I utlize the Opportunity Insights website (https://opportunityinsights.org/data/). There are two major dataset that I use: 
1. [The Baseline Cross-Sectional Estimates of Child and Parent Income Distributions by College](https://github.com/sophiaxuu/decision-analytics/blob/main/mini-proj2/mrc_table2.csv)
2. [Innovation Rates by College](https://github.com/sophiaxuu/decision-analytics/blob/main/mini-proj2/table3.csv)

The table mrc_table2.csv (The Baseline Cross-Sectional Estimates of Child and Parent Income Distributions by College) reports our baseline estimates of parents’ and children’s income distributions by college. The values are calcualted at college-level as means over students in the 1980, 1981 and 1982 birth cohorts. When we first look at our data, we see that we can see the following information: 
* super_opeid: Institution OPEID / Cluster ID when combining multiple OPEIDs
* name: Name of college (or college group)
* tier: Selectivity and type combination (see Table 6 for more detailed descriptions of these groups)
* tier_name: Name of college tier

The tatble table3.vcs (Innovation Rates by College) reports resents estimates of students’ patent rates by the college they attended. The table define the college each child attends as the institution the child attended for the greatest amount of time during the four calendar years in which the child turned 19-22. 

According to Opportunity Insights, they define an individual as an investor if he or she is listed on a patent application between 2001 and 2012 or grant between 1996 and 2014 (see Section II.B of the paper), and as a highly-cited inventor if he or she is among the 5% of inventors with the most patent citations by 2014 within his or her birth cohort. When we first look at the data, we see the followoing information: 
* super_opeid: Institution OPEID / Cluster ID when combining multiple OPEIDs
* count: Number of students
* inventor: Share of inventors among students

## Setup Datasets 
### Combine two datasets 

### Data Cleaning 


## Simple Linear Regression 

## Malti-variable Linear Regression 

## Malti-variable Linear Regression (updated) 

## Calculate Prediction and Identify Outliners 

## Further Analysis and Application



