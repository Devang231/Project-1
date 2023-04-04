## Project title: Optimizing Solar Development in Southwest US

## Team Members: 
* Tanner Amman
* Henry Luken
* Devang Patel
* Adina Raizen

## Project description/outline

Using multiple data sources, we will determine the best locations in the southwest US to build more solar panel infrastructure.

## Main question

Where are the best places to install solar panels in the southwest US?

## Considerations: 
* Cost
* Population
* Energy usage
* Terrain
* Solar radiation
* Weather
* Size (area of panels)

## Data sources: 
* https://www.eia.gov/opendata/browser/electricity (Henry)
* https://www.census.gov/data.html (group)
* https://openweathermap.org/api (Adina)
* https://rapidapi.com/solcast/api/solcast/ (Devang)
* https://developer.nrel.gov/docs/solar/ (Tanner)
  
## Breakdown of tasks:
  1. Importing data from APIs and creating dataframes
  2. Assign considerations - based on assigned APIs
  3. Merge dataframes (group task)
  4. Create regressions from historical data to predict current/future data
  
## Other notes:
* Determine time frame for data (5-year historical data across all APIs - range TBD)
* Geographical range: CO, AZ, UT, NM
* Use zip code for locations
* Types of visualizations
  * Heat map
  * Scatterplots (for regressions)
  * Energy cost by energy source (line graph)
  * Bar graph (comparison of cost for different energy types)
  
## 3/30/23 Updates
 * Narrowing the scope to just CO - by county (62 counties)
 * Weather data from VisualCrossing (temp, cloud cover, solar radiation, solar energy) - 1000 requests per day per person
   * Everyone will get an API key to start pulling historical data
   * Adina will build the query - everyone will share API keys with Adina to pull the data
 * Other data we will look at:
   * Census data (comparing types of energy used (% solar), population)
   * Locations of solar farms currently (eia.gov)
 * Current questions:
   * Where is optimal to build more solar infrastructure?
   * Are current solar farms optimally placed?
   * Where to market to individuals installing solar panels?
 * After pulling data, each person will investigate different weather metrics
 * Goal: Gather majority of data before 4/3
 * Goal: By Wednesday, start on PPT

## 4/3/23 Updates
 * Need to calculate a linear regression to determine estimates for census data beyond 2020 (Tanner)
 * Need to figure out how to plot a map with county lines (ref: https://melaniesoek0120.medium.com/data-visualization-how-to-plot-a-map-with-geopandas-in-python-73b10dcd4b4b)
 * Heat maps of solar/weather data (Henry)
 * Need to create final dataframe of census data with weather data (3-year averages by county) and county data (Adina)
 * Need to gather data on where solar farms exist in CO already (Devang)
