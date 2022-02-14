# kickstarter-analysis

## Overview of Project

Our goal is to assist a decision-maker Louise who wants to start a crowdfunding campaign to help fund a play with a budget of $10,000. We will analyze campaign data to determine the factors that make a project’s campaign successful. 

### Purpose
Louise is interested in knowing how different campaigns performed relative to their launch dates and funding goals since her play "Fever" raised close to its fundraising goal in a short period.

## Analysis and Challenges
To begin the analysis, we need to check the outcomes of other campaigns within the same category and see what effect the launch date and goal had on the results. 

### Analysis of Outcomes Based on Launch Date
A line chart will be used to compare the results of different campaigns over time. We can see that May is the month that launched the most successful campaigns. In addition, we can see that the failed campaigns occurred primarily in January, June, July, and October. 

![Theater_Outcome_vs_Launch](https://user-images.githubusercontent.com/66279829/153790369-1fa61af0-c455-4cc5-9413-72a8ced3fe63.png)

### Analysis of Outcomes Based on Goals
A line chart representing the percentage of successful and failed campaigns based on their goals will be used to compare the outcomes of various campaigns. We can see in the chart below that the goal amount set for the campaign and the percentage of successful campaigns is negatively correlated. In other words, the fewer goals are set for a campaign, the more likely it is to be successful. However, this isn’t the case for most of the campaigns with goals between $35,000 and $45,000. There needs to be more analysis to figure out why this is the case.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/66279829/153790463-8da1d7ab-25a5-4bfc-9535-f3313911c0a1.png)

 
### Challenges and Difficulties Encountered
The challenge I can mention is that to visualize the results based on the goal, we needed to separate the goal into 12 intervals and calculate the percentage of successful and failed campaigns in each group. It was done manually using the countif function, and would be even more challenging if there were more groups of goals. Automating this analysis with VBA using a code would be more appropriate in this instance. 

## Results
The best time to launch a theater campaign is in May to improve chances of success, and to avoid launching the campaign in January, June, July, and October, as most unsuccessful campaigns occur during these months. Louise set a $10,000 goal for this campaign, and that can result in a 50% chance of her reaching that target. Therefore, I advise her to set a smaller goal closer to $5,000 to have a 70% or higher chance of succeeding. 
In addition to goal and launch date factors, further investigation should be made to determine if these factors vary by country or by genre. 
Moreover, since the data set only includes data from 2017 and before, more recent data would be more useful for assessing how the pandemic affected this type of fundraising.
Furthermore, we need to find out if there are other factors not collected that may influence backers to donate more to a specific campaign than another (ads, etc.). 

