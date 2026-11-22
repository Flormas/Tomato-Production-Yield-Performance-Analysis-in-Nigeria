# Tomato-Production-Yield-Performance-Analysis-in-Nigeria
## An Excel-based analysis of tomato production, cultivated area and yield patterns across selected Nigerian states from 2024 to 2025.
### Table of Content
- [Project overview](Project-overview)
- [Tools used](#Tools-used)
- [Dataset overview](#Dataset-overview)
- [Sample dataset preview](#Sample-dataset-preview)
- [Data cleaning process](#Data-cleaning-process)
- [Exploratory data analysis](#Exploratory-data-analysis)
- [Dashboard details](#Dashboard-details)
- [Key insights](#Key-insights)
- [Recommendations](#Recommendations)

### Project Overview
This project analyses tomato production records across selected locations in Nigeria over 2024 and 2025. The analysis focuses on production volume, cultivated land area and yield performance, with comparisons across states, years and months. The goal is to identify differences in production and productivity, highlight patterns that may warrant further investigation, and present the findings in an interactive Excel dashboard for decision support.
The workbook contains a raw production dataset, a cleaned analysis dataset, KPI and PivotTable calculations, and a dashboard. The cleaned worksheet contains 1,997 records and 30 columns, including a derived Year field.
### Tools Used
- Microsoft Excel 2021 (data preparation, calculations, PivotTables, charts and dashboard)
- Excel formulas and GETPIVOTDATA (KPI and weighted-yield calculations)
### Dataset Overview
- workbook sheets: Raw_Production_Dataset, CLEANED_DATASET, KPIs_PIVOT and DASHBOARD.
- Analysis period: 2024–2025. The cleaned dataset has 1,997 records and 30 fields.
- Fields cover production identifiers and dates; state and LGA; farm and buyer identifiers; tomato variety and production season; cultivated area, harvested, spoiled/lost and sold tonnes; yield; grade; selling price and revenue; cost components and gross margin; irrigation method; sales channel; payment and delivery status; supplier ID; and Year.
### Sample Preview of Dataset
<img width="1363" height="550" alt="Tomato Dataset" src="https://github.com/user-attachments/assets/9ddb6657-a283-432d-b896-24d109ac17a9" />

### Data Cleaning Process
1.	Loaded and reviewed the raw production data before preparing the analysis-ready worksheet.
2.	Converted Production_Date into a date field and derived a Year column for year-over-year comparisons.
3.	Standardized key text fields such as state, tomato variety and production season for consistent grouping and filtering.
4.	Reviewed numerical production, area, yield, price, revenue and cost fields for consistent numeric formats and calculations.
5.	Prepared a cleaned worksheet for PivotTable analysis and dashboard reporting.
### Exploratory Analysis
The analysis uses KPI summaries and PivotTables to compare production and cultivated area by state and year, calculate weighted yield, and examine monthly production and yield patterns. A state-level scatter plot explores the relationship between cultivated area and harvested production.
Weighted yield is calculated as total harvested tonnes divided by total cultivated hectares for the selected group. This is preferable to taking a simple average of record-level yields.
### Dashboard Details
- Four headline KPIs: Total Tomato Production, Total Cultivated Area, Weighted Average Yield and Production Records.
- State comparisons: Tomato Production by State and Weighted Yield by State.
- Time trends: Monthly Tomato Production Trend (2024 vs 2025) and Monthly Tomato Yield Trend (2024 vs 2025).
- Relationship analysis: Cultivated Area versus Tomato Production by State.
- Interactive slicers: Year, State, Tomato Variety and Production Season.
The dashboard is designed to let a viewer filter the results and compare production and yield performance across the available dimensions.

<img width="1339" height="503" alt="Tomato Dashboard" src="https://github.com/user-attachments/assets/9a5f5af2-9eac-4b4c-a2be-ac52d81bffcd" />

### Key Insights
- Overall performance: The workbook KPI PivotTable reports 90,299.18 tonnes harvested across 6,231.92 cultivated hectares, with an overall weighted yield of 14.49 tonnes/ha and 1,998 production records.
- Production by state: Kano has the highest recorded production at approximately 16,316.14 tonnes, while Oyo has the lowest at approximately 3,299.37 tonnes.
- Yield by state: Yobe has the highest weighted yield at approximately 15.15 tonnes/ha, while Delta has the lowest at approximately 13.18 tonnes/ha. The state with the highest production is not necessarily the state with the highest yield.
- Year-over-year performance: Production was 47,881.31 tonnes in 2024 and 42,417.86 tonnes in 2025, a decline of approximately 11.41%. Cultivated area declined approximately 7.26%, while weighted yield declined approximately 4.48%.
- Monthly production: The latest PivotTable monthly production totals show April as the highest month in 2024 (6,257.20 tonnes) and May as the highest month in 2025 (4,999.76 tonnes).
- Monthly yield: The latest monthly weighted-yield summary shows September as the highest-yield month in 2024 (17.19 tonnes/ha), and May as highest in 2025 (15.73 tonnes/ha). February is the lowest month in 2025 (12.15 tonnes/ha).
- Area and production relationship: The dashboard includes a state-level scatter chart to explore the relationship between cultivated area and harvested production. 

### Recommendations
- Investigate the 2025 production decline by comparing state-level performance, cultivated area and weighted yield.
- Examine lower-yield locations, especially Delta, to identify questions for further investigation around season, variety, irrigation and production practices.
- Monitor production volume together with weighted yield and cultivated area rather than relying on one measure alone.
- Use monthly trends to inform further questions about planting, harvesting, storage and market planning, and validate these patterns against real operational data.
- Strengthen data quality through complete record identifiers, standardized state labels and documented calculation rules.

