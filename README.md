## Citibike Data Cleaning for Tableau Analysis

Reducing CitiBike data for use in Tableau COVID impact assessment

This repo holds the processing files for reducing and merging data for multiple months to be used in Tableau.

### Summary
The project pulled 2 years of data from CityBike, much of which was not useful for our analysis, so data was condensed into months by counts of rides and total minutes (rather than individual rides and individual ride minutes). Additionally, we were not interested in rider demographics and focuses station "popularity" on the most used Starting Station, rather than ending station. Once data was organized in Python (in Jupyter Notebook), it was exported as a csv for use in Tableau.

The Tableau Notebook looks at Station Popularity, Ride Count and the impact of Station Expansion during Covid. Some slides are below, and full description/all slides can be found via the Tableau Public link below.

![Screen Shot 2023-09-18 at 8 48 12 PM](https://github.com/mtolan2023/citibike_preprocessing/assets/123139216/dba22ad9-540b-4a19-a0eb-a69affb4aa5b)
![Screen Shot 2023-09-18 at 8 48 45 PM](https://github.com/mtolan2023/citibike_preprocessing/assets/123139216/fc4aa66d-89ab-420a-bcd0-083b25b457b3)
![Screen Shot 2023-09-18 at 8 49 10 PM](https://github.com/mtolan2023/citibike_preprocessing/assets/123139216/58b67fd3-14e8-4fc6-9648-8ec7ab5a4383)
![Screen Shot 2023-09-18 at 8 49 36 PM](https://github.com/mtolan2023/citibike_preprocessing/assets/123139216/d5a36f6f-e59a-4a02-9106-16e9639e3328)


### Link to Tableau Project:
https://public.tableau.com/views/CitiBikeCOVIDImpact/PandemicimpactonCitiBike2020?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

Link to CitiBike Data Source:
https://citibikenyc.com/system-data
