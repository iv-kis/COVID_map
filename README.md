# COVID_map
The map of Portugal, representing the density of active cases (red points) and recovered patients (blue points) per administrative unit.  Brings better perception of how many people were affected with covid, and how likely you are to encounter an active case.

**STRUCTURE**
- concelhos-shapefile - a folder with geospatial shapefile  
- covid_data.csv - a datasource file for the script  
- Covid_geo.ipynb - the script for building the map  

**DATA**  
**(1) covid_data.csv**  
Data per Concelho (as of the end of Jan 2021): 
- Population
- Number of active cases (calculated as new cases in last 14 days)
- Number of recoveries

Although the absolute numbers of active and recovered cases are rough estimates, they follow the real proportion, which is of first interest in this visualization.

*Sources:  
https://www.pordata.pt  
https://github.com/dssg-pt/covid19pt-data*

Thanks to José Miguel Rodrigues Quintas for scraping and cooking the COVID data.  
*https://github.com/josemrquintas*  
Thanks to Filipe G. Coelho for the idea of colour design.  
*https://github.com/FilipeGCoelho/*

**(2) Portugal shapefile**  
*https://dados.gov.pt/pt/datasets/concelhos-de-portugal/*



