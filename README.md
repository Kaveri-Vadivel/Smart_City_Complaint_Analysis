Smart City Complaint Analysis
Problem Statement

Modern cities receive thousands of citizen complaints every day regarding road damage, water supply issues, garbage collection, street light failures, drainage problems, traffic congestion, and public safety concerns. As the volume of complaints increases, it becomes difficult for city authorities to manually monitor, track, and resolve issues efficiently.

The objective of this project is to analyze smart city complaint data and develop an interactive analytics dashboard that helps city administrators identify complaint trends, evaluate department performance, detect complaint hotspots, and improve service delivery through data-driven decision-making.

Dataset Description

This project uses a Smart City Complaint Dataset containing approximately 210,000 complaint records. The dataset includes information related to complaint categories, responsible departments, complaint priority levels, complaint status, complaint dates, resolution time, and geographic locations such as zones, wards, and areas.

Before analysis, the dataset was cleaned by handling missing values, removing duplicate records, converting date fields into the appropriate format, and creating additional analytical features such as Severity Score, Resolution Delay, Satisfaction Score, Month, and Year.

KPI Definitions

The dashboard was designed using several key performance indicators to measure city operational efficiency and service quality.

Total Complaints: Total number of complaints received by the city.
Resolved Complaints: Number of complaints that have been successfully resolved.
Resolution Rate: Percentage of complaints resolved out of the total complaints received.
Average Resolution Time: Average number of days required to resolve complaints.
High Priority Complaints: Total number of complaints marked as High or Critical priority.
Citizen Satisfaction Score: Estimated satisfaction score based on complaint resolution speed.
Complaint Hotspot Zones: Zones generating the highest number of complaints.
Department Performance Score: Performance metric based on complaint resolution efficiency.
Dashboard Screenshots
Executive Overview

This dashboard provides a high-level summary of city complaint operations. It includes Total Complaints, Resolution Rate, Average Resolution Time, Citizen Satisfaction Score, Monthly Complaint Trends, and Complaint Distribution.

<img width="1151" height="646" alt="EXECUTIVE_OVERVIEW" src="https://github.com/user-attachments/assets/85040df4-2eb7-4f58-9a66-6398fa7075f1" />

Complaint Analysis

This dashboard focuses on complaint categories and complaint patterns. It helps identify the most common complaint types, complaint priorities, and complaint status distribution.

Insert Complaint Analysis Dashboard Screenshot Here

Geographic Analysis

This dashboard highlights complaint hotspots and geographic patterns. It helps identify zones and areas experiencing recurring civic issues.

Insert Geographic Analysis Dashboard Screenshot Here

Service Performance

This dashboard evaluates departmental efficiency and complaint resolution performance. It compares department performance, resolution times, and priority handling efficiency.

Insert Service Performance Dashboard Screenshot Here

Key Findings
Road Damage, Garbage Collection, and Water Supply complaints were among the most frequently reported issues.
Certain zones consistently generated a higher number of complaints, indicating recurring infrastructure and service-related challenges.
Departments responsible for infrastructure maintenance experienced comparatively longer complaint resolution times.
High-priority complaints were generally resolved faster than low-priority complaints.
Complaint volumes varied across different time periods, highlighting fluctuations in service demand.
Faster complaint resolution contributed positively to citizen satisfaction levels.
Recommendations
Allocate additional resources to departments with high complaint volumes and longer resolution times.
Prioritize infrastructure maintenance and improvement activities in complaint hotspot zones.
Implement preventive maintenance programs for frequently occurring civic issues.
Strengthen monitoring systems for unresolved high-priority complaints.
Improve coordination among departments to reduce complaint resolution delays.
Continuously track citizen satisfaction and service quality metrics to support performance improvement initiatives.
Future Scope
Develop a real-time complaint monitoring system for city authorities.
Integrate GIS-based mapping for advanced geographic analysis.
Implement predictive analytics to forecast future complaint trends.
Build machine learning models to identify high-risk complaint zones.
Develop automated alert systems for critical complaints requiring immediate attention.
Incorporate citizen feedback and sentiment analysis for improved satisfaction measurement.
Tools and Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Power BI
Google Colab
Jupyter Notebook
GitHub
## Project Structure

```text
Smart_City_Complaint_Analysis/
│
├── data/
│   ├── smart_city_raw.csv
│   └── cleaned_smart_city.csv
│
├── notebook/
│   └── SMART_CITY_COMPLAINT.ipynb
│
├── dashboard/
│   └── SMART_CITY_DASHBOARD.pbix
│
├── images/
│   ├── executive_overview.png
│   ├── complaint_dashboard.png
│   ├── geographic_dashboard.png
│   └── service_performance_dashboard.png
│
├── reports/
│   └── Smart_City_Complaint_Analysis_Report.pdf
│
├── README.md
└── requirements.txt
```

---

## Author

**Kaveri Vadivel**

