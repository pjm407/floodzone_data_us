## R Code - Wrangling Floodzone Data from NYU Furman Center

### Source: http://floodzonedata.us/

Furman provides housing and floodzone data sourced from the National Housing Preservation Database (2016 sample), U.S. Census Bureau (2010 decennial Census data and American Community Survey 2011-2015 5-year estimates), and the U.S. Federal Emergency Management Agency (2016 National Flood Hazard Layer data). Exact methodology can be found here: https://furmancenter.org/floodzonedata/data/methodology.

This repository provides R code on how to reshape the New York data from wide to long. Because the column names vary by length, it is recommended to create subsets of the main dataset by subject (e.g., population, race and ethnicity, building type, tenure, etc.) before joining.  

Code is provided for reshaping both county- and tract- level data. One advantage of using the tract-level data is the ability to identify "500-Year" floodzones through filtering.  
