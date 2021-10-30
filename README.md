# Kickstarter Analysis

## Overview of Project

### Purpose
Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to understand how different theater campaigns fared in relation to their launch dates and their funding goals (specific to plays). We'll be performing data analysis on several thousand crowdfunding projects to uncover any hidden trends associated with launch dates and funding goals. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
We will use the data to spotlight any theater campaign trends related to launch dates. The screenshot below illustrates how campaigns fared throughout the year. The lines on the chart indicate the campaign outcome and how many campaigns had a specific outcome type for the 12 months of the year. 
![Theater Outcomes by Launch Date Chart](https://github.com/Jflux05/kickstarter-analysis/blob/a03d5fc0b5b5cbf31b8deb634fda79954d965c16/Resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
We will use the data to identify plays campaign success relative to its goal amount ($).  The screenshot of the chart below illustrates how successful and failed campaigns fared based on their campaign goal amounts.
![Plays campaign outcomes by goal amount](https://github.com/Jflux05/kickstarter-analysis/blob/a03d5fc0b5b5cbf31b8deb634fda79954d965c16/Resources/Outcomes_vs_Goal.png)

### Challenges and Difficulties Encountered
The challenge's prompt mentions that it wants it to be well described with screenshots, when it should request a brief breakdown of the analysis performed with screenshots to support it. Additionally, I ran into the issues created by a  difference between local and remote git changes. I also learned a little bit about hidden files and how they can introduce a bit of confusion and require complex merging. Additionally, in the analysis based on goals, the data for plays is limited and for that particular subcategory and there are no cancelled campaigns. Finally, in the prompt for the campaigns by goals, the image showing the different goal ranges displays "Greater than 50000" however this appears to be incorrect. The reason being, that if we were to enter >50000 into our COUNTIF formula the results would be different and not capture all of the qualifying campaigns. 

## Results

### Outcomes Based on Launch Date
- Theater campaigns have the highest success rate when launched between April and August. They are most successful when launched from May to June. Conversely, campaigns have their highest failure rates during the same period. So it's possible that further analysis would be required to really understand what drives campaign success.

- Theater campaigns are more successful at the beginning of the year vs the end of the year (when they begin to taper off).

### Outcomes Based on Goals
Play campaigns with lower goal amounts (< $5,000) have the highest success rate. Campaigns with goals ranging from $20,000 to $34,999 have a high failure rate, however it's clear that campaigns with goals over $45,000 have the highest failure rates. Failed campaigns are invesresly corrilated to Successful campaigns. Additonally, the total count of campaigns >$29,999 is significantly lower than the amount of campaigns with goals < $29,999. 

### Limitations and Recommendations 
The data seems to be quite limited in terms of the sample size we are utilizing. Additionally, the analysis itself is pretty limited in its scope because it does not factor in the other important campaign elements, ie. pledge size, total backers, and/or average donation size. 

I would recommend diving deeper into the data provided by looking into campaign success rates based on total backers (utilizing another a line graph) and then another analysis of how successful play campaigns were based on average donation amount.  

