# Comparing Income in Baltimore, MD and New York with Opportunity Atlas Data

## Background
“Social mobility is the movement of individuals, families, households, or other categories of people within or between social strata in a society. It is a change in social status relative to one's current social location within a given society.” Keeping fluid social mobility is critical for the growth of cities, states, or countries. It gives hope for the poor to escape poverty and increases their living standards. It represents how resources are not controlled by a small group of people and is provided to improve the general standard of living. 

In particular, I want to dive into the social mobility for two cities: Baltimore and New York. I choose these two cities because I attend university in Baltimore, and have visited New York most of the time (as an international student). And I choose to assess social mobility by looking at the individual average income. 

## Business Question 
_How is the Individual Income level differ in Baltimore and New York?_

## List of Data Source 
I obtain my data source all from the same website (https://www.opportunityatlas.org/) . And attached are links to my source cvs files: 
- [Baltimore City Immigrant Individual Income](https://github.com/sophiaxuu/decision-analytics/blob/main/mini-proj1/sources/baltimore_cty_kir_imm_rP_gP_pall.csv)
- [Baltimore City U.S. Native Individual Income](https://github.com/sophiaxuu/decision-analytics/blob/main/mini-proj1/sources/baltimore_cty_kir_native_rP_gP_pall.csv)
- [New York City Immigrant Individual Income](https://github.com/sophiaxuu/decision-analytics/blob/main/mini-proj1/sources/ny%20cty_kir_imm_rP_gP_pall.csv)
- [New York City Native Individual Income](https://github.com/sophiaxuu/decision-analytics/blob/main/mini-proj1/sources/ny_cty_kir_native_rP_gP_pall.csv) 

- [Average individual income for immigrants in New York and in Baltimore](https://github.com/sophiaxuu/decision-analytics/blob/main/mini-proj1/sources/imm_parent_child_income_comparisoin.xlsx)

## Data Question
### 1. How does the Individual Income level differ for U.S. Native and Immigrants in Baltimore and New York?

![Figure 1: Average Individual Income for Immigrants and U.S. Natives in Baltimore](https://github.com/sophiaxuu/decision-analytics/blob/main/mini-proj1/figures/Figure1.png)
![Figure 2: Average Individual Income for Immigrants and U.S. Natives in New York](https://github.com/sophiaxuu/decision-analytics/blob/main/mini-proj1/figures/Figure2.png)

By observing Figure1 and Figure2, we can find out that the Average Individual Income for Immigrants for both Baltimore and New York are approximately the same, which is about $31,500. And the Average of Individual Income for U.S. Native for both Baltimore and New York are also approximately the same, which is around $30,000. The finding is a bit surprise for me because previously I would assume immigrants will have a lower level of average income than natives. Some possible reasons maybe there is a higher population of U.S. natives are in the lowest income range, which could potentially drive the average down. 

### 2. How does Parent Income affect the Immigrant’s Average Individual Income in Baltimore? 
![Figure 3: Average Individual Income Relative to Parent Income for Immigrants in Baltimore](https://github.com/sophiaxuu/decision-analytics/blob/main/mini-proj1/figures/Figure3.png)

The answer is obtained by getting the average individual income level for different races (black, white, Hispanic, Asian), and for different parent income levels (high represent 75 percentiles in income level, middle represent 50 percentiles, and low represent 25 percentile)

Looking at the line graph created, there is a positive correlation between Parent Income and Individual Income for all races. And the most are linearly related with a similar gradient. 


### 3. How does Parent Income affect the Immigrant’s Average Individual Income in New York? 
![Figure 4: Average Individual Income Relative to Parent Income for Immigrants in New York](https://github.com/sophiaxuu/decision-analytics/blob/main/mini-proj1/figures/Figure4.png)

The answer is also obtained by getting the average individual income level for different races (black, white, Hispanic, Asian), and for different parent income levels (high represent 75 percentiles in income level, middle represent 50 percentiles, and low represent 25 percentile). 

There are a few interesting observations. First, I find that the Hispanic in Baltimore relatively low social mobility - this is shown by the high positive gradience of the approx linear relationship between Parent Income Level and Individual Average Income. The steep line represents that individual with wealthy parents tend to have much higher income. 

Secondly, I find that there is a negative correlation between Parent Income Level and Individual Average Income for Asian living in Baltimore. This is counter-intuitive as it means that individuals with less wealthy parents will have higher income. 

## Summary
To summarize from the above analysis, I find that: 
The individual income level for U.S. Native is smaller than Immigrants for both Baltimore and New York, and the values are approximately the same. 

In most cases, individual with wealthy parents will have higher individual income than the poor. Yet there is still notable difference in income inequality among different races both in New York and Baltimore. 

For New York, the correlation between parents and children's income level is pretty similar across all races.  

For Baltimore, some specific races have atypical relationships between parent income and children's income, which indicates excellent social mobility for Asians in Baltimore, and Hispanics in Baltimore may need more efforts to increase social mobility. 