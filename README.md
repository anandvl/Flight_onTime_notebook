# Flight_onTime_notebook
Experiments with combining data from different sources and with interactive plots

### Analysis of flight delays and taxiing times and its relationship to the local weather for Jan 2018

In this notebook, I am experimenting with combining data from different sources to find correlations between relevant parameters and experimenting with creating interactive plots using Bokeh.  The data and the correponding data sources used in this analysis are

* Flight details are obtained from [On-Time Flight performance database](https://www.transtats.bts.gov/DL_SelectFields.asp?DB_Short_Name=On-Time&Table_ID=236)
* Airline details are obtained from [Carrier Decode Table](https://www.transtats.bts.gov/Tables.asp?DB_ID=595&DB_Name=Aviation%20Support%20Tables&DB_Short_Name=Aviation%20Support%20Tables#)
* Airport information (including precise location) is obtained from [Master Coordinate Table](https://www.transtats.bts.gov/Tables.asp?DB_ID=595&DB_Name=Aviation%20Support%20Tables&DB_Short_Name=Aviation%20Support%20Tables#)
* Daily average weather conditions are obtained from [National Climatic Data Center (NCDC)](ftp://ftp.ncdc.noaa.gov/pub/data/gsod)
* Information (including precise location) about weather stations are obtained  from [Station list](ftp://ftp.ncdc.noaa.gov/pub/data/noaa/isd-history.txt)

All data presented here only correspond to airports within the US for the month of January 2018.  Data for other time periods (month, year) are availabe at the sites mentioned above.  Similar analysis could be applied to those other time periods by downloading the appropriate data sets.  But, that is beyond the scope of this analysis.

#### (For now, I am not including any weather related plots. These will be added later along with other plots and analysis).

You can view this notebook at [nbviewer](https://nbviewer.jupyter.org/github/anandvl/Flight_onTime_notebook/blob/master/Flight_onTime.ipynb) and if you wish to experiment with the code, you can execute it on mybinder from [nbviewer](https://nbviewer.jupyter.org/github/anandvl/Flight_onTime_notebook/blob/master/Flight_onTime.ipynb), OR you can directly execute it on mybinder [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/anandvl/Flight_onTime_notebook/master?filepath=Flight_onTime.ipynb)

[github.com's notebook viewer](https://github.com/anandvl/Flight_onTime_notebook/blob/master/Flight_onTime.ipynb) also works to view this notebook, but it is supposed to be slower.
