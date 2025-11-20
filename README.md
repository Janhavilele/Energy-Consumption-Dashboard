# Energy-Consumption-Dashboard
**1. Project Title :** Electricity Consumption & Sustainability Dashboard
An interactive Power BI dashboard designed to analyze India’s electricity consumption trends, renewable energy share, carbon emissions, and forecast future demand using dynamic filters and DAX-powered KPIs.

**2. Purpose :**
The Energy Insights Dashboard provides a clear, visual understanding of monthly and yearly electricity consumption patterns across India. It helps identify renewable vs. non-renewable trends, carbon emissions, peak load months, and future consumption forecasts to support sustainable energy planning and decision-making.

**3. Tech Stack:**
The dashboard was built using the following tools and technologies:
- Power BI Desktop – Core platform for visualization
- Power Query – Data cleaning, transformation & shaping
- DAX (Data Analysis Expressions) – All KPIs, calculations & forecasting logic
- Data Modeling – Relationships between Date, Variable, Units & Consumption measures
- File Formats – .pbix for the report, .png for dashboard previews

**4. Data Source:**
Source : Kaggle – India Monthly Electricity Consumption (2019–2025) (https://www.kaggle.com/datasets/rhtsingh/india-monthly-electricity-consumption-20192025)
Dataset includes month-wise energy consumption, generation categories, carbon emissions, renewable share, and YoY/MoM changes across Indian states.

**Key Columns:**
Country – Country name (India)
State – Indian state/union territory
State type – State / Union territory
Date – Month and year (DD-MM-YYYY)
Category – Data category (e.g., Capacity)
Subcategory – Aggregate fuel / Fuel
Variable – Type of energy source (Coal, Gas, Hydro, Solar, Renewables, etc.)
Unit – Measurement unit (MW)
Value – Capacity value in MW
YoY absolute change – Year-on-year absolute capacity change
YoY % change – Year-on-year percentage change

**5. Features:**
**Business Problem:**
India’s energy sector is rapidly growing, but insights on consumption patterns, renewable share, and carbon emissions are difficult to analyze directly from raw data.

**Key questions include:**
1) When does consumption peak?
2) How fast are renewables growing?
3) What states or months contribute more to emissions?
4) How will energy demand grow in upcoming years?

**Goal of the Dashboard:**
To build a single-page interactive tool that:
- Tracks national energy consumption & emissions
- Identifies renewable contribution trends
- Highlights peak energy demand periods
- Forecasts next-year electricity consumption
- Supports sustainable planning & policy decisions

**Walkthrough of Key Visuals:**

**i) KPI Cards (Top Left)**
- Total Energy Consumption
- Peak Load Month
- Total CO2 Emissions (ktCO2)
- Renewable Share %
- MoM Change %

**ii) Forecast of Total Consumption (2025–2026):**
- Line + forecast visual showing expected demand for next year using DAX measure + built in forecasting model.

**iii) Total Consumption by Month:**
- Shows seasonal consumption patterns and identifies peak vs. low-demand months.

**iv) Total Consumption by Variable (Bar Chart):**
Comparison of categories like:
- Total Generation
- Wind & Solar
- Total Emissions
- Wind
- Solar
Helps understand energy mix composition.

**v) Total Renewables by Year (Area Chart):**
- Tracks year-wise renewable energy growth and sustainability progress.

**vi) Total Consumption by State:**
- Highlights the top 5 Indian states with the highest electricity consumption, enabling quick comparison of regional energy demand.

**vii) Slicers for Interactivity**
Users can filter by:
- State
- Energy Variable
- Unit
- Year
- Month

**Business Impact & Insights :**
1. Strategic Energy Planning: Identifies consumption peaks to optimize grid load and infrastructure planning.
2. Sustainability Tracking: Helps monitor renewable energy growth and CO2 emission reductions.
3. Policy Support: Enables data-driven decisions on energy diversification and environmental impact.
4. Operational Efficiency: Organizations can track monthly usage patterns and optimize energy usage.
5. Forecasting Readiness: Predictive insights help anticipate demand fluctuations for upcoming years.

**6. Screenshot:**
![Dashboard Screenshot]()
