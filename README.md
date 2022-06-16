# Kickstarter-Analysis

## Overview of Project
	
This project was started by the desire to utlize data to maximize the chances of success for a crowdfunding activity.
The data used is a cross category compilation of successful and unsuccessful crowdfunding campaigns in similar categories.

### Purpose
	
The purpose of this project was to organize and to analyze past crowdfunding events to try and maximize the liklihood of a successful crowdfunding event for an upcoming play.
This analysis will, at the very least, provide some direction as to when, and to what scale, to start a crowdfunding event in the theater/play category.
This analysis will also provide guidance as to which other successful crowdfunding events should be examined more closely so that a similar approach might be taken; thereby, maximizing the liklihood of success.

## Analysis and Challenges
	
For this analysis we needed to make our data a little more readable, sortable, and manageable. 
This required the breaking up of categories and subcategories, as well as reformatting of the dates given into readable dates.
These reformatting techniques allowed us to filter and pivot the data in a way that some proper insights might be taken.
Most of the challenges belonged to the reformatting stage. 
Understanding what a Unix time looks like and know ing that it should be converted in order to be readable is a potential challenge for this an other analyses.
Another challenge could be understanding exact cutoff points for given filters like ">=" vs ">". 
Discussing this with the end user can provide guidance for determining the correct cutoffs to use.

### Analysis of Outcomes Based on Launch Date

![Theater Outcomes Based on Launch Date](https://github.com/Beardlow/kickstarter-analysis/blob/main/Theater_Outcome_vs_Launch.png)	
What we can determine from the Theater Outcomes vs Launch Date analysis is that there seems to be a higher liklihood of success when a crowdfunding event is started in May.
However, this could be due to more events being started in May vs other months since this chart is based off of counts in the Y column. 
A related chart showing percentages of successes and failures based on month started may be a more prudent way to provide actual insight.
This analysis/chart also seems to show that the starting a crowdfunding event in the month of October is more likely to result in a failure than other months.
However, and again, this chart is based on counts and this inference is subject to the same misunderstanding as trying to figure out the best month to start a crowdfunding event.

### Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals](https://github.com/Beardlow/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)
One conclusion of the Outcomes vs Goals chart is that there seems to be an inverse relationship between the goal amount and the likelihood of success.
This can be seen by either one of the trend lines; however, there also seems to be some outliers in the $35k to $45k range.
It may be worth drilling down a little deeper into this goal range and examining particular crowdfunding techniques and activities to determine why the lilihood of success in this range does not follow the same trend as other goal ranges.

### Challenges and Difficulties Encountered
	
One challenge I had was with the COUNTIFS function in Excel. I had used the COUNTIF function before and was unaware of the COUNTIFS function. 
Due to this I misread the COUNTIFS function provided in the module and was attempting to make a COUNTIF function work correctly. It did not.
Re-reading the module section, after becoming mildly frustrated allowed me to quickly realize my mistake and perform the correct analysis.
	
## Limitations of This Dataset

One limitation of this dataset is that the data is not current with the most recent value being from 2017.
Another limitation is that the particular type of crowdfunding activity per attempt is not listed. Auctions, flyers, GoFundMe, etc..
This piece of data. along with analyses similar to what were performed would allow some guidance on effective crowdfunding techniques.
You could even drill down and determine what is the most effective strategy for a given category/subcategory, as well as what is the best strategy for a given goal range or time of year.

