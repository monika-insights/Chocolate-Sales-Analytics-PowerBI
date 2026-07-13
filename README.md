# Chocolate Sales Analytics Dashboard 🍫
An end-to-end Business Intelligence dashboard built with Microsoft Power BI to analyze chocolate sales performance across products, countries, sales representatives, and shipment activities through interactive visualizations and KPI-driven insights.

## 📑 Table of Contents

- [📖 Project Overview](#-project-overview)
- [🎯 Business Problem](#-business-problem)
- [🎯 Project Objectives](#-project-objectives)
- [📊 Dashboard Preview](#-dashboard-preview)
- [⭐ KPI Summary](#-kpi-summary)
- [📸 Dashboard Pages](#-dashboard-pages)
- [🧩 Data Model](#-data-model)
- [💡 Business Insights](#-business-insights)
- [📊 Business Value](#-business-value)
- [✨ Key Dashboard Features](#-key-dashboard-features)
- [🛠️ Tools & Technologies](#️-tools--technologies)
- [🚀 Skills Demonstrated](#-skills-demonstrated)
- [📂 Repository Structure](#-repository-structure)
- [👩‍💻 About the Author](#-about-the-author)



# 📖 Project Overview

The Chocolate Sales Analytics Dashboard is an end-to-end Business Intelligence project developed using Microsoft Power BI to transform raw sales data into meaningful, interactive insights. The dashboard provides a comprehensive view of business performance by analyzing sales across products, countries, sales representatives, and shipment activities through dynamic visualizations and KPI tracking.

The project demonstrates the complete data analytics workflow, including data cleaning and transformation with Power Query, data modeling to establish relationships between tables, and the creation of DAX measures to calculate key performance indicators. Interactive filters and slicers enable users to explore data from multiple perspectives, making the dashboard both user-friendly and insightful.

Designed with a focus on business decision-making, the dashboard helps stakeholders monitor sales performance, identify high-performing products and regions, evaluate salesperson contributions, and uncover trends that support strategic planning. This project showcases my ability to build scalable, interactive reporting solutions while applying data visualization best practices and analytical thinking to solve real-world business challenges.


# 🎯 Business Problem

This project simulates a business scenario in which a chocolate company generates large volumes of sales data across multiple products, countries, sales representatives, and shipment records. As the business grows, the data becomes increasingly difficult to analyze in its raw transactional format, making it challenging for stakeholders to efficiently monitor performance, identify sales trends, and make timely, data-driven decisions.

Without a centralized reporting solution, answering key business questions—such as which products generate the highest revenue, which countries contribute most to sales, how individual sales representatives perform, and how shipment activity impacts overall performance—requires significant manual analysis and is both time-consuming and prone to error.

To address these challenges, an interactive Power BI dashboard was developed to transform raw sales data into a centralized, user-friendly reporting solution. The dashboard provides clear visibility into key performance indicators (KPIs), enables interactive analysis across multiple business dimensions, and supports stakeholders in monitoring performance, identifying trends, and making informed business decisions.

Dataset 1 :   <img width="958" height="367" alt="Dataset 1" src="https://github.com/user-attachments/assets/7e62877e-1990-4996-8d9c-139950d5762d" />  Dataset 2 :   <img width="953" height="337" alt="Dataset 2" src="https://github.com/user-attachments/assets/2c31c94c-f9ef-44de-aa20-cf7644b98b23" />  Dataset 3 :   <img width="959" height="364" alt="Dataset 3" src="https://github.com/user-attachments/assets/caf02cae-5c83-42b0-8033-ec5adbfdb7d0" />

Fig 1, 2, 3 : Preview of the sample dataset used for analysis. The original dataset is excluded from this repository to respect potential licensing and redistribution restrictions.

# 🎯 Project Objectives

- Develop an interactive Business Intelligence dashboard to transform raw sales data into meaningful and actionable insights.
- Monitor key business performance indicators (KPIs), including sales, profit, shipments, and product performance.
- Analyze sales trends across products, countries, sales representatives, and shipment activities to identify business opportunities and performance patterns.
- Enable dynamic data exploration through interactive visualizations, slicers, filters, and advanced Power BI features such as Field Parameters.
- Support data-driven decision-making by providing a centralized, intuitive, and user-friendly reporting solution.
- Demonstrate end-to-end Business Intelligence development skills, including data cleaning, transformation, data modeling, DAX calculations, and interactive dashboard design.

# 📊 Dashboard Preview

The image below presents the main overview page of the Chocolate Sales Analytics Dashboard, providing a high-level summary of business performance through interactive KPIs, data visualizations, and analytical insights. The dashboard is designed to help stakeholders monitor sales performance, explore trends, and make informed, data-driven decisions through an intuitive and user-friendly interface.

<p align="center">
<img width="565" height="317" alt="Dashboard Overview" src="https://github.com/user-attachments/assets/4e727261-766f-43fb-8601-d82d7be43c7f" />
</p>

Figure 1: Overview page of the Chocolate Sales Analytics Dashboard showcasing key performance indicators (KPIs), sales trends, product performance, regional analysis, and interactive business intelligence visualizations.

# ⭐ KPI Summary

The dashboard highlights key business performance indicators (KPIs) that provide stakeholders with a quick and comprehensive overview of the company's sales performance, operational efficiency, and profitability.

<img width="472" height="84" alt="KPI Summary" src="https://github.com/user-attachments/assets/eaf55664-1a33-44ef-aefb-a06664a9d88a" />

KPI	Description

💰 Total Sales : Displays the total revenue generated from chocolate sales across all products, countries, and sales representatives.

📦 Total Boxes : Represents the total number of chocolate boxes sold, providing insight into overall sales volume and product demand.

🚚 Total Shipments : Tracks the total number of shipments completed, helping evaluate distribution activity and order fulfillment.

🏭 Total Costs : Shows the overall operational and production costs associated with generating sales, supporting cost analysis and financial planning.

💵 Total Profit : Calculates the net profit earned after deducting total costs from total sales, providing a clear measure  of business profitability.

📊 Profit Percentage : Indicates the percentage of profit generated from total sales, allowing stakeholders to assess overall business efficiency and profit margins.

📌 Additional KPI Insights 

- **Monthly Sales:** Displays the total sales generated during the current month.
- **Month-over-Month (MoM) Growth:** Compares the current month's sales with the previous month to measure short-term business growth and performance trends.

# 📸 Dashboard Pages

🏠 Dashboard Overview

<img width="565" height="317" alt="Dashboard Overview" src="https://github.com/user-attachments/assets/6e1947f3-dee9-475a-99c7-65ec042eab10" />

Description : Provides a high-level summary of sales performance, KPIs, and business metrics.

📈 Sales Analysis

<img width="562" height="315" alt="Sales Analysis" src="https://github.com/user-attachments/assets/daafd599-6145-4dd2-990a-86c5f7ec80cd" />

Description : Analyzes sales trends over time using dynamic visualizations and Field Parameters.

🍫 Product Analysis

<img width="563" height="319" alt="Product Analysis" src="https://github.com/user-attachments/assets/3ab1ea98-04cd-42db-a55d-3cac04af74f8" />

Description : Evaluates product-wise sales, revenue, and profitability to identify top-performing products.

🌍 Country Analysis

<img width="562" height="319" alt="Country Analysis" src="https://github.com/user-attachments/assets/95449995-54ca-4a6a-8c2b-dab7e8751602" />

Description : Compares sales performance across different countries and regions.

🚚 Shipment Analysis

<img width="561" height="318" alt="Shipment Analysis" src="https://github.com/user-attachments/assets/f1821e8c-5f34-4220-bd52-5e28aa7fd79d" />

Description : Visualizes shipment distribution using a histogram with a zoom slider for detailed exploration.

# 🧩 Data Model

The dashboard is built on a star schema data model, with the Shipments table serving as the central fact table and supporting dimension tables for Products, People, Locations, and Calendar. This structure establishes clear relationships between business entities, enabling efficient filtering, accurate DAX calculations, and optimized dashboard performance.

The data model follows Business Intelligence best practices by separating transactional data from descriptive dimensions, improving scalability, maintainability, and analytical accuracy. A dedicated Measures table is used to organize DAX calculations, while a Field Parameter (Measure Selector) enables dynamic metric switching for interactive trend analysis.

<p align="center">
<img width="670" height="337" alt="Data Model" src="https://github.com/user-attachments/assets/48419b20-bf97-4a02-93af-747d00edaf9f" />
</p>

Description : The data model illustrates the relationships between fact and dimension tables that power the dashboard's calculations, interactive filtering, and business insights.

# 💡 Business Insights

The Chocolate Sales Analytics Dashboard enables stakeholders to uncover actionable insights by transforming raw sales data into interactive business intelligence reports. Key analytical capabilities include :

- 📈 Sales Performance Monitoring : Track overall sales, profit, costs, shipments, and profit percentage through centralized KPI cards.
- 🍫 Product Performance Analysis : Identify top-performing and underperforming products based on sales volume, revenue, and profitability.
- 🌍 Regional Sales Analysis : Compare sales performance across countries and regions to identify high-performing markets and growth opportunities.
- 👥 Sales Representative Performance : Evaluate individual salesperson contributions to support performance tracking and informed business decisions.
- 🚚 Shipment Analysis : Analyze shipment distribution patterns using histogram visualizations to better understand operational trends and shipment volumes.
- 📅 Trend Analysis : Monitor sales performance over time using dynamic trend analysis with Field Parameters, enabling users to switch between different business metrics interactively.
- 🎯 Interactive Decision Support : Utilize slicers, filters, and cross-filtering to explore data from multiple perspectives and answer specific business questions efficiently.

# 📊 Business Value

This dashboard transforms raw sales data into an interactive Business Intelligence solution, enabling stakeholders to monitor key performance indicators, identify sales trends, evaluate product and regional performance, and make informed, data-driven decisions. By centralizing business metrics into a single reporting interface, the dashboard reduces manual analysis and provides faster access to actionable insights.

# ✨ Key Dashboard Features

- 📊 Interactive KPI Dashboard – Provides a real-time overview of key business metrics, including Total Sales, Total Boxes Sold, Total Shipments, Total Costs, Total Profit, and Profit Percentage.
- 📈 Dynamic Trend Analysis – Utilizes Field Parameters to allow users to switch between multiple business metrics within a single trend chart for flexible analysis.
- 🎛️ Interactive Filters & Slicers – Enables users to dynamically filter data by product, country, salesperson, and time period for customized reporting.
- 🍫 Product Performance Analysis – Evaluates product-wise sales, revenue, costs, and profitability to identify top-performing and underperforming products.
- 🌍 Regional Sales Analysis – Compares sales performance across countries and regions to uncover geographical trends and market opportunities.
- 👥 Sales Representative Performance – Tracks individual salesperson performance to support productivity analysis and performance evaluation.
- 🚚 Shipment Distribution Analysis – Visualizes shipment patterns using a histogram with a zoom slider, enabling detailed exploration of shipment volume distribution.
- 📅 Time Intelligence Analysis – Supports monthly sales monitoring and Month-over-Month (MoM) growth analysis to identify business trends over time.
- 🔄 Cross-Filtering & Interactive Visualizations – Selecting any visual automatically filters related charts, allowing users to explore data from multiple perspectives.
- ⚡ Optimized Data Model – Built using a star schema with dedicated dimension tables, DAX measures, and Power Query transformations to ensure efficient performance and accurate reporting.

# 🛠️ Tools & Technologies

| **Category** | **Tools / Technologies Used** |
|:-------------|:------------------------------|
| 📊 **Business Intelligence** | Microsoft Power BI Desktop |
| 📁 **Data Source** | Microsoft Excel (.xlsx) |
| 🔄 **Data Transformation** | Power Query |
| 🧩 **Data Modeling** | Star Schema, Relationship Modeling |
| 🧮 **Calculations** | DAX (Data Analysis Expressions) |
| 📈 **Data Visualization** | KPI Cards, Bar Charts, Line Charts, Donut Charts, Maps, Histograms, Tables, Field Parameters, Slicers |
| 📅 **Time Intelligence** | Calendar Table, Month-over-Month (MoM) Analysis |
| 🎨 **Design & Assets** | Microsoft PowerPoint (Custom Icons & Dashboard Assets) |
| 💻 **Version Control** | Git & GitHub |


# 🚀 Skills Demonstrated

- 📊 Business Intelligence & Dashboard Development
- 🔄 Data Cleaning & Transformation
- 🧩 Data Modeling (Star Schema)
- 🧮 DAX Measure Development
- 📈 KPI Design & Business Reporting
- 📅 Time Intelligence Analysis
- 🎛️ Interactive Dashboard Design
- 📊 Dynamic Trend Analysis using Field Parameters
- 🚚 Shipment Distribution Analysis
- 🔍 Data Exploration using Slicers & Cross-Filtering
- 💡 Business Insight Generation
- 🎨 Dashboard UI & Visual Design

# 📂 Repository Structure

```text
Chocolate-Sales-Analytics-Dashboard/
│
├── 📄 README.md
│   └── Complete project documentation
│
├── 📸 Dashboard Screenshots/
│   ├── Dashboard_Overview.png
│   ├── Sales_Analysis.png
│   ├── Product_Analysis.png
│   ├── Country_Analysis.png
│   ├── Shipment_Analysis.png
│   ├── KPI_Summary.png
│   └── Data_Model.png
│
├── 📁 Dataset Preview/
│   ├── Sales_Data.png
│   ├── Products_Data.png
│   └── People_Data.png
│
├── 🎥 Dashboard Walkthrough/
│   └── Coming Soon
```

# 👩‍💻 About the Author

**Monika A**

Junior Data Analyst with a strong foundation in **Power BI, Excel, SQL, and Business Intelligence**. Passionate about building interactive dashboards, analyzing business data, and delivering actionable insights through data visualization and analytical problem-solving.

### 📬 Connect with Me

- 💼 LinkedIn: https://www.linkedin.com/in/monika-a-3a9094301
- 💻 GitHub: https://github.com/monika-insights
