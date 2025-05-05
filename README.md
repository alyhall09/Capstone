# Diurnal Rates of Winter Precipitation

### Description:

This project looks at ASOS station data across the Northeastern United States, specifically the six New England States and New York. Date, time, precipitation amount and present weather codes are used to determine rates of precipitation in millimeters per hour (when precipitation occurs) over the winter season. 


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
* Files with prefix 'snow' only include snow amounts at that location.
* Cumulative and SnowCumulative show annual rates per station for all precipitation and snowfall respectively.
* PrecipCumulative and SOCumulative combine exported CSV files from individual notebooks, to create one large dataframe of all states. CSV files are available within the Precip Cumulative and SO Cumulative folders.


#### Author:

Aly Hall
[alissah3@illinois.edu]
