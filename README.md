# surfs_up
Finding Best Weather for Surfing Using SQLite and SQLAlchemy

## Purpose

To analyze and compare weather temperature trends of Oahu for June and December and determine if a surf and ice cream shop business is sustainable year round.

## Results

![JuneTemps](https://github.com/DavidFGitH/surfs_up/blob/main/Resources/June_Temps.png)

![DecTemps](https://github.com/DavidFGitH/surfs_up/blob/main/Resources/December_Temps.png)

- The first thing that stands out is that the mean of the December temperatures are approximately 3.9 degrees lower than the mean of June temperatures. The lower temperatures are relatively consistent across the range of both months, with minimum of December being 8 degrees lower and the median being 4 degrees lower than the minimum and median temperature of June.

- Interestingly enough, the standard deviation of the temperature in December is also larger than the standard deviation of temperatures in June, which means there was a larger, more disparate range of temperatures in December than there were in June. Looking at the interquartile range of temperatures we get 4 degrees in June and 5 degrees in December. The difference between the minimums and maximums are even more disparate, with June being 21 degrees and December being 27 degrees.

- Even with the large difference at the lower ranges of temperatures for December and June, the temperatures at the higher ranges of temperatures are surprisingly close, with 75th quartile range difference being 3 degrees and the maximum temperature difference being 2 degrees. On a surface level, it seems that the data skews left for December while temperatures are more consistent for June.

## Summary

The biggest takeaway is that while temperatures are generally lower in December, on the higher end they still get closer to the higher temperatures in June, but when the days get colder, the temperatures in December get a lot colder than they do in June. Depending on when things get a lot colder and how quickly, a surf and ice cream shop could still be sustainable since the hotter temperatures in December could support it. In order to investigate further, we could look at the temperatures of June and December at peak hours to determine how demand would be affected in peak hours. In addition, we could find the temperatures of morning and evening to see how long the store could stay open at peak hours in December before the colder temperature of night comes. Finding the maximum temperatures for every day as query could help as well.
