# Daikibo Telemetry Dashboard (Deloitte Job Simulation)

## Overview
This project presents an interactive dashboard developed as part of the Deloitte Data Analytics Job Simulation. The objective was to analyze IoT telemetry data from Daikibo factories and identify patterns in device health across different locations and machine types.

The dashboard focuses on:
- Unhealthy device counts by factory  
- Distribution of unhealthy devices by device type  
- Operational insights to support decision-making  

---

## Tools and Technologies
- Tableau (data visualization and dashboard development)  
- JSON (source data format)  
- Data aggregation and transformation techniques  

---

## Dataset
The dataset (`daikibo-telemetry-data.json`) contains IoT device information, including:
- Device ID  
- Device Type  
- Factory location (Area/City)  
- Temperature readings  
- Status (Healthy/Unhealthy)  

---

## Methodology

### Data Preparation
- Imported the JSON dataset into Tableau  
- Validated and assigned appropriate data types  
- Created calculated fields to isolate and count unhealthy devices  

### Data Transformation
- Grouped data by factory (Berlin, Meiyo, Seiko, Shenzhen)  
- Grouped data by device type (e.g., Laser Cutter, CNC, Furnace)  
- Aggregated counts of unhealthy devices for analysis  

### Dashboard Development
- Built two primary visualizations:
  - Bar chart showing unhealthy device counts by factory  
  - Bar chart showing unhealthy device counts by device type  
- Incorporated interactivity through filters and tooltips for deeper exploration  

---

## Key Insights
- Seiko and Shenzhen factories show the highest number of unhealthy devices  
- Laser-based equipment (Laser Cutter and Laser Welder) has the highest failure rates  
- Devices such as Air Wrench and Conveyor Belt show minimal issues  

---

## Dashboard Preview
<img width="1592" height="1079" alt="image" src="https://github.com/user-attachments/assets/70bbfc0f-fc46-428b-be53-70fb6808cb11" />


---

## How to Use
1. Open the Tableau dashboard file  
2. Use filters to explore device performance by factory or type  
3. Review patterns to identify high-risk equipment and locations  

---

## Learning Outcomes
- Developed skills in data visualization and dashboard design  
- Gained experience working with semi-structured JSON data  
- Applied data aggregation techniques for business insights  
- Translated raw telemetry data into actionable findings  

---

## Author
V. Karthikeyan
