# Call Center KPI Dashboard

### Dashboard Link: https://app.powerbi.com/groups/me/reports/b9ff04a2-8095-4f33-8bbb-369ad49be4dd/ReportSectione719ef80db76ae2815d3?experience=power-bi

##  Overview
The **Call Center KPI Dashboard** provides actionable insights into call center performance, agent efficiency, and customer satisfaction. This dashboard enables call center managers to track key metrics and make data-driven decisions to improve operations and enhance customer experience.

##  Problem Statement
Call centers handle thousands of interactions daily, making it crucial to monitor agent performance and service quality. This dashboard helps:
- Identify areas needing improvement in customer satisfaction.
- Analyze average call handling and resolution times.
- Track agent efficiency and workload distribution.
- Detect patterns in call volume and peak hours to optimize staffing.

##  Key Insights
-  **Average Handling Time (AHT)**: Insights into call duration trends.
-  **Agent Performance Metrics**: Productivity and efficiency evaluation.
-  **Customer Satisfaction Analysis**: Rating trends from post-call surveys.
-  **Call Resolution Time**: How quickly issues are resolved.
-  **Call Trends & Peak Hours**: Identifying high-traffic periods for resource optimization.

##  Steps Followed in Power BI Development

### **Step 1: Data Preparation**
- Imported call center dataset (CSV file).
- Used Power Query to clean and preprocess data.
- Checked for null values and applied necessary transformations.

### **Step 2: Data Exploration**
- Enabled **Column Quality, Distribution, and Profile** in Power Query Editor.
- Verified missing values; handled NULLs in **Call Resolution Time** and **Customer Ratings** fields.

### **Step 3: KPI Calculation & DAX Measures**
- **Agent Utilization Rate** = `(Total Talk Time / Available Time) * 100`
- **Average Handling Time (AHT)** = `Total Call Duration / Number of Calls`
- **First Call Resolution (FCR)** = `Resolved Calls on First Attempt / Total Calls`
- **Customer Satisfaction Score (CSAT)** = `Average(Customer Ratings)`


# Report 

### **Call Center KPI Overview**
<img width="1093" alt="Image" src="https://github.com/user-attachments/assets/5f845e36-19fa-4ab5-be8a-af3c372f9309" />

count of call center answered calls 
<img width="1108" alt="Image" src="https://github.com/user-attachments/assets/bfc75350-292a-4e2b-9d27-fa3c0aa19886" />

Count of total resolved calls
<img width="992" alt="Image" src="https://github.com/user-attachments/assets/ee621034-1de2-4591-bea8-9dae19082dea" />

Average speed of answer (in seconds)
<img width="265" alt="Image" src="https://github.com/user-attachments/assets/28202d0a-40b3-4905-b3d9-7806b3411a13" />

Average satisfaction rating
<img width="1091" alt="Image" src="https://github.com/user-attachments/assets/26a26ba3-4e2e-44b6-9f52-855e28c9c91c" />

Count of answered calls per Month
<img width="1244" alt="Image" src="https://github.com/user-attachments/assets/fb397098-2a49-4daa-b3be-513c9fb6a2a4" />

### **Agent Performance Insights**
<img width="579" alt="Image" src="https://github.com/user-attachments/assets/a0009db1-5ef6-4aec-b14c-9d4fe4c0b3d3" />

## 🔗 Installation 
1. **Download & Install Power BI Desktop**: [Power BI Download](https://powerbi.microsoft.com/)
