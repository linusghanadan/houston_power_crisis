# Spatial Analysis of 2021 Houston Power Crisis
## Background
In February 2021, Texas faced an unprecedented power crisis that left millions without electricity as a result of three winter storms (Ramsey, 2021). Struggling to meet the extraordinary demand for heating amid freezing temperatures, the Electric Reliability Council of Texas (ERCOT) implemented widespread blackouts to prevent a total grid collapse. In addition to exposing the vulnerabilities of Texas’s energy infrastructure, the crisis also prompted a nationwide discussion on the resilience of power grids in the face of extreme weather events.

## Purpose
This analysis will look at where residential blackouts occurred during February 2021 in the Houston area. After mapping the blackout data onto census tracts, I’ll look at the median income of the census tracts that were affected by residential blackouts compared to those that were not affected.

## Repository Structure
    houston_power_crisis
    │   README.md
    │   .gitignore
    │   .Rmd
    │   .Rproj   

## Datasets
1. Blackout TIF files
2. Highway locations GeoPackage
3. House locations GeoPackage
4. Income data GeoDataBase

## Data References
1. National Aeronautics and Space Administration (NASA). 2022. "Level-1 and Atmospheric Archive & Distribution System Distributed Active Archive Center (LAADS DAAC)". https://ladsweb.modaps.eosdis.nasa.gov/
2. GeoFabrik. 2022. "OpenStreetMap Data Extracts". https://download.geofabrik.de/
3. GeoFabrik. 2022. "OpenStreetMap Data Extracts". https://download.geofabrik.de/
4. U.S. Census Bureau. 2019. "American Community Survey". https://www.census.gov/programs-surveys/acs

## Notes on Data Access
Data used in this analysis was stored locally and included in repositiory .gitignore file. Use data references to access the original data.
