## European Green Mobility Dashboard
CO₂ Emissions Analysis – Power BI 2025
Overview

This project presents a detailed analysis of CO₂ emissions from passenger cars registered in Europe. The work focuses on exploring emission trends across manufacturers, comparing fuel types, and studying how engine capacity and vehicle mass influence CO₂ output. The dashboard was developed in Power BI with an emphasis on statistical reasoning, visual clarity, and data-driven insight.

## Dataset

The dataset is based on the official European Union Regulation (EU) 2019/631, which records detailed information about new passenger car registrations across EU member states. It contains around 4.9 million records and includes variables such as manufacturer, fuel type, engine capacity, power, vehicle mass, and CO₂ emissions.

## Key variables used in the analysis:

Manufacturer (Mh, Man)

Fuel Type (Ft)

Engine Capacity (ec cm³)

Power (ep kW)

Vehicle Mass (m kg)

CO₂ Emissions (Enedc g/km)

## Analytical Approach

The project follows a structured analytical and statistical process:

Data Preparation: Cleaned data, handled missing values, and standardized column formats using Power Query.

Descriptive Statistics: Computed means, variances, and emission averages using DAX functions.

KPI Construction: Developed key indicators for average CO₂ emission, average engine capacity, and average power.

Comparative Analysis: Compared manufacturer-level and fuel-type averages to identify high- and low-emission groups.

Correlation Study: Explored the relationship between engine capacity, vehicle mass, and CO₂ emissions using a scatter plot.

## Dashboard Components

The Power BI dashboard consists of several interactive visuals:

KPI Cards: Display average CO₂ emissions (114.28 g/km), average engine capacity (1.50K cm³), and average power (93.45 kW).

Bar Chart: Shows the average CO₂ emission by manufacturer, identifying the top and bottom performers.

Pie Chart: Displays the distribution of cars by fuel type, highlighting the dominance of petrol and diesel vehicles.

Scatter Plot: Demonstrates the positive correlation between engine capacity and CO₂ emissions, with bubble size representing vehicle mass.

Interactive Filters: Country, Manufacturer, and Fuel Type slicers allow users to filter and explore data dynamically.

## Key Findings

Petrol and diesel vehicles account for more than 95% of total registrations, confirming limited penetration of electric and hybrid cars.

A clear positive correlation exists between engine capacity and CO₂ emissions. Larger engines emit proportionally higher CO₂ levels.

Electric vehicles consistently appear at the lower end of the emission spectrum, validating their environmental efficiency.

Significant differences exist between manufacturers, with luxury and sports car brands showing notably higher average emissions.
