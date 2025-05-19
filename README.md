# Data Cleansing and Analysis of Queensland Crash Data

## Repository Files

- [Data Cleansing Record.pdf](./Data%20Cleansing%20Record.pdf) – Documentation of the data cleansing process.
- [Project2.pptx](./Project2.pptx) – Project presentation slides.
- [Project2final.twb](./Project2final.twb) – Tableau workbook with analysis.

## 1. Data Sources

- **Population of Australia:** [Australian Bureau of Statistics](https://www.abs.gov.au/statistics/people/population)
- **Crash Data Queensland (2001–2022):** [Kaggle Dataset](https://www.kaggle.com/datasets/joebeachcapital/crash-data-queensland-australia-2001-2022)

Datasets were joined using the **Year** column as the primary key.

## 2. Exploratory Data Analysis (EDA)

- Initial EDA was conducted using **Tableau Prep Builder**.
- The process identified missing data and potential insights.

## 3. Data Cleansing Process

### Removal of "Property Damage Only" Cases

- "Property Damage Only" records (minor incidents with only vehicle damage) from 2001–2010 were removed, as a policy change after 2010 excluded such records.
- This ensures consistency in the analysis and does not impact overall findings.

### Tools Used

- **Tableau Desktop** was used for:
  - **Filtering** out "Property Damage Only" cases.
  - **Grouping** crash conditions for analysis and visualisation.

## License

This project is licensed under the [MIT License](./LICENSE).
