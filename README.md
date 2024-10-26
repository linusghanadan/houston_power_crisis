## Using NASA Data to analyze Residential Blackouts during Houston Power Crisis

### [Link to Blog (includes R code, code output, and written analysis)](https://linusghanadan.github.io/blog/2024-1-20-post/)

### Repository Structure
    houston_power_crisis
    └───images
        │   Side-by-side histograms of income distribution in census tracts: income-distribution.png
        │   Map showing median income and residential blackout status of census tract: income-map.png
        │   Map of census tracts with residential blackouts: residential-blackout-map.png
    │   README.md
    │   .gitignore
    │   .Rmd
    │   .Rproj   

### Context

This project was completed for my Geospatial Analysis & Remote Sensing class, taken as part of my Master's program at UC Santa Barbara. Provided with data and questions, I carried out this analysis using appropriate geospatial modeling techniques.

### Question

During the 2021 Houston Power Crisis, in which census tracts did residential blackouts occur, and how did this relate to a census tract's median income?

### Analysis Summary

Used data from NASA's VIIRS instrument to conduct a spatial analysis of the 2021 Houston Power Crisis. Determined and visualized census tracts in the Houston metropolitan area where residential blackouts occurred and analyzed how this related to median income of census tracts.

### Datasets
1. Blackout TIF files
2. Highway locations GeoPackage
3. House locations GeoPackage
4. Income data GeoDataBase

### Data References
1. National Aeronautics and Space Administration (NASA). 2022. "Level-1 and Atmospheric Archive & Distribution System Distributed Active Archive Center (LAADS DAAC)". https://ladsweb.modaps.eosdis.nasa.gov/
2. GeoFabrik. 2022. "OpenStreetMap Data Extracts". https://download.geofabrik.de/
3. GeoFabrik. 2022. "OpenStreetMap Data Extracts". https://download.geofabrik.de/
4. U.S. Census Bureau. 2019. "American Community Survey". https://www.census.gov/programs-surveys/acs

### Notes on Data Access
Data used in this analysis was stored locally and included in repositiory .gitignore file. Use data references to access the original data.
