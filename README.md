# Diurnal Rates of Winter Precipitation

### Description:

This project looks at ASOS station data across the Northeastern United States, specifically the six New England States plus New York. Date, time, precipitation amount and present weather codes are used to determine rates of precipitation in millimeters per hour (when precipitation occurs) over the winter season. 


### Dependencies:

* astral
* cartopy.crs
* cartopy.feature
* datetime
* matplotlib.pyplot
* numpy
* pandas
* pytz
* scipy.stats


### Executing program

* Once appropriate station data is downloaded, import data to file and run.
* Files with prefix 'yearly' include all winter weather precipitation at that location.
* Files with prefix 'snow' only include winter snow amounts at that location.
* Cumulative and SnowCumulative show all station data for all precipitation and snow only precipitation respectively.
* SOCumulative and PrecipCumulative combine exported CSV files from individual notebooks, to create one large dataframe of all states. CSV files are available within the SO Cumulative and Precip Cumulative folders.


#### Author:

Aly Hall
[alissah3@illinois.edu]
