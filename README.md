# Kickstarter-Analysis-GB
Performing Excel analysis on kickstarter spreadsheet
----------------------------------------------------------------------------------------------------------------------
## Kickstarter Part 1

- Created Pivot Table with Kickstarter spreadsheet
- Created stacked bar-chart to illustrate the Outcomes of all Parent Categories

![](https://github.com/GR8505/Kickstarter-Analysis-GB/blob/master/PNGpicture.png)


- Under Edinburgh Research Spreadsheet, I used VLOOKUP formula to create table for the following campaigns:
  - Be Prepared
  - Checkpoint 22
  - Cutting Off Kate Bush
  - Jestia and Raedon
  - The Hitchhiker's Guide to the Family


- Demonstrated the following skills in the kickstarter spreadsheet:
  - Conditional Formatting
  - Filtering
  - Created New Columns using Text to Columns function
  - Used Formulas to round numbers and convert Unix Timestamps to dates
  
  
- Created BoxPlot for UK Musicals for Fundraising Goal and Amount Pledged

![](https://github.com/GR8505/Kickstarter-Analysis-GB/blob/master/UKMusicalsGoalandPledged.png)


## Kickstarter Part 2

- Demonstrated ability in using formulas to compute:
  - Measures of Central Tendency
  - Distribution of Data
  
  
![](https://github.com/GR8505/Kickstarter-Analysis-GB/blob/master/DescriptiveStatistics.png)





### Challenge

Louise’s play Fever came close to its fundraising goal in a short amount of time. How many other Kickstarter campaigns were able to do this as well? In this challenge, you’ll conduct a data analysis to answer this question and determine whether the length of a campaign contributes to its ultimate success or failure.


### Analysis

- Louise’s play Fever achieved 86 percent of its fundraising goal during a 28-day campaign, which commenced on June 13, 2016 and ended on July 11, 2016.
- Out of the 1,393 theater Kickstarter campaigns, only 42 had a 28-day campaign of which, 71 percent reached their fundraising goal and the remaining 29 percent failed.
- However, looking at length of a campaign to determine the success of theater campaigns provide little insight.
- The distribution of Failed and Successful theater Kickstarter campaigns by length of campaign are similar.


![](https://github.com/GR8505/Kickstarter-Analysis-GB/blob/master/SuccessfulbyLengthofCampaign.png)

![](https://github.com/GR8505/Kickstarter-Analysis-GB/blob/master/FailedbyLengthofCampaign.png)


- The reason for this is simple.  In analyzing the measures of central tendency for the variable length of campaign, we realize that the mean, mode and median are very close, so most campaigns run for approximately 30 days.


![](https://github.com/GR8505/Kickstarter-Analysis-GB/blob/master/LengthofCampaignBoxPlot.png)

* Mean = 33.5
* Median = 30
* Mode = 30

- Therefore, length of campaign tells us little.
- Probably, the launch date may be more insightful.


![](https://github.com/GR8505/Kickstarter-Analysis-GB/blob/master/OutcomesBasedonLaunchDatePNG.png)


- From this chart, we can see that campaigns launched in the month of May tend to do better, with the highest success rate of 66.9 percent. The months of June (65.4 percent) and July (63 percent) are the second and third most successful months, which is a clear indication that theater Kickstarter campaigns do well when launched during the summer.


- On the other hand, launching a campaign in the months of August, October and December are not encouraged, as they have the highest failure rates of 38.2 percent, 43.5 percent and 46.7 percent, respectively.



- Looking at how the goal affects the success rate of a Kickstarter campaign.


![](https://github.com/GR8505/Kickstarter-Analysis-GB/blob/master/OutcomesBasedonGoalsPNG.png)


- Based on this chart we can see that a campaign has a higher probability of being successful if:
1. Fundraising Goal < $20,000
2. $35,000 < Fundraising Goal < $45,000


**Conclusion**
- Given that Louise launched her campaign in the month of June (during the summer) with a fundraising goal of $2,885 (which was LESS than $20,000), we suggest the following:
1. Launch the campaign in May (which has the highest success rate for theater)
2. Maintain the fundraising goal at $2,885








