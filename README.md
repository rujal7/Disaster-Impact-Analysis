# India Disaster Impact Analysis (2010-2025)

An interactive **Power BI dashboard** analyzing natural disasters in India from **2010 to 2025**: how often they occur, where they hit, and their impact in deaths, injuries, economic damage, and relief funds.

---

## Dashboard Preview

![Dashboard Overview](dashboard_overview.png)
![Dashboard Detail](dashboard_detail.png)

---

## Project Overview

The dashboard analyzes disaster events across Indian cities and years, and helps answer questions such as:

- How has the number of disasters changed from 2010 to 2025?
- Which disaster types cause the most economic damage, and which occur most often?
- Which cities are most affected in terms of deaths?
- How do relief funds compare with economic damage?
- How does disaster severity vary across cities and disaster types?

## Dataset

The data is stored in an Excel workbook (`data/disaster_data.xlsx`, sheet `Sheet1`).

| Field | Description |
|---|---|
| `Disaster_ID` | Unique ID for each disaster event |
| `Year` | Year of the event (2010-2025) |
| `City` | City affected |
| `Disaster_Type` | Type of disaster |
| `Severity` | Severity level of the event |
| `Deaths` | Number of deaths |
| `Injured` | Number of people injured |
| `Economic_Damage_USD_Millions` | Economic damage in USD millions |
| `Relief_Funds_USD_Millions` | Relief funds in USD millions |
| `Latitude`, `Longitude` | Location coordinates used for the map |

## Dashboard Structure

**Page 1 - Overview:** project title and a summary of the dashboard's purpose.

**Page 2 - Dashboard:**
- **KPI cards:** Total Economic Damage, Total Relief Funds, Total Deaths, Total Injured
- **Line chart:** number of disasters by year
- **Column chart:** economic damage by disaster type
- **Pie chart:** share of disasters by disaster type
- **Map:** locations of disasters, sized by deaths
- **Slicers:** filter by Year, City, Disaster Type, and Severity

**Page 3 - Conclusion:** summary of findings and future scope.

## Tools Used

- **Microsoft Excel**: data storage and preparation
- **Power BI**: data modeling, interactive visuals, slicers, map visualization
- **Microsoft PowerPoint**: presentation of the analysis

## Key Insights

> Add 3-4 findings from your own dashboard, each with a real number. Example format:
> - **[Disaster type]** caused the highest economic damage at about $X million.
> - **[City]** had the highest number of deaths.
> - Disaster counts [rose/fell] between 2010 and 2025, peaking in [year].
> - Relief funds covered about X% of total economic damage.

## Future Scope

- Integrate real-time disaster data from government APIs
- Add weather and satellite data for predictive analysis
- Develop AI-based disaster risk forecasting models
- Include district-level analysis for more detailed insights
- Create mobile-friendly dashboards for emergency response teams

## Repository Contents

| File | Description |
|---|---|
| `data/disaster_data.xlsx` | Dataset used for the analysis |
| `Disaster Impact Analysis.pbix` | Power BI dashboard (open with Power BI Desktop) |
| `Disaster Impact.pptx` | Presentation summarizing the analysis |

## How to Open the Dashboard

1. Download `Disaster Impact Analysis.pbix`.
2. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows only).
3. Open the file. If prompted for the data source, point it to `data/disaster_data.xlsx`.

## Author

**Rajneesh Sharma**
GitHub: [@rujal7](https://github.com/rujal7)
