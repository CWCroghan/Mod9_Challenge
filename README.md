# Business Proposal
## Overview:
<p>Oahu, Hawaii is the perfect location for a new Surf and Ice Cream Shack.  The weather is ideal, and nothing is better than a day surfing followed by some excellent ice cream.   To demonstrate the ideal weather conditions in Oahu, Hawaii, statistical analysis of temperature data from various weather stations in the vicinity will be calculated for the two extreme months: June and December. </p>

<p>An SQLite (a self-contained database engine) database containing weather data from 2010-01-01 to 2017-08-23 collected at nine weather stations around the island of Oahu was provided.  The database contained two datasets: Measurements and Stations.  The Measurements had a total of 19,550 observations and two weather measurements: temperature and precipitation.</p>

<p>The analysis that will be discussed concerns only the temperature measurements.</p>

## Results:

<p>Univariate statistics were calculated for the month of June and December for all the years that the data were collected.</p>

![June Temps](https://github.com/CWCroghan/Mod9_Challenge/blob/main/JuneTemps.png)

![December Temps](https://github.com/CWCroghan/Mod9_Challenge/blob/main/DecTemps.png)

<p>Here are some observations about the statistics:</p>
<ul>
<li>The mean for December, 71, is lower than that of June, 75.</li>
<li>The minimum for December, 56, is lower than that of June, 64.</li>
<li>The standard deviation for December 3.75 is higher than that of June 3.26.</li>
</ul> 

<p>The median and mean for both time periods are close to each other (June: mean 75, median 75; December: mean 71, median 71), indicating that neither time period is skewed.  This indicates that parameteric statistical analysis would be appropriate for these data.</p>

## Summary: 

<p>One of the primary findings of the analysis shows that the data distribution is different during the two time periods.  December temperatures are more variable.  These two histograms demonstrate this point.</p>

![June Temps Histogram](https://github.com/CWCroghan/Mod9_Challenge/blob/main/JuneHistogram.png)

![December Temps Histogram](https://github.com/CWCroghan/Mod9_Challenge/blob/main/DecHistogram.png)

<p>Although the mean temperatures differ for the two time periods, there is no indication that these differences are statistically significant or even consequentially different.  A more considerable concern may be the number of days that will have ideal surfing conditions.  According to House of Surf (https://houseofsurf.co/), temperatures in the range of 75 – 82 are ideal for surfing.</p>

<p>Querying the database, we find that 229 out of 240 days (95%) are in the ideal range for June.  Whereas in December, only 105 out of 217 days (48%) are in the ideal range.  </p>

<p>This demonstrates that while there will be ideal surfing weather in December, it is still possible that the surf and ice cream business might have less business during winter.</p>
