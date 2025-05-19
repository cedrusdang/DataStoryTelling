Data Cleansing and Analysis of Queensland Crash Data

## 1. Data Sources

- **Population of Australia:** [Australian Bureau of Statistics](https://www.abs.gov.au/statistics/people/population)
- **Crash Data Queensland (2001–2022):** [Kaggle Dataset](https://www.kaggle.com/datasets/joebeachcapital/crash-data-queensland-australia-2001-2022)

The datasets were joined using the **Year** column as the primary key.

## 2. Exploratory Data Analysis (EDA)

- An initial EDA was conducted using **Tableau Prep Builder**.
- The process helped identify missing data and potential insights.

## 3. Data Cleansing Process

### Removal of "Property Damage Only" Cases

- Records classified as "Property Damage Only" (minor incidents with only vehicle damage) from 2001–2010 were excluded due to a policy change after 2010.
- This removal ensures consistency in the analysis and does not affect the overall findings.

### Tools Used

- **Tableau Desktop** was used for:
  - **Filtering** out "Property Damage Only" cases.
  - **Grouping** crash conditions for analysis and visualisation.
