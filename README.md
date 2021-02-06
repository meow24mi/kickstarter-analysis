# Kickstarter Crowdfunding Analysis

## Overview of Project
This analysis determines if the fundraising goal and or launch date had an influence on the outcome of the theater projects across all years and all locations.

### Purpose
This analysis will assist in the future direction of fundraising and launch date determination.

## Analysis and Challenges
To perform this analysis, we sorted the data based on the parent category: theatre and the outcome: successful, failed, and canceled. We further sorted the data based on fundraising goals in $5000 increments starting with less than a $1000 and up to greater than $50000,and launch month. In the raw data provided, I developed an additional worksheet that would generate the number of plays based on goal range and sort them based on outcome. This required the use of COUNTIF code. [excel link](https://github.com/meow24mi/kickstarter-analysis/blob/main/Copy%20Kickstarter_Challenge.xlsx) Accuracy is of critical importance, and I had inaccurate calculations. The error was identified when the double checking count did not match. It required that I comb over my work closely to identify the typo. To analyze the outcomes based on launch date, I utilized the pivot table to generate a line graph that presented the launch date in relation to outcome. ![](kickstarter-analysis Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Launch Date
From the theater outcomes based on launch date data, it is identified that plays have very few cancellations based on launch date. The most successful launch month is May; In May there are greater number of successful plays compared to other months, while the failed and canceled plays have little fluctuation. 

### Analysis of Outcomes Based on Goals
Generally speaking, the great the goal, the less likely for success of the play. The goal amount had little to no effect on cancelled plays. 
### Challenges and Difficulties Encountered

## Results

- Plays are mostly successful regardless of the launch date. The most successful launch dates are between May through July.

- Plays with goals less than $15000 are more successful than goals greater than $15000. 

- This dataset does not take into consideration other factors that may influence the outcome of a play, such as actors, directors and or play genre. 

- As an alternative to the line graph to display Outcomes Based on Goals, I would use the 100% stacked column or the stacked bar. It would be clear at a glance the porportions of successful versus failed percentage. 
