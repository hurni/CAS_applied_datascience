General File Information

- Download from: https://www.ecdc.europa.eu/en/publications-data/download-todays-data-geographic-distribution-covid-19-cases-worldwide 
- Date of download and file creation: 2020-10-09
- File format: .CSV
- Rows: dateRep, day, month, year, cases, deaths, countriesAndTerritories, geoId, countryterritoryCode, popData2019, continentExp, Cumulative_number_for_14_days_of_COVID-19_cases_per_100000


Methodological Information

- "day", "month", "year" were dropped since information also available in "dateRep"
- Data was split into 10 different data frames by the following "countryterritoryCode": "United_States_of_America", "China", "Japan", "Germany", "India", "United_Kingdom", "France", "Italy", "Brazil", "Canada"
- data frames were reindexed with a date-time index for the period of 2019-10-01 to 2020-09-30
- NaN were treated as 0s using the bfill method of pandas
	- Exception: China needs manual setting of "cases" at date "2019-12-30" to 0 in order for bfill to work properly
- More detailled information regarding methodology can be found in the Jupyter notebooks in the corresponding github repository.
 	



