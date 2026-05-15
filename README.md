# 🌎 United States Emissions Breakdown — Databricks Dashboard

An interactive county-level emissions dashboard built in **Databricks**, visualizing EPA greenhouse gas data across the United States.

---

## 📊 Dashboard Preview

![US Emissions Dashboard](assets/dashboard_preview.png)

> **Live Dashboard (Databricks):**
> [View on Databricks](https://dbc-67b2619d-a17e.cloud.databricks.com/sql/dashboardsv3/01f150107ac5140aa4c2a770b77c5e26/pages/89e4d604?o=335152379134188)

---

## 📁 Dataset

**File:** `Emissions_Data_2023.csv`
**Source:** U.S. Environmental Protection Agency (EPA), collected 2025
**Coverage:** 3,142 counties across all 50 U.S. states

### Key Fields

| Field | Description |
|---|---|
| `state_abbr` | State abbreviation |
| `county_name` | County name |
| `latitude / longitude` | Geographic coordinates |
| `population` | County population |
| `GHG emissions mtons CO2e` | Total greenhouse gas emissions (metric tons CO₂ equivalent) |
| `consumption (MWh)` | Electricity consumption |
| `consumption (TcF)` | Natural gas consumption |
| `vehicle miles traveled (miles)` | Total VMT per county |
| `consumption (gallons)` | Water/fuel consumption |

---

## 📈 Dashboard Highlights

### Emissions per Location
Interactive map plotting emissions intensity by county across the US.

### Emissions vs. Population
Scatter plot showing the relationship between county population and per-capita emissions.
> **Key Insight:** Higher-population counties tend to have *lower* emissions per person.

### Top 10 States — Emissions Share
These 10 states account for **51% of all US emissions:**
`TX • FL • OH • IL • GA • MO • CA • TN • PA • NC`

### Top Counties by Total Emissions (mTon CO₂e)

| County | Total Emissions |
|---|---|
| Maricopa County, AZ | 9.81M |
| Harris County, TX | 9.68M |
| Cook County, IL | 8.11M |
| Miami-Dade County, FL | 5.62M |
| Dallas County, TX | 5.43M |
| Los Angeles County, CA | 5.00M |
| Tarrant County, TX | 4.48M |
| Broward County, FL | 4.41M |
| Clark County, NV | 4.24M |

---

## 🛠 Built With

- **Databricks** — Dashboard, SQL analytics, Delta Lake
- **EPA Emissions Dataset** — County-level GHG and energy data
- **Mapbox / OpenStreetMap** — Geospatial map layer

---

## 📂 Repository Structure

```
us-emissions-dashboard/
│
├── Emissions_Data_2023.csv       # Source dataset (3,142 counties)
├── assets/
│   └── dashboard_preview.png    # Dashboard screenshot
└── README.md
```
