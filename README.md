# Power-BI-Delay-in-Production-App  

[View on Microsoft AppSource](https://appsource.microsoft.com/en-us/product/power-bi/dhyeyconsultingservicespvtltd1584430919382.delay-in-production?tab=Overview)  

[![Watch the Demo](https://img.youtube.com/vi/DzmJWCtGLks/0.jpg)](https://youtu.be/DzmJWCtGLks?si=1jHD9FHUU08e-Ru5)  

---

## Overview  

Delays in production can ripple across supply chains, leading to cost overruns and unsatisfied customers. The **Delay in Production Dashboard** provides operations and production leaders with critical insights into what’s slowing down deliveries, how often it's happening, and where interventions are needed most.  

By uncovering time loss patterns and common delay reasons, this Power BI app enables continuous improvement, proactive scheduling, and increased reliability in production workflows.  

---

## Technical Framework  

This dashboard uses a structured model named **Production Info**, designed to capture key data points on order delays.  

**Key components:**  
- **Data Source:** Excel file or system export detailing production order lifecycle and delay reasons  
- **Data Preparation (Power Query):**  
  - Cleaned date and text fields  
  - Calculated total delivery days and delay time  
  - Bucketed delays into 0–30, 30–60, 60–90, and 90+ days  
  - Categorized delay causes (e.g., Labor Shortage, Weather, Raw Material)  
- **Data Model Dimensions:**  
  - Order ID  
  - Order Placement Date  
  - Delivery Date  
  - Target Days  
  - Total Days to Delivery  
  - Delay Time  
  - Delivery Status  
  - Reason for Delay  

This setup supports flexible filtering, drill-down analysis, and integration with ERP or MES systems.  

---

## Interactive Filters  

The dashboard includes essential slicers for focused analysis:  
- **Delivery Status Filter:** Distinguish between delivered and undelivered orders  
- **Reason for Delay Filter:** Focus on specific causes such as customs, labor, or supplier-related issues  

These controls help narrow investigations and drive targeted process improvements.  

---

## Dashboard Highlights  

**KPI Tiles – Delivery Performance Overview**  
- Avg. Total Days to Delivery – End-to-end order fulfillment duration  
- Avg. Delay Time – Average number of delayed days  

**Line Chart – Average Delay by Reason**  
- Visualize which delay reasons contribute the most time loss  

**Combo Chart – Frequency vs Impact**  
- **Bar:** Number of delayed orders by reason  
- **Line:** Total delay time across each reason  
- Identify which issues are both frequent and time-intensive  

This dashboard drives smarter production planning and fosters a culture of accountability—allowing teams to minimize disruptions, set accurate expectations, and ensure on-time delivery through data-informed decisions.  

---

## Screenshots  

### Dashboard Overview  
![Dashboard Overview](https://github.com/SuperfiedStudd/Power-BI-Delay-in-Production-App/blob/main/docs/dashboard_overview.png?raw=true)   

---

## How to Use  

This repository is intended as a showcase:  
1. Watch the demo video above for a walkthrough.  
2. Explore the screenshots for dashboard views.  
3. Try the published app directly on [Microsoft AppSource](https://appsource.microsoft.com/en-us/product/power-bi/dhyeyconsultingservicespvtltd1584430919382.delay-in-production?tab=Overview).  
   - You can download and play around with the app if you have a school or work account that supports Microsoft apps.  

---

## Why It Matters  

Delays in production don’t just impact timelines—they create cascading effects across suppliers, customers, and costs. This dashboard enables leaders to pinpoint root causes, address systemic inefficiencies, and foster a more reliable production system.  

---

## Author  

Developed by **Jasjyot Singh**  
Contact: jasjyotsingh.work@gmail.com  
