### Effect of Lockdown on levels of Air Pollutants in 2020




**Data dictionary (Air Quality):**\
**-DATE**: date the readings were recorded starting January 1 through December 31 each year\
**-Source**: source of the data. The primary source of all the data included in this projec is the Air Quality Systems (AQS)
**-SITE ID**: ID number of the monitoring station\
**-SITE NAME**: name of the monitoring site\
**-POC (Parameter Occurrence Code)**: ID number of the monitoring device when there's more than one device measuring the same pollutant\
**-Daily Max 8-hour Concentration**: maximum 8-hour average concentration of pollutant out of 24 reading periods/day (e.g. 00:00–07:59, 01:00–08:59 etc) and is specific to measuring Carbon Monoxide (CO). An 8-hour average is considered valid if at least 75% of the hourly averages (17/24 reading periods/day) for the 8-hour average are available.\
**-Daily Max 1-hour concentration**: maximum 1-hour concentration of pollutant out of hourly reading/day. This metric is specific for nitrogen dioxide (NO2) and gground-level ozone (O3).\
**-Daily Mean Concentration**: average daily concentration of pollutant. This metric is specific for particulate-matter 2.5 (PM2.5) and 10 (PM10)
**-Units**: the units for the displayed pollutant concentration.\
**-DAILY_AQI_VALUE**: daily average air quality index.\
**-DAILY_OBS_COUNT**: number of observations per day (max 24 observations)\
**-PERCENT_COMPLETE**: percentage of daily observations collected (a minimum of 75% is required)\
**-AQS_PARAMETER_CODE**: AQS database ID code for pollutants and meteology measuements (e.g. wind speed).\
**-AQS_PARAMETER_DESC**: AQS database description of the parameter.\
**-CBSA_CODE**: ID code for the Core-Based Statistical Areas (CBSAs). These areas are defined as areas based around an urban center of > 10,000 people and adjacent areas.\
**-CBSA_NAME**: name of the Core-Based Statistical Areas (CBSAs).\
**-State_Code**: Federal Information Processing Standards (FIPS) ID code for a state.\
**-State**: state name.\
**-County_Code**: FIPS ID code for a county.\
**-County**: county name./
**-SITE_LATITUDE**\
**-SITE_LONGITUDE**

Data source: https://www.epa.gov/outdoor-air-quality-data/download-daily-data


**Data dictionary (California state COVID-19 cases/deaths/tests):**\
**-date**: date of recoding data starting Feburary 1, 2020 through Feburary 17, 2022\
**-area**: area name.\
**-area_type**: type of area (county)\
**-population**: number of population in that area\
**-cases**:  number of of reported new cases on that day\
**-cumulative_cases**: number of total cases up to that day\
**-deaths**: number of reported new deaths on that day\
**-comulative_deaths**: number of reported total COVID-19 deaths up until that day\
**-total_tests**: number of reported new COVID-19 tests that were performed on that day\
**-commulative_total_tests**: number of total COVID-19 tests that were performed up to that day\
**-positive_tests**: reported COVID-19 positive resulsts on that day\
**-commulative_positive_tests**: total number of COVID-19 positive tests up until that day
**-positive_tests**: reported COVID-19 positive resulsts on that day\
**-commulative_positive_tests**: total number of COVID-19 positive tests up until that day\

Data source: https://data.ca.gov/dataset/covid-19-time-series-metrics-by-county-and-state1
