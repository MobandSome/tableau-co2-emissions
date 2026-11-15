# CO2 Emissions Per Capita — Tableau Public

An interactive world map of CO2 emissions per capita (metric tons) by country, built in Tableau Public.

**[View the live dashboard on Tableau Public](https://public.tableau.com/views/CO2EmissionsPerCapita_17947104680000/Sheet1)**

## What it shows

- A filled map of every country, colored by CO2 emissions per capita
- A stepped red-green diverging palette (5 steps, reversed): green = low emissions, red = high emissions, fixed to a 0–62 metric-ton scale so years are comparable
- A single-year dropdown filter (1960–2011) to see how each country's emissions change over time

## Data

Four World Bank–style datasets, linked in Tableau on **Year** and **Country**:

| Table | Key fields |
|---|---|
| CO2 Data Cleaned | Country Name, Country Code, Region, Year, CO2 (kt), CO2 Per Capita |
| Energy | Country, Year, Energy use (kg of oil equivalent per capita) |
| GDP total | Country, Year, Current GDP |
| Total Population | Country, Year, Population Total |

## Skills demonstrated

- Combining multiple data sources with Tableau relationships (multi-field: year + country)
- Fixing type mismatches between keys across tables
- Geographic visualization with custom diverging color scales
- Interactive filtering for time-series exploration
