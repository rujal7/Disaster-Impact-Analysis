# Disaster Impact Analysis

An interactive **Power BI dashboard** that analyzes the human and economic impact of natural disasters, with an **Excel** dataset and a **PowerPoint** presentation summarizing the findings.

---

## Project Overview

Natural disasters affect millions of people and cause large economic losses every year. This project explores disaster records to help answer practical questions such as:

- Which disaster types occur most often, and which are the most destructive?
- Which countries and regions are hit hardest?
- How have deaths, people affected, and economic damage changed over time?
- Where should preparedness and relief efforts be prioritized?

The dashboard lets users filter and explore the data interactively instead of reading static tables.

## Repository Contents

| File | Description |
|---|---|
| `data/disaster_data.xlsx` | Dataset used for the analysis |
| `Disaster Impact Analysis.pbix` | Power BI dashboard (open with Power BI Desktop) |
| `Disaster Impact.pptx` | Presentation summarizing the analysis and findings |
| `README.md` | Project documentation |

## Tools and Skills Used

- **Microsoft Excel**: data collection, cleaning, and preparation
- **Power BI**: data modeling, DAX measures, interactive visuals, slicers and filters
- **Microsoft PowerPoint**: storytelling and presenting insights
- **Skills demonstrated**: data cleaning, exploratory analysis, KPI design, dashboard design, data storytelling

## Methodology

1. **Data collection**: gathered disaster records into a single Excel workbook.
2. **Data cleaning**: checked for duplicates, missing values, and inconsistent labels; standardized fields so they could be grouped and compared.
3. **Data modeling**: loaded the cleaned data into Power BI and created measures (DAX) for key metrics such as total events, deaths, people affected, and economic damage.
4. **Visualization**: built charts, maps, and KPI cards, with slicers for year, disaster type, and region.
5. **Insights and presentation**: summarized the main patterns and recommendations in a PowerPoint deck.

## Dashboard Features

- KPI cards for headline totals
- Trend analysis over time
- Breakdown by disaster type
- Geographic view of affected countries or regions
- Interactive slicers and cross-filtering between visuals

## Key Insights

> Add 3-4 findings from your dashboard here, each with a real number. Example format:
> - **Floods** were the most frequent disaster type, making up X% of all events.
> - **Earthquakes** caused the highest number of deaths.
> - Economic damage increased by X% between YEAR and YEAR.

## How to Open the Dashboard

1. Download `Disaster Impact Analysis.pbix` from this repository.
2. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows only).
3. Open the `.pbix` file. If Power BI asks for the data source, point it to `data/disaster_data.xlsx`.

## Future Improvements

- Add more years or additional data sources for a longer trend
- Include population data to compare impact per capita
- Add forecasting to estimate future disaster impact
- Publish the report online with Power BI Service

## Author

**Rujal**
GitHub: [@rujal7](https://github.com/rujal7)
