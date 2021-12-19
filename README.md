# Kickstarter-Analysis-Challenge-1
## Overview of Project 
Analyze the kickstarter data set which contains information from 2009 - 2017 on the outcomes of crowdfunding projects from a variety of industries. 
### Purpose
To analize the kickstarter data set for Louise to help determine how the play Fever compared the successful outcomes of other theatrical kickstarters based upon there launch date and to analysis the overall outcomes of kickstarters based upon their inital monetary goals.
## Analysis and Challenges
One glaringing issue in the data set is that the currency for each country doesn't seem to have been converted to a common number. When comparing moneies we need to be certain we are comparing apples to apples and that the goals and pedges are compared to each other with the same currency. 
### Analysis of Outcomes Based on Launch Date
The outcomes for theatre crowdfunding based on launch dates looks to have the highest success rate when started in May. From that point June then and July are the second and third best months to start a crowdfunding project, respectively. It also seems that the amount of failed and canceled projects seem to be relatively consistent throughout the year. These months also have the highest number of crowdfunding projests started which would affect the overall ammount of all the categorical outputs. Another conclusion that  can be made from this chart is that....

![Theater_Outcomes_vs_Launch ](https://user-images.githubusercontent.com/95573310/146690195-b68c2099-39f4-4004-ab33-85a116743868.png)
### Analysis of Outcomes Based on Goals
The conclusion that can be made from the outcomes based on crowdfunding monetary goals is that overall, the lower the amount of the goal, the higher the success rate of the project. The limitation on the data set is the inverted graph tells the same information. The higher the goal the lower the success rate. There is a increase in success rate from 35k-45K but the sample size consists of 9 sampes which, compared to the rest of the data is less than 1%. Overall, success rate trends down the larger the monetary goal.

![Outcome_vs_Goals](https://user-images.githubusercontent.com/95573310/146690203-3b8fb3d3-9145-4ceb-bc6e-a15fbe5b25ad.png)

### Challenges and Difficulties Encountered
When writing the SUMIFS formula for the "outcomes based on goals" sheet I had to look up what I was doing wrong and found out that I needed parentheses aound the number when hardcoded in to the formual. I then tried to format cells A2-A13 in way that I could use that cell in the SUMIFS formula but realized I would have to create at least one more column to include one of the two goal thresholds. 
## Results
Analyzing the results of these two tables and the data set it seems that the ideal crowdfunding project would be created in May and would have a relatively small financial goal to ensure a higher success rate. Logically this make sense as ususally the higher the financial obligations are to create a business plan the higher the risk. 



- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
