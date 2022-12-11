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


## Summary:

### Major conclusions

* Max temperature:
June highest temperature: 85.00 °F 
December highest temperature: 83.00 °F

The difference between the hightest temperature for each month based on its hystorical data was only of 2°F being June warmer than December. This shows there is not much perceived difference between the hotest days of both months. 

* Min temperature:
June lowest temperature: 64.00 °F 
December lowest temperature: 56.00 °F

As shown above the lowest tempertaure shows the biggest difference for the assessed months with a delta of 8 °F. This is important business information 

* Average temperature:
June average temperature: 75.00 °F 
December average temperature: 71.00 °F

There is a high-level summary of the results and there are two additional queries to perform to gather more weather data for June and December. (5 pt)

### Other analysis

![Other_analysis](https://github.com/Li11iana/surfs_up/blob/main/Resources/Other_analysis.png)

![April_temperature_stats](https://github.com/Li11iana/surfs_up/blob/main/Resources/April_temperature_stats.png)


![Aug_temperature_stats](https://github.com/Li11iana/surfs_up/blob/main/Resources/Aug_temperature_stats.png)
