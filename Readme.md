#  Delivery Performnace Report - Dashboard

## 📌Table of Contents
- [Overview](#overview)
- [Objective](#objective)
- [Project Structure](#project-structure)
- [Datasets](#datasets)
- [Business Problem](#business-problem)
- [Tools & Technologies](#tools--technologies)
- [Key Insights](#key-insights)
- [Dashboard](#dashboard)
- [How to Run This Project](#how-to-run-this-project)
- [Author & Contact](#author--contact)

---

## Overview
<p align="justify">
This Power BI dashboard is designed to evaluate and track delivery performance metrics. It provides actionable insights into delivery operations, enabling teams to monitor efficiency, identify bottlenecks, and enhance overall service quality.
</p>

---

## Objective
<p align="justify">

1. **Import Data** - Use Power Query to import the raw data from your SQL database or local host into the Data pane.

2. **Data Cleaning** - Utilize Power Query Editor to refine, clean, and structure the dataset, ensuring it is ready for analysis and meaningful insights.

3. **Data Visualization** - Use the Visualization pane to build a compelling visual story. It enables the business to track the sales performance, identify growth opportunities, and make data-driven decisions..

</p>
--- 

## Project Structure
```
Delivery-Performance-PowerBI-Dashboard-Project2/
│
├── 1) Datasets /           #Excel Data File
│      └── Delivery Performance Report.xlsx
│
├── Images /           #Folder
│       ├── Icon /
│       └── Dashboard.PNG   
│   
├── Delivery Performance - Dashboard.pbix   #PowerBi file        
├── README.md


```

---

## Datasets

<p align="justify">

1. Delivery Performance Report – An Excel workbook with four sheets, each holding specific parameters:
- Order Sheet – Serves as the fact table, containing purchase order data along with foreign keys linking to all dimension tables.
- City Sheet – A dimension table that stores city-related data.
- Product Sheet – A dimension table that provides product details.
- Delivery Sheet – A dimension table listing delivery personnel and the companies they work for.

</p>

---

## Business Problem

- Track key performance indicators (KPIs) – Analyze average delivery time, revenue generated, total quantity sold, and total transactions.
- Trend Analysis – Monthly, quarterly, and yearly comparisons
- Interactive Reports – Filter by month, category, and payment mode.
- Data-Driven Decisions – Identify improvement areas to optimize operations.


---

## Tools & Technologies

1. Microsoft Power BI Features:
- Power Query – Data Loading
- Power Query Editor – Data Cleaning & Transformation

2. Power BI Core Functions:
- Report View – Dashboard Building
- Model View – Relationship Creation
- Measures & Columns (DAX) – Calculations & Formulas
- Slicers – Data Filtering

3. Version Control & Collaboration:
- GitHub – Project Hosting & Sharing

---

## Key Insights

- Monthly Trends:
    - During the summer season, customers show a higher preference for e-commerce when purchasing daily essentials.
    - Online deliveries drop to their lowest levels in October and November.
- City: Demand for online delivery is growing rapidly in metropolitan areas.
- Product: Milk, Eggs, and Paneer are the most frequently ordered items through online delivery.
- Payment Mode: Customers are shifting towards UPI and Credit Card payments, while reliance on cash continues to decline.
- Weekday Trends:
    - Thursday records the highest number of purchases.
    - Monday sees the lowest purchase activity.


---

## Dashboard
![Dashboard Preview](Images/Dashboard.PNG)

---

## How to Run This Project
1. Download the .pbix file from this repository.
2. Open it in Power BI Desktop.
3. Explore the dashboard and interact with filters, slicers, and charts.
4. Use Slicer to filter data by
    - Year
    - Month
    - Category
    - Payment Mode
5. Download the data file from this repository.
6. Change the Data Source Location, to load the data in Power Query .
7. Utlize the Power Query to transform the data.
8. Use Dax Formula, to create custom calculation on the data.

---
    
## Author & Contact

**Sagar Kumar Mandle** <br>

  
📧 Email: sagarmandle11135@gmail.com 

🔗 [LinkedIn](https://www.linkedin.com/in/sagar-kumar-mandle-7086ba366/)


