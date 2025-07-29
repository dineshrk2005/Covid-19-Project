📊 COVID-19 Global Impact & Vaccination Dashboard
📁 Project Description
This Excel project analyzes global COVID-19 data using two datasets:

Covid_deaths.csv (case counts, deaths, population)

Covid_vaccinations.csv (vaccination status)

It provides insights into global trends, death rates, and vaccination progress through pivot tables, formulas, and visual dashboards.

📌 Project Objectives
Track global COVID-19 infections and deaths over time.

Calculate and visualize death rates per country.

Compare vaccination progress between countries.

Highlight top 10 countries by infection rate.

Build an interactive Excel dashboard for decision-making.

📂 Excel Sheets Structure
Sheet Name	Description
Covid_Deaths	Raw data imported from Covid_deaths.csv.
Covid_Vaccinations	Raw data from Covid_vaccinations.csv.
Global_Summary	KPI metrics using formulas (Total Cases, Deaths, Death %).
Infection_Trend	Pivot tables and line chart showing case/death trends over time.
Top_10_Countries	Pivot with calculated field for Infection Rate % + bar chart.
Vaccination_Progress	Pivot showing vaccination % by country + chart.
Dashboard	Final visual dashboard combining charts, KPIs, and slicers.

⚙️ How to Use
Open Excel and import both CSV files:

Covid_deaths.csv → Sheet Covid_Deaths

Covid_vaccinations.csv → Sheet Covid_Vaccinations

Use Ctrl + T to format each dataset as a Table.

All pivot tables and formulas will automatically update.

Navigate to the Dashboard sheet for visual insights.

🧮 Key Formulas Used
Total Cases:
=SUM(Covid_Deaths!F2:F100000)

Death Rate %:
=Total Deaths / Total Cases * 100

Infection Rate % (Pivot Calculated Field):
= total_cases / population * 100

Vaccination %:
= total_vaccinations / population * 100

📈 Charts Used
Global cases and deaths line chart

Top 10 countries by infection rate (bar chart)

Vaccination rate by country

KPI cards (Total Cases, Deaths, Death Rate)

✅ Requirements
Microsoft Excel 2016 or newer (for pivot charts and slicers)

Basic Excel skills (formulas, pivot tables, charts)
