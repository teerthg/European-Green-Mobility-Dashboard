# European Green Mobility Dashboard  
### CO₂ Emissions Analysis – Power BI 2025

## Project Overview
This project provides an analysis of CO₂ emissions from newly registered passenger cars across Europe. It examines emission differences across manufacturers, fuel types, and vehicle characteristics such as engine capacity, engine power, and vehicle mass.

The dashboard was built entirely in **Power BI**, focusing on clear visual insights and data-driven reasoning to support sustainable mobility decisions in the European Union.

---

## Dataset Information
The dataset originates from **EU Regulation (EU) 2019/631**, which mandates CO₂ reporting for all new passenger car registrations.

**Dataset Size:** ~4.9 million records  
**Source:** EU Open Data Portal

**Main Variables**

| Variable | Description |
|---------|-------------|
| Manufacturer | Car manufacturer |
| Fuel Type | Petrol, Diesel, Electric, Hybrid, etc. |
| Engine Capacity (cm³) | Engine volume |
| Power (kW) | Engine power |
| Vehicle Mass (kg) | Weight of the vehicle |
| CO₂ Emissions (g/km) | Emissions per kilometer |

---

## Analytical Approach

### 1. Data Preparation
- Cleaned and standardized data using Power Query  
- Removed duplicates and filled missing values  
- Ensured consistent formatting across numeric and categorical fields  

### 2. Descriptive Statistics
- Used DAX to compute averages and distributions  
- Summarized key emission metrics  

### 3. KPIs
- **Average CO₂ Emission:** 114.28 g/km  
- **Average Engine Capacity:** 1.50K cm³  
- **Average Power:** 93.45 kW  

### 4. Comparative Analysis
- Compared emissions between manufacturers  
- Examined differences across fuel types  

### 5. Correlation Study
- Analyzed the relationship between engine capacity, mass, and emissions  
- Found a strong positive correlation between engine size and CO₂ emissions  

---

## Dashboard Components

| Component | Purpose |
|----------|---------|
| **KPI Cards** | Display core averages |
| **Bar Chart** | Compare manufacturers by emission levels |
| **Pie Chart** | Show distribution of fuel types |
| **Scatter Plot** | Visualize relationship between engine capacity and emissions |
| **Filters** | Slicers for manufacturer, country, and fuel type |

---

## Key Findings

- Petrol and diesel vehicles account for over 95% of registrations, showing slow adoption of electric and hybrid vehicles.  
- Cars with larger engine capacity consistently produce higher CO₂ emissions.  
- Manufacturers such as BMW, Mercedes, and Porsche show significantly higher average emissions than economy-focused brands.  
- Electric vehicles perform best environmentally, aligning with EU sustainability goals.  

---

## Skills Demonstrated
- Data analysis and interpretation  
- Power Query data cleaning and modeling  
- Power BI dashboard creation and DAX calculations  
- Comparative analytics and correlation analysis  
- Insightful data storytelling  

---

## Tools and Technologies
- Power BI  
- Power Query  
- Microsoft Excel  
- Statistical methods: mean, variance, correlation  

---

## Results Summary
- **Average CO₂ Emission:** 114.28 g/km  
- **Average Engine Capacity:** 1.50K cm³  
- **Average Power:** 93.45 kW  
- **Electric + Hybrid Share:** < 5%  
- **Correlation (engine capacity vs emissions):** r ≈ 0.78  

---

## Project Impact
This dashboard provides a structured analytical solution that helps policymakers, automotive researchers, and manufacturers:

- Identify high-emission vehicle categories  
- Track progress toward EU CO₂ reduction targets  
- Support decisions to promote sustainable vehicle development  

It highlights how data visualization and analytical reasoning can contribute to environmental and policy-related decision-making.

---

## Author
**Teerth Gupta**  
Master’s in Statistics and Data Science, Uppsala University  
Sweden | Data Analytics | Power BI | Machine Learning  

**Email:** teerthgupta19@gmail.com  
**GitHub:** https://github.com/teerthgupta
