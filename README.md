![screenshot](https://raw.githubusercontent.com/maybemkl/GIS_tweets/master/images/screenshot_overview.png)  

This is my final project for the GIS class in the [Quantitative Methods in the Social Sciences program](http://www.qmss.columbia.edu/) at Columbia University. For my project, I decided to explore the relationship between tweeting and gentrification. 

I started the analysis with one independent variable (rate of change in rents between 2010 and 2015), one dependent variable (amount of tweets in an area) and two control variables (rate of change in education level and income in an area), but ended up dropping the control variable on education. Initially, I also performed my analysis on the level of subborrough areas. This proved problematic, as there are only a few dozen subborrough areas.

In this final version, I use block groups from the United States Tigerlines Census files and associated data on rents and income. The tweets were scraped during one day in November. While this only provided a few thousand tweets, the results from regressing the data at the block group level are encouraging. It seems like it would be worth exploring the connection of tweets to more established gentrification measurments with a bigger sample of tweets.

The hypothesis is that the amount of tweets in an area is positively related to the change in rents in an area. The null hypothesis is that no such relationship exists.

You can see the full project [here](https://rpubs.com/maybemkl/NYCtweetsGentrification).