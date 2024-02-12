# GroupAssignment1: Project Proposal
**Group Member**: Alain Jabbour, Simon Han, Tomohiro Ujikawa, Xinyi Cao  
**Group Repository**: https://github.com/tomo-ujikawa/up221-group.git

## Research Topic
- What are the population characteristics of transit corridor households vs transit desert households in LA County?
- In LA County, which areas have the greatest need and potential for transit development?

## Why This Matters
The Los Angeles Metropolitan Area is the second most populous metropolitan area in the United States. With the growing need to reduce greenhouse gas emissions and to implement sustainable solutions, the pressure to develop a public transportation network has never been greater. While public investment budgets are limited due to austerity policies, these infrastructure developments need significant investment, prioritization, and political decision-making. We believe that analyzing the characteristics of existing rail and BRT transit corridor areas and other areas with high potential and need for public transit development is essential for its future planning.  
One framework for planning the future of public transportation is the concept of transit desert. Transit deserts are areas where public transportation supply is notably lower than transit service demand. Transit deserts, or the gap between demand and supply, is often the result of the inequitable distribution of resources and services, and Public transit that is distributed fairly is an important component of an equitable society. We analyze transit deserts in LA by comparing the supply of transit to the demand for transit and examine the potential for future planning to contribute to an equitable society.  

## Spatial Scope
**LA County**:  The biggest transit agency in the LA Metropolitan Area is LA Metro, which operates within the boundaries of LA county. Our analysis will hence focus on Metro transit services with LA County as the scope for our study. Even within a single county, LA County, each neighborhood's social composition and built environment characteristics are diverse. Prioritization is necessary when considering the development of transportation infrastructure, and analysis of geographical distribution and characteristics of population and built environment is essential in developing transportation infrastructure plans. Since the planning for the transportation infrastructure was created over several decades ago, it is not only crucial to understand current ridership patterns, but also critical to predict future ridership needs. Although forecasting the future is not within the scope of our research, we believe that understanding past change patterns over time will reveal spatial patterns that hold true to this day. 

## Intended Analysis and Visualizations
The first step in identifying transit deserts is to determine the demand for transit. In prior studies, ten demographic factors have been considered as measures of transit dependence. One arm consists of items related to income and social class, such as household income, car ownership, employment, and emigration status, another one is related to mobility need and ability, such as age, transit use and disability. In this project, we analyze the indicators of greater importance and data availability: household income, car ownership, age, and public transportation use.  
Previous transit desert studies have defined transit supply by factors such as the number of bus stops, weekday bus arrivals, number of routes, the total length of sidewalks, bike routes, presence of low-speed limit roads, and finally the density of intersections. While this is not a comprehensive approach as it captures only one aspect of transit, due to limited time and data, we have chosen to evaluate transit supply by the distribution of the rail network in this project.  
We use the previous literature to define a transit corridor as an area 0.5 miles from a metro rail station, and examine the spatial distribution of transit supply and compare transit corridor and non-transit corridor areas to identify spatial disparities in transit supply. The spatial distribution of transit demand is examined using census tract data for the items mentioned on the previous slide. Based on the results of these comparative studies, we will identify transit deserts and propose a transit network for the future.
![alt text](https://github.com/tomo-ujikawa/up221-group/blob/main/images/Midterm_TransitCorridor.png)

## Data Sources
We use the age distribution, car ownership, median income, household size, and household percentage without vehicles from these data source titled [US Census Bureau](https://data.census.gov/table?d=ACS%205-Year%20Estimates%20Subject%20Tables), [IPUMS](https://usa.ipums.org/usa-action/variables/TRANWORK#description_section), and [GeoHub](https://geohub.lacity.org/).  
We will use the geo data of boundaries of census tracts and city from these data sources of [US Census tracts](https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2022&layergroup=Census+Tracts) and [LA City](https://egis-lacounty.hub.arcgis.com/datasets/lacounty::city-boundaries-lines/about).  
We will use the railway station data from [LA Metro](https://developer.metro.net/gis-data/).

## Conclusion
By visualizing the social and demographic characteristics and geographic distribution of transit corridors and transit desert within LA County, we expect to be able to identify the development needs and feasible areas for TOD in LA.
