# An analysis of kickstarter campaigns
Performing an analysis on Kickstarter data to uncover trends

## Overview of Project
### Purpose
The purpose of this analysis is to examine trends within the kickstarter campaign industry, specifically for theaters and plays. 
There are a few ways in which we will examine these trends in this analysis. 
One is to evaluate and compare how well campaigns performed based on the time of year when they were launched. 
A second evaluation will examine percentages that were successful versus those that failed or canceled in comparison to initial financial goals set. 
Two questions when examining this data will be to see if any trends exist as to what time of year a campaign launches as to how successful it may be and the other question will ask if there is a trend in how well a campaign performs compared to how lofty of a revenue goal it set. 

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
In examining Figure 1: Theater Outcome versus Launch, it appears that most successful theater campaigns occured when they were kickstarted in Springtime, especially May. 
Success seems to start off in January, increase into February, peak in May, and then continuously have a slow decline into wintertime. 
The highest amount of campaigns that saw success began in the springtime and the lowest number of campaigns with success kicked off in December. 
Campaigns that saw the highest levels of failures kicked off in October and through the winter. 
Logistically this makes sense, as it is likely that the general population tends to be very busy in the fall months leading up to holidays and likely don't put a lot of time or concern into booking and attending theater productions. Theater productions likely see heights of activity during summer and vacation months when families have more time for freedom, the weather is nicer, and they aren't looking to save their money away for the holidays and gifts, etc. 
When examining campaigns that failed, the numbers are pretty steady across the year and there doesn't seem to be a strong trend line one way or the other in favor of a certain time of year for when a campaign will decide to cancel. 

![Theater Outcomes versus Launch Date](Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals


![Theater Outcomes versus Income Goals](Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
This analysis was performed by creating a pivot table from the main Kickstarter Data Sheet. A pivot table is a helpful analysis for this data because it summarizes it in an easily viewable filtered way. The data became filtered down to focus only on theater campaigns at different times of year. Launch dates became the row while outcomes became the column and the number of outcomes was treated as a value. While I had no issues filtering this data, setting up the pivot chart, and creating a graph that easily depicts the data, I did notice that there were a few campaigns who were still acting as a live. These few live campaigns possibly could skew the data as they can't quite be considered relevant yet, as they have not yet either failed or been successful. Possible challenges and difficulties that could be easily found in this visualization creation might be issue of considering what values to place in which areas of the pivot chart. For example, one might struggle with deciding what fields to put in the columns versus rows, which to decide to count the value of, and which fields to filter on. Other possible difficulties could have been found in attempting to group the data together so that years and quarters did not show, and only months of the year showed. While I did not struggle with these scenarios, had they happened, they could have been solved with trial and error as well as mapping out potential math thoughts and attempting to understand the logics behind what we were attempting to dispaly first. Also google, youtube, and the microsoft platform itself are great resources for help when trying to understand how to solve data issues in excel. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
