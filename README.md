# Kickstarter-Analysis-Challenge-1
## Overview of Project 
Analyze the Kickstarter data set on the outcomes of crowdfunding projects from a variety of industries. 
### Purpose
To analyze the Kickstarter data set for Louise to help determine how the play Fever compared to the successful outcomes of other theatrical kickstarters based upon their launch date and to analyze the overall outcomes of kickstarters based upon their initial monetary goals.
## Analysis and Challenges
One of the biggest challenges with this data set is the ammount of columns that have unecessary information as text. There are about four or five columns that are not needed to analyze this data. ANother glaring issue in the data set is that the currency for each country doesn't seem to have been converted to the same dollar value. When comparing currencies, we need to be certain we are comparing apples to apples and that the goals and pledges are compared to each other using the same exchange rate.  
### Analysis of Outcomes Based on Launch Date
The outcomes for theater crowdfunding based on launch dates looks to have the highest success rate when started in May. From that point, June and July are the second and third best months to start a crowdfunding project, respectively. These months also have the highest number of crowdfunding projects started which would affect the overall amount of all the categorical outputs. The amount of failed and canceled projects seems to be relatively consistent throughout the year. Another conclusion that can be drawn from this chart is that the successful outcomes that started in December had essentially the same number of failed outcomes. It seems this is the least successful time to create a kickstarter.   

![Theater_Outcomes_vs_Launch ](https://user-images.githubusercontent.com/95573310/146690195-b68c2099-39f4-4004-ab33-85a116743868.png)
### Analysis of Outcomes Based on Goals
The conclusion that can be made from the outcomes based on crowdfunding monetary goals is that overall, the lower the amount of the goal, the higher the success rate of the project. The limitation on the data set is the inverted graph tells the same information. The higher the goal the lower the success rate. There is an increase in success rate from 35k-45K but the sample size consists of 9 samples which, compared to the rest of the data is less than 1%. Overall, success rates of kickstarters decrease the larger the monetary goal of funding.

![Outcome_vs_Goals](https://user-images.githubusercontent.com/95573310/146690296-abb28b30-eacb-4735-aaf4-158b8ff6630e.png)

### Challenges and Difficulties Encountered
When writing the SUMIFS formula for the "outcomes based on goals" sheet I had to look up what I was doing wrong and found out that I needed parentheses around the number when hardcoded into the formula. I then tried to format cells A2-A13 in a way that I could use that cell in the SUMIFS formula but realized I would have to create at least one more column to include one of the two goal thresholds. 
## Results
Analyzing the results of these two tables and the data set, which contains information from 2009 - 2017, it seems that the ideal crowdfunding project, for theatrical events, would be created in May and would have a relatively small financial goal to ensure a higher success rate. One chart for this project would have been helpful would have the average amount pledged (once currency was converted) for theater, per country, to create a benchmark goal for Louise to set for their next kickstarter. Another beneficial chart to help Louise analyze this data would have been to breakdown the average amount donated withing the timeframe of the kickstarter to see if there was an ideal length of crowdfunding to maximize pledges.



