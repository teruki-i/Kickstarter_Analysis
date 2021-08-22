# Kickstarting with Excel

## Overview of Project

### Purpose
This analysis sought to uncover trends in Kickstarter campaign outcomes. More specifically, my goal was to determine how campaigns fared based on their launch dates and goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![Theater_Outcomes_vs_Launch.png](https://github.com/teruki-i/Kickstarter_Analysis/blob/5920f67fcaf4dc136a19acf61be2d94e768f8caa/Theater_Outcomes_vs_Launch.png)

Focusing on just theater campaigns provided in the data, it is apparent that there is a sudden increase in campaign launches between April and May from 92 to 113 in total. Of the 113 campaigns launched in May, 111 (approximately 67%) were successful. There was a slight decrease in the number of campaigns launched in June to 153, but 100 of them (approximately 65%) were successful. The total number of successful campaigns launched continue to decline as the year goes on.
This data would suggest that May and possibly June would be the best time to launch a theater fundraiser on Kickstarter. With a lack of percentages presented though, it was initially hard to see in relative terms how the outcomes trended over time.

### Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals.png](https://github.com/teruki-i/Kickstarter_Analysis/blob/5920f67fcaf4dc136a19acf61be2d94e768f8caa/Outcomes_vs_Goals.png)

Drilling down further and looking specifically at campaigns for plays, we also examined outcomes based on campaign goal amounts.
76% of campaigns that set goals below $1,000 while only 17% of those setting goals above $50,000 were successful. However, there doesn't seem to be a smooth, straight line relationship between success rates and goal amounts. There was a clear decrease in success rates as goal amounts decreased from less than $1,000 to $34,999 to 27%. However, there was a sudden increase in success rates as campaigns with goals of $35,000 to $44,999 had success rates of 67%. Due to a lack of sufficient data though, it might be hard to understand the true relationship between goal amounts and outcomes. Therefore, it is hard to really assess if this fluctuation is an aberration.

### Challenges and Difficulties Encountered

## Results

### Outcomes based on Launch Date

As May and June had so many successful campaigns, those two months may be the best time to launch a campaign on Kickstarter. There was a noticeable decline in successful campaign launches in the following months with December having almost the same number of successful and failed campaigns, which suggests that the winter months are possibly the worst for launching a campaign.

### Outcomes based on Goals

In general, the data seems to suggest that campaigns with lower goal amounts tend to be more successful. campaigns with goals below $1,000 were the most successful at a rate of 76% and the success rate noticeably decreases as the goal amounts increase, though with some fluctuations.

### Limitations

The outcomes based on goal amounts had a sudden increase in success rates for campaigns with goals between $35,000 and $44,999. This fluctuation from the overall trend suggests that goal amounts might not be the best predictor of outcomes. However, when looking at the number of project within each goal range, of the 978 play fundraisers, 824 had goals below $10,000. In other words, there were not too many campaigns with larger goals. Because of this, there might be insufficient data to really gain insight when it comes to the relationship between goal amounts and outcomes.

### Possible Improvements for Future Analyses

For the analysis of outcomes based on launch date, it would be helpful to have a table or bar graph showing the percentages of successful and failed campaigns for each month. The line chart in this analysis only quantified the outcomes in absolute terms. Since the total number of successes and failures would be expected naturally to increase as the total number of campaigns increase, it's important to also look at the outcomes in relative terms to more accurately understand the relationship between seasonality and outcomes.
The analysis of outcomes based on goals would also be helped with a pie chart showing the percentage of campaigns that fell within each goal range. As already discussed in the limitations, the overwhelming majority of campaigns had goals below $10,000, which suggests that we don't have enough data regarding larger campaigns and might not have the best data to make a more thorough analysis on the relationship between goal amounts and outcomes. This limitation is not at all apparent when observing the line graph created for this analysis. A box plot could also help highlight this problem. The descriptive statistics of the goal amounts show that the first quartile is at $2,000 and the third quartile is at $15,000. With an IQR of $13,000, any goal amount above $34,500 is an outlier in this data set.  A box plot showing this would thus make apparent the lack of campaigns with very large goals in this data set.
