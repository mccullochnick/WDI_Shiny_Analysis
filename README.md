# WDI_Shiny_Analysis
An analysis and Shiny project using the World Bank's World Development Indicators dataset.

## Project Description
This project utilized the World Bank's Development Indicator's Database. The Database contains information by country, year, and topic, covering everything from healthcare to criminal justice and every year from 1960 to the present. We decided to explore the relationship between a country's education system and its economy.

The primary purpose of the World Bank is to support the development of lower income countries. However, although humanitarian in its aim, it's not a charity. The Bank offers loans and competitive grants and ideally hopes for a good rate of return. High impact and reliable development activities allow the bank to recoup its investment, and bad investments endanger its mission. Therefore, it's critical to identify which investments have the greatest relationship with the Bank's development goals and are most likely to pay off.

Education is often seen as a vehicle to better employment and prosperity. As students, we personally have made the decision to invest in education with the hope that the long-term reward is worth it. The government has taken an interest as well in the form of subsidized student loans and education grants. The potentially significant benefits of education are matched by significant expense, so it is critical to determine whether it is a good use of government, Bank, and student resources.

## Data
The data was taken from the World Development Indicators [dataset](https://databank.worldbank.org/source/world-development-indicators) of the World Bank. The initial data set consisted of 10,113 observations of 65 variables. These include, Country and Series, two character-columns, and 63, year columns from 1960:2022. We first pivoted this data first longer, then wider, leaving us with 40 variables, Country and Year, and 38, Series variables which covered a mixture of education topics such as total adult literacy, primary, secondary, and tertiary education as a percentage of the population and economic measures such as GDP and GDP per capita.

## RShiny
A shiny dashboard for the project can be found [here](https://nickmcculloch.shinyapps.io/world_bank_project/).

## Files

| Name | Description | Type |
| ----------- | ----------- | ----------- |
| world_bank_paper | the accompanying paper | .Rmd |
| world_bank_paper | the accompanying paper | .pdf |
| world_bank_project | project code-doc | .docx |
| world_bank_project | project code-Rmd | .Rmd |
| world_bank_project | project code-pdf  | .pdf |
| world_bank_project-shiny files | Rshiny zip files | .zip |
| Project_Files | project zip files | .zip |



## Authors
* [@mccullochnick](https://github.com/mccullochnick)