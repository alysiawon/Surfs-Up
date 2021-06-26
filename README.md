# Surfs_Up

## Overview of Analysis

The purpose of this project is to determine the feasibility of opening a Surf n' Shake shop in Oahu, Hawaii. This analysis will focus on analyzing  weather and temperature data for the months of June and December, in order to determine if the surf and ice cream shop business is sustainable year-round.

## Results

The data preparation utilizes Python, Pandas functions and methods, and SQLAlchemy to analyze and create reports. Insight are generated on the <a href="SurfsUp_Challenge.ipynb">Surfs Up Database</a>. 

### Analysis 1: Summary Statistics for June

This analysis filters the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June.

<img src="Analysis/June_Temps.png" width="500">

### Analysis 2: Summary Statistics for December

This analysis is identical to the June analysis, except it focuses on retrieving all the temperature data for the month of December.

<img src="Analysis/December_Temps.png" width="500">

### Key Results

1. The average temperature in June is hotter than it is in December but the standard deviation of December is larger than June. That means that although June is hotter on average, that December's variation from the average is greater.

2. The range from the minimum temperature to maximum temperature for June is 21 degrees, where as for December it is 27 degrees. December has a larger range for temperature.

3. The minimum temperture for June is 62 degrees, whereas the minimum temperture for December is 56 degrees. This is significantly lower than June's temperture as it can get 9 degrees colder. But the maximum temperature is relatively the same and only 2 degrees off. 

## Summary

### Key Summary

Overall, June's weather is better for a Surf and Ice Cream shop because it is overall warmer and does not have as much variation in its standard deviation. In addition, the difference between the minimum and maximum temperture varies less with the minimum temperature at 64 degrees, whereas December going as low as 56 degrees. 

### Recommended Additional Queries

The recommdned additional queries to conduct are:

1. **Precipitation Statistics** 

    In this query, we can determine what month has the most precipitation. This can also effect whether or not the Surf and Ice Cream shop will have a lot of cutsomers as rain can hinder people from coming to the store. 

2. **Additional Temperture Statistics**

    In this analysis, we only looked at June and December statistics. It would be worthwhile to analyze the other months and see if there are any additional months that can prevent the opening of the Surf and Ice Cream shop. 