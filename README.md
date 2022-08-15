# kickstarter-analysis
## Overview of Project
Performing an analysis on Kickstarter data to discover trends and create images to help describe those trends.---
## Analysis and Challenges
I preformed my analysis by starting on deliverable 1. I started with the dataset and creating a column for years that way I could create a pivot table and line chart to make the dataset easier to understand.---
I did run into a challenge with deliverable 2 witht the countifs function but I watched the video that was given as a hint and it helped me get an idea of what I needed to add to the function. I was forgetting to add quotes around the word for the filter for this example it was lets say "failed", but once I realized that it went smoothly. =COUNTIFS(Kickstarter!$D:$D,"<1000",Kickstarter!$F:$F,"failed",Kickstarter!$S:$S,"plays") is the correct way but I was putting in =COUNTIFS(Kickstarter!$D:$D,"<1000",Kickstarter!$F:$F,failed,Kickstarter!$S:$S,plays)---
## Results
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/110861876/184721333-ea8951e5-b309-4b2b-a124-d26cd29dac5a.png) The Theater Outcomes by Launch Date line graph  gave me two outcomes that stood out and those two are that May is the most successful month and the other being that there is zero cancelled in October.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/110861876/184722062-c189bcaa-4bdd-4dd9-bc69-31cc4d9c388c.png) One conclusion with the Outcomes based on Goals line graph  is the goal range of 45000 to 49999 failed 100% of the time.---
The limitaions of the dataset are that the date created and the date ended are not all the same span of time which creates different implications to how much money can be pledged in that time of the year.
Seperate tables and graphs I would recommend would be how much does backers effect the success/failure rate.
