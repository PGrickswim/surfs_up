# surfs_up
Module 9

## Overview
In this challenge, using Python, Pandas, and SQLAlchemy, I've filtered the date column of temperature observations in the hawaii.sqlite database to determine temperature trends for both June and December. By querying for this data, converting it to a list, and then using Pandas to build and describe a dataframe, I've gathered actionable insigts into the temperature trends.

## Results

### June Temperatures
---
![June Temps](https://github.com/PGrickswim/surfs_up/blob/main/Resources/June.png)
- There are 1,700 observations from the dataset that occur during the month of June.
- Temperatures are very consistent, with a Standard deviation of only 3.26 degrees
    - The minimum temperature is 64 degrees
    - The maximum temperature is 85 degrees
    - 50% of the observations fall within a four degree range: 73 - 77 degrees, with the median at 75 degrees.

### December Temperatures
---
![December Temps](https://github.com/PGrickswim/surfs_up/blob/main/Resources/December.png)
- There are 1,517 observations from the dataset that occur during the month of December.
- Temperatures are less consistent than June, but still very consistent. December has a Standard deviation of only 3.75 degrees
    - The minimum temperature is 53 degrees, 11 degrees cooler than June.
    - The maximum temperature is 83 degrees, 2 degrees cooler than June.
    - 50% of the observations fall within a four degree range: 69-74 degrees, with the median at 71 degrees.

## Summary
The results show that overall, the weather is very consistent as far as temparatures go, regardless of the season. While the temparatures are never extremely warm, they also are rarely very cold. With the median temperature of 75 in June and 71 in December, some surfers may be unlikely to feel the need to cool off with ice cream. I suggest there are other food offerings made available at the shack, in addition to ice cream, for surfers who work up an appetite on the waves.

### Further Exploration
To dig deeper into the data that could support weather information, I suggest two additional queries:

1. Query frequency of precipitation in each month. This data will help us understand how often fair weather is observed.
2. Dig in to observations based on the station. Pinpointing the best place to build the shack and operate the business will be crucia.

I hope this information gives you the necessary detail and confidence to move forward with the business. Have fun!