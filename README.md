 Smart City Bike Sharing Analysis | Power BI

##  Project Overview

This project analyzes a Smart City Bike Sharing dataset using **Power BI** to evaluate bike station performance, bike availability, utilization efficiency, and operational status across multiple European cities.

The objective is to transform raw data into meaningful insights through data cleaning, modeling, DAX calculations, and interactive dashboard visualizations.

---

##  Objectives

- Import and explore the dataset in Power BI.
- Clean and transform data using Power Query.
- Build a Star Schema data model.
- Create DAX measures and calculated columns.
- Design an interactive dashboard.
- Generate business insights and recommendations.

---

##  Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Microsoft Excel
- GitHub

---

##  Dataset

**Dataset:** Smart City Bike Sharing Dataset

### Key Fields

- Station ID
- Station Name
- City Name
- Latitude
- Longitude
- Status
- Banking
- Bonus
- Total Bike Stands
- Available Bike Stands
- Available Bikes
- Update Date
- Update Time

---

##  Data Cleaning & Transformation

The following preprocessing steps were performed using **Power Query**:

- Removed unnecessary columns
- Renamed column headers
- Changed data types
- Converted TRUE/FALSE values
- Split Date and Time columns
- Removed duplicate records
- Standardized text formatting
- Created separate Update Date and Update Time columns

---

##  Data Model

A **Star Schema** was implemented.

### Fact Table

- Fact_Bike Stations Sharing Table

### Dimension Tables

- Dim_Date
- Dim_City
- Dim_Status

### Relationships

- Fact ↔ Dim_Date
- Fact ↔ Dim_City
- Fact ↔ Dim_Status

---

##  DAX Measures

Created the following measures:

- Total Stations
- Active Stations
- Total Bikes
- Total Bike Stands
- Occupancy Rate
- Empty Rate
- Utilization Percentage

---

## Dashboard Features

The dashboard contains:

- KPI Cards
- Dashboard Filters (Slicers)
- Top 10 Cities by Available Bikes
- Top 10 Cities by Utilization Rate
- Bike Station Status
- Interactive Map
- Station Details Table
- Key Insights Panel

---

## Key Insights

- Approximately **1,000 bike stations** are available across the network.
- Around **57,000 bike stands** support the bike-sharing system.
- Nearly **20,000 bikes** are currently available.
- **941 stations** are active.
- **92.79%** of stations are operational.
- Bruxelles-Capitale and Lyon have the highest bike availability.
- Jcdecauxbike records the highest utilization rate.
- The network spans more than **20 European cities**.

---

##  Recommendations

- Increase bike availability in high-demand cities.
- Reduce station downtime through preventive maintenance.
- Rebalance bikes based on utilization patterns.
- Monitor occupancy trends for operational optimization.
- Expand services in high-performing locations.

---

