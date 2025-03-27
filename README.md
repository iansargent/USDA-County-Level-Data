# USDA-County-Level-Data (2023)

## Project Overview
This project uses R and SQL to extract, clean, and query data from the USDA Economic Research Service database. The final dataset contains three tables covering employment, poverty, and population at the county level. The analysis highlights economic and demographic trends across U.S. counties.

### Skills Developed

*Data Cleaning using* ***R***
* Manipulation using the dplyr package
* Table joins
* Handling missing values

*Database Querying using* ***SQLite***
* Basic SELECT and FROM statements
* Filtering using WHERE
* Table joins
* Relational algebra

### Original Datasets
[County-level Data Sets](https://www.ers.usda.gov/data-products/county-level-data-sets/county-level-data-sets-download-data)

### Final Tables in Database
1. **Population**(State, County, Census_Pop_2020, Population_Estimate_2023, Births_2023, Deaths_2023)
2. **Employment**(State, County, Civ_Labor_Force_2023, Med_Household_Income, Unemployment_Rate_2023)
3. **Poverty**(State, County, Poverty_All_Ages_2023, Poverty_Pct_All_Ages_2023, Poverty_0to17_2023, Rural_Urban_Code_2023)

**Note**: Connecticut regions are excluded in the Employment table due to data reporting inconsistencies.


