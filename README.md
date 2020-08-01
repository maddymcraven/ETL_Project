# ETL_Project

Extract
- Extract data from Census API on poverty
- Extract COVID-19 data: https://www.kaggle.com/imdevskp/corona-virus-report/data?select=usa_county_wise.csv 

Transform
- Cleaning data sources to only relevant data (most current COVID data)
- Making FIPS common type on both datasources
- Merge with pandas on FIPS

Load
- Load to a SQL DB
- Final table covid_census


