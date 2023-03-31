## Project title: Optimizing Solar Development in Southwest US
#test comment
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
  
