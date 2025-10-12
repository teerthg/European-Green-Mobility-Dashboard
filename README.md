#  European Green Mobility Dashboard
### **CO₂ Emissions Analysis – Power BI 2025 Overview**

##  Project Overview
This project presents a **comprehensive analysis of CO₂ emissions** from new passenger cars registered in Europe. It explores emission patterns across **manufacturers**, **fuel types**, and **vehicle characteristics** such as engine capacity and mass.

Developed entirely in **Power BI**, the dashboard focuses on delivering **data-driven insights**, **statistical reasoning**, and **visual clarity** to support sustainable mobility decisions within the European Union context.

---

##  Dataset Information
The dataset is derived from the **European Union Regulation (EU) 2019/631**, which mandates annual CO₂ reporting for all new passenger car registrations within EU member states.

**Size:** ~4.9 million records  
**Source:** Official EU Open Data Portal

**Key Variables:**
| Variable | Description |
|-----------|--------------|
| Manufacturer (Mh, Man) | Name of car manufacturer |
| Fuel Type (Ft) | Petrol, Diesel, Electric, Hybrid, etc. |
| Engine Capacity (ec cm³) | Engine volume in cubic centimeters |
| Power (ep kW) | Engine power in kilowatts |
| Vehicle Mass (m kg) | Vehicle weight in kilograms |
| CO₂ Emissions (Enedc g/km) | Carbon dioxide emissions in grams per kilometer |

---

##  Analytical Approach
The analysis followed a structured **data analytics and statistical workflow**:

1. **Data Preparation:**  
   - Cleaned and standardized data using **Power Query**.  
   - Removed duplicates and handled missing values.  
   - Ensured consistent formatting across numeric and categorical fields.  

2. **Descriptive Statistics:**  
   - Computed emission averages, variances, and distributions using **DAX measures**.  
   - Calculated key descriptive metrics (mean, standard deviation) to summarize emission trends.  

3. **KPI Construction:**  
   - Created KPIs for:  
     - Average CO₂ Emission → **114.28 g/km**  
     - Average Engine Capacity → **1.50K cm³**  
     - Average Power → **93.45 kW**

4. **Comparative Analysis:**  
   - Compared **manufacturer-wise** and **fuel-type-wise** emission levels.  
   - Identified top and bottom performers using bar and pie charts.  

5. **Correlation Study:**  
   - Investigated the relationship between **engine capacity**, **vehicle mass**, and **CO₂ emissions** using scatter plots.  
   - Demonstrated a clear positive correlation trend.

---

##  Dashboard Components

| Component | Description |
|------------|--------------|
| **KPI Cards** | Display key averages: CO₂ emissions, engine capacity, and power. |
| **Bar Chart** | Visualizes average CO₂ emissions by manufacturer, identifying high and low emitters. |
| **Pie Chart** | Illustrates the proportion of fuel types—showing petrol and diesel dominance. |
| **Scatter Plot** | Reveals correlation between engine capacity and CO₂ output, with bubble size representing vehicle mass. |
| **Interactive Filters** | Country, Manufacturer, and Fuel Type slicers for dynamic exploration. |

---

##  Key Findings

- **Fuel Type Insights:**  
  Petrol and diesel vehicles make up **over 95%** of total registrations, showing limited adoption of electric and hybrid cars.  

- **Emission Correlation:**  
  Larger engines with higher capacity produce proportionally greater CO₂ emissions, confirming a **strong positive correlation** between performance and emissions.  

- **Manufacturer Variation:**  
  Luxury and sports manufacturers (e.g., BMW, Mercedes, Porsche) exhibit **notably higher average emissions**, while economy and electric brands perform better environmentally.  

- **Sustainability Evidence:**  
  Electric vehicles consistently rank lowest in emissions, reinforcing their role in achieving **EU Green Mobility targets**.

---

##  Skills Demonstrated

- **Data Analysis & Statistics:** DAX, Descriptive Statistics, Correlation Study  
- **Data Cleaning & Transformation:** Power Query, Data Modeling  
- **Visualization & Reporting:** Power BI (KPIs, Charts, Filters, Dynamic Slicers)  
- **Analytical Reasoning:** Identifying emission trends, comparative insights, and performance evaluation  

---

##  Tools & Technologies

- **Power BI** – Dashboard creation & DAX analytics  
- **Power Query** – Data cleaning and transformation  
- **Microsoft Excel** – Preliminary validation and summarization  
- **Statistical Concepts** – Mean, variance, correlation, comparative analysis  

---

##  Results Snapshot

- **Average CO₂ Emission:** 114.28 g/km  
- **Average Engine Capacity:** 1.50K cm³  
- **Average Power:** 93.45 kW  
- **Electric & Hybrid Share:** < 5%  
- **Strong correlation (r ≈ 0.78)** between engine capacity and emissions  

---

##  Project Impact

The dashboard serves as an **evidence-based visual tool** for policymakers, environmental analysts, and automobile manufacturers to:  
- Identify **high-emission vehicle categories**,  
- Monitor **progress toward EU carbon targets**, and  
- Promote **sustainable automotive innovation**.  

It demonstrates how **data visualization and statistical reasoning** can contribute to **climate-conscious decision-making**.

---

##  Author

** Teerth Gupta**  
Master’s in Statistics and Data Science, *Uppsala University*  
📍 Sweden | 💡 Data Analytics | Power BI | Machine Learning  

 [teerthgupta19@gmail.com] 
 [GitHub Profile](https://github.com/teerthgupta)
