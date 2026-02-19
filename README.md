# Hospital-data-analysis

Project Overview

This dashboard transforms raw hospital visit data into clear, actionable visuals. Key focus areas include:
- Total visits, revenue, and average length of stay (ALOS)
- Diagnosis distribution (Diabetes, Flu, Hypertension, Malaria, Pneumonia, Typhoid) by county (Kiambu, Kisumu, Mombasa, Nairobi, Nakuru, etc.)
- Monthly trends in visits and revenue
- Revenue breakdown by department (Inpatient, Outpatient, Emergency)
- Patient demographics by age group (Children, Teens, Adults, Middle-Age, Seniors)
- Average LOS and revenue comparison across diagnoses

Designed with intuitive slicers/filters for date range, county, and diagnosis — perfect for quick exploration and performance monitoring.

 Key Features & Visuals

- **KPIs Cards** — Total Visits: 300 | Total Revenue: $275.407K | Avg LOS: 1.41 days
- **Diagnosis by County** — Stacked bar chart showing count per diagnosis across Kenyan counties
- **Monthly Trends** — Dual-axis line + column chart for visits and revenue over 2024
- **Revenue by Department** — Donut/pie chart highlighting Outpatient (34.5%), Emergency (34.5%), Inpatient (31.5%)
- **Age Group Distribution** — Pie chart of patient quantities by age category
- **Diagnosis Performance** — Scatter/bubble chart comparing Avg LOS vs. Total Revenue per diagnosis
- **Interactive Filters** — Slicers for Visit Date (range), County, and Diagnosis selection

All visuals are cross-filtered for seamless drill-down and storytelling.

  Tech Stack

- **Power BI Desktop** — Core tool for data modeling, DAX calculations, and visualization
- **DAX** — Custom measures for KPIs, aggregations, and trends
- **Data Sources** — Excel/CSV (hospital visits with columns: Visit_Date, County, Diagnosis, Department, Age Group, Quantity/Revenue, etc.)
- **Modeling** — Star schema with relationships between fact table (visits) and dimensions (date, county, diagnosis, age, department)
- **Visuals** — Cards, bar/column charts, line charts, pie/donut, scatter, slicers

Insights Delivered

- Identify high-burden diagnoses (e.g., Malaria/Pneumonia spikes in certain counties)
- Spot revenue seasonality and peak months
- Compare department contributions and efficiency (ALOS)
- Understand patient demographics for targeted resource allocation
- Support healthcare planning in Kenyan counties
 
