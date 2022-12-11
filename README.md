# Temperature Trend Analysis for Oahu, Hawaii.

## Overview
Using Python and SQLAlchemy the hawaii.sqlite database is analyzed. This database contains Oahu's weather data, and allows us to determined if there are any major temperature considerations for business purposes.

### Objective:
Retrieve and compare the statistics for Oahu's temperature for the months of June and December to determine if there is potential impact to the surf and ice cream shop sustainability.


## Results:
All data entries for both the month of June and December were retrived from the database using SQLAlchemy and stored in Python Pandas Dataframes for further evaluation. The statistical description for each month's temperatures is shown below: 

### June Temperature Statistics

![June_temperature_stats](https://github.com/Li11iana/surfs_up/blob/main/Resources/June_temperature_stats.png)

* A total of 1700 data entries were used for this analysis. It determined that the average temperature is 74.94 °F, while the lowest and hightest temperatures for the month of June were 64.00 °F and 85.00 °F respectively.

### December Temperature Statistics

![Dec_temperature_stats](https://github.com/Li11iana/surfs_up/blob/main/Resources/Dec_temperature_stats.png)

* A total of 1517 data entries were used for this analysis. It determined that the average temperature is 71.04 °F, while the lowest and hightest temperatures for the month of December were 56.00 °F and 83.00 °F respectively.

## Information Sources

* Weather doesn’t affect ice cream consumption by Valerie Vande Panne. 2013. Retrieved fromhttps://news.harvard.edu/gazette/story/2013/07/weather-doesnt-affect-ice-cream-consumption/

* The Ultimate Wetsuit Thickness Guide. 2022. Retrieved from https://quiksilver.com/expert-guide/surf/buying/how-to-choose-wetsuit-thickness.html

* Fresh Essays. (September 2022). Correlation Between Ice-Cream Sales and Temperature. Retrieved from https://samples.freshessays.com/correlation-between-ice-cream-sales-and-temperature.html

## Summary:

* Max temperature:
June highest temperature: 85.00°F 
December highest temperature: 83.00°F

The difference between the hightest temperature for each month based on its hystorical data was only of 2°F being June warmer than December. This shows there is not much perceived difference between the hotest days of both months. 

* Min temperature:
June lowest temperature: 64.00°F 
December lowest temperature: 56.00°F

As shown above the lowest tempertaure shows the biggest difference for the assessed months with a delta of 8°F. This is important business information since days with unusually colder weather can tend to affect all in-person sales. Additionally a difference of almost 10°F indicates that thicker wetsuits and extra accesories are needed to practice surf.
The shop should prepare for a decrease in ice cream sales during those colder days, on the other hand specialty surf equipment should be stocked such as sealed and taped full wetsuits, booties and gloves.

* Average temperature:
June average temperature: 75.00°F 
December average temperature: 71.00°F

The average temperature remains pleasent during both months, following the same pattern until now, warmer on June and colder in December with a delta of 4.00°F.
We can conclude from this average temperature data that the business activities we are interested in: ice cream sales and surfing can be expected to go year round without great differences however a close follow up on the weekly weather would prepare the business to any unusually cold or hot day.


### Other analysis

We analyzed the temperature data for June and December specifically to contrast two climate patterns. However having the database available we can determine in which months have the lowest and highest temperatures occured. The query and the data entries answering that question can be seen below:

![Other_analysis](https://github.com/Li11iana/surfs_up/blob/main/Resources/Other_analysis.png)

Max temperature recorded: 2010-08-23, 87.0°F 
Minimum temperature recorded:2013-04-02', 53.0°F 
Based on these information we can further evaluate the temperature patterns for the month with the hystorical highest and lowest temperature. The statistical review of the temperature for August (highest temperature recorded 87.0°F) and April (lowest temperature recorded 53.0°F).

![April_temperature_stats](https://github.com/Li11iana/surfs_up/blob/main/Resources/April_temperature_stats.png)


![Aug_temperature_stats](https://github.com/Li11iana/surfs_up/blob/main/Resources/Aug_temperature_stats.png)
