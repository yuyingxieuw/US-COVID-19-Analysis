US Covid-19 Data Visulalization 

## Project Introduction 
This project aimed at mapping covid cases on the county level in the United States in 2020. The first covid case emerged in king county Washington State in January 2020,  and until now, it has killed [at least 1,111,485](https://www.cnn.com/interactive/2020/health/coronavirus-us-maps-and-cases/) people and infected about 102.6 million in the United States, according to the data by Johns Hopkins University. And therefore, tracking Covid-19 cases is relatively important in understanding its spreading features and putting forward coping strategies accordingly. Particularly, the spatial feature of Covid cases and rates are significant, through which we can explore why certain places have more cases or higher rates and what factors lead to a certain kind of spatial pattern. Thus, this project tries to visualize spatial data of Covid-19 rates and cases in the United States in 2020 by the county to show the spatial pattern to help better trace the spreading of the pandemic. 

## Mapping Result
1. The first one is a choropleth map showing Covid-19 rates (cases/population) in each county in December 2020. We use the [Mapbox Light v10](https://www.mapbox.com/maps/light) as the basemap. The U.S. county boundary shapefile was collected from the [U.S. Census Bureau](https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html); The Covid-19 case data was downloaded from [The New York Times](https://github.com/nytimes/covid-19-data/blob/43d32dde2f87bd4dafbb7d23f5d9e878124018b8/live/us-counties.csv). And the population data used for calculating the case rates are from the [2018 ACS 5 year estimates](https://data.census.gov/table?g=0100000US$050000&d=ACS+5-Year+Estimates+Data+Profiles&tid=ACSDP5Y2018.DP05&hidePreview=true). 

**Open the [map]() and click each polygon to see the specific data!**
![Covid-19 Rates by County](https://github.com/yuyingxieuw/US-COVID-19-Analysis/blob/main/img/Lab3map1.png)
<img scr="https://github.com/yuyingxieuw/US-COVID-19-Analysis/blob/main/img/Lab3map1.png" width="70%" height="70%">

2. The second one is a dot density map showing covid-19 cases by county in the U.S. in December 2020. We use the [Mapbax Dark v10](https://www.mapbox.com/maps/dark) as the basemap. The U.S. county boundary shapefile was collected from the [U.S. Census Bureau](https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html); The Covid-19 case data was downloaded from [The New York Times](https://github.com/nytimes/covid-19-data/blob/43d32dde2f87bd4dafbb7d23f5d9e878124018b8/live/us-counties.csv).

**Open the [map]() and click each dot to see the specific data!**
![Covid-19 Cases by County](https://github.com/yuyingxieuw/US-COVID-19-Analysis/blob/main/img/lab3map2.png)
<img scr="https://github.com/yuyingxieuw/US-COVID-19-Analysis/blob/main/img/lab3map2.png" width="70%" height="70%">

## Acknowledgement
Thank you for Steven's help in completing this project!
