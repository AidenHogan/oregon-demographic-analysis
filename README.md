# Oregon Demographic & Economic Analysis (2020-2024)
An analysis of 5-year PUMS census data exploring income distribution, commute impacts, and demographic shifts in Oregon.


### Viewing The Project
[View the interactive web report here](https://aidenhogan.github.io/oregon-demographic-analysis/)

If you prefer a static version, download the `pums-analysis.pdf` in this respository. 

### Repository Contents
`index.html`: The interactive web deployment of the report.
`pums-analysis.pdf`: The formal, downloadable brief.
`pums-analysis.qmd`: The raw Quarto source code containing all data processing and visualization steps.

### Data Source
The data used in this analysis is the 2020-2024 5-Year ACS PUMS data for Oregon (State Code 41). Due to file size constraints, the raw `.csv` files are not hosted in this repository. They can be downloaded directly from the [US Census Bureau](https://www2.census.gov/programs-surveys/acs/data/pums/) (select "2024", then "5 year", then `csv_hor.zip` (household data) and `csv_por.zip` (individual data).

### Technologies used
Language: R
Libraries: `tidyverse` for data wrangling, `ggplot2` for data visualization
Environment: Quarto in Positron