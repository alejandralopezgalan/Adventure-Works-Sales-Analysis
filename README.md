# Adventure Works Sales Analysis
Excel-based analysis of four years of Adventure Works transactional data

<img src="assets/img/project5_ecommerce.png" width="500" height="600" />

Image from [storyset](https://storyset.com/illustration/ecommerce-web-page/amico)

> **Note**
>
> This project was guided by a tutorial from Ismaila Omeiza M. - Data with Decision [YouTube channel](https://www.youtube.com/watch?v=VxOOt2dP8Jw&ab_channel=DatawithDecision). which provided clear, structured instruction on conducting sales analysis using Excel. The hands-on walkthrough helped deepen my understanding of dashboard design and data storytelling using transactional data
>
> Original Project:
> 
> Title: Data Analysis Project in Excel - Build Interactive Dashboard. Author: Ismaila Omeiza M. - Data with Decision. Platform: [YouTube](https://www.youtube.com/@datalab365).
>
> The original tutorial offered an excellent foundation for building practical data analysis skills. Full credit goes to Data with Decision for the methodology, design approach, and dataset structure. You can explore more of their content on their [YouTube Channel](https://www.youtube.com/@datalab365).
<br/>

## Table Of Contents
- [Executive Summary](#executive-summary)
  - [Primary Goal](#primary-goal)
  - [Solution](#solution)
  - [Key Findings](#key-findings)
  - [Recommendations](#recommendations)
- [Introduction](#introduction)
  - [Business Problem](#business-problem)
  - [Goals](#goals)
- [Methodology](#methodology)
  - [Data Source](#data-source)
  - [Tools](#tools)
  - [Data Cleaning and Transformation](#Data-cleaning-and-transformation)
  - [Data Analysis](#data-analysis)
  - [Excel Formulae](#excel-formulae)
  - [Data Visualisation](#data-visualisation)
- [Insights](#insights)
- [Action Plan](#action-plan)
  - [1. Customer Acquisition Strategy](#1.Customer-Acquisition-Strategy)
  - [2. Boosting Sales in Q4](#2.-Boosting-Sales-in-Q4)
  - [3. Product and Shipping Optimisation](#3.-Product-and-Shipping-Optimisation)
  - [4. Maximising Regional Performance](#4.-Maximising-Regional-Performance)
  - [5. Customer Retention Initiatives](#5.-Customer-Retention-Initiatives)
- [Excel Report](#excel-report)	


## Executive Summary
### Primary Goal
The main goal is to develop a functional and visually engaging Excel dashboard that analyses four years of transactional sales data from Adventure Works. It focuses on refining data interpretation skills, enhancing storytelling through visualisations, and applying structured methodologies for business insight generation. The dashboard is designed to highlight key performance patterns and support data-informed decision-making.


### Solution
This project delivers a comprehensive Excel dashboard tailored for sales data analysis using the Adventure Works dataset. Through a guided methodology, the dashboard offers:
- Visual representations of profit trends across products, regions, and time periods
- Interactive features that allow users to filter and explore data dynamically
- Structured insights to support business-oriented decision-making
- A clear demonstration of analytical thinking and visualisation techniques in Excel

The approach bridges foundational data skills with professional-level presentation, transforming raw transactional data into accessible and insightful business intelligence.

### Key Findings


### Recommendations


## Introduction
### Business Problem
Adventure Works, a multinational retail company, manages a diverse product portfolio across several global regions. However, the organisation faces challenges in identifying key profit drivers and regional performance disparities over time. Without a cohesive and accessible method for analysing historical sales data, stakeholders struggle to make informed decisions regarding product strategy, regional investment, and seasonal demand planning. This project addresses the need for a visually intuitive dashboard that consolidates four years of transactional data, enabling clearer insight into sales trends and unlocking opportunities for data-driven decision-making.

### Goals
- Summarise Multi-Year Sales Performance: Present a high-level overview of Adventure Works' sales trends over a four-year period to help users quickly grasp historical performance.
- Highlight Profit Drivers by Category and Region: Identify which product categories and geographical markets contributed most significantly to revenue generation.
- Enable Dynamic Data Exploration: Integrate interactive Excel features (e.g. slicers, filters) to allow users to customise views and explore specific timeframes, regions, or product groups.
- Reveal Seasonal and Temporal Patterns: Analyse time-based trends to uncover seasonal spikes or declines in sales, guiding future planning and promotional activities.
- Support Strategic Decision-Making: Provide actionable insights through visualisations that help stakeholders evaluate investment, inventory, and marketing strategies.
- Create a Visually Intuitive Dashboard Experience: Ensure the layout is clean, coherent, and easily navigable—making the dashboard approachable for users with varying data literacy levels.

## Methodology
### Data source
The dataset used in this project was provided as part of a tutorial from the Data with Decision [YouTube channel](https://www.youtube.com/watch?v=VxOOt2dP8Jw&ab_channel=DatawithDecision). It features transactional sales records from the fictional company Adventure Works, commonly employed in training scenarios for data analysis and dashboard development. All data was made available for educational purposes and aligns with the instructional content presented in the original video.

### Data Overview
The project utilises the [AdventureWorks.xlsx](https://github.com/alejandralopezgalan/Adventure-Works-Sales-Analysis/blob/main/assets/data/Project5_AdventureWorks_Database.xlsx) workbook, which contains six relational tables:
- **FactInternetSales:** The central fact table containing transactional records, linked to other tables through keys such as ProductKey, CustomerKey, SalesTerritoryKey, and date fields. It stores detailed sales metrics including quantities, discounts, costs, and revenue values.
- **DimCustomer:** Contains customer demographics and contact information, such as name, birth date, marital status, education level (in multiple languages), occupation, income, address, purchase history, and commute distance. Linked via CustomerKey.
- **DimDate:** A calendar table used for time-based analysis. Includes fields for full dates, day names (English, Spanish, French), month details, calendar and fiscal periods, and date keys to support flexible filtering.
- **DimProduct:** Stores product-level attributes including category, colour, size, cost, pricing, manufacturing details, multilingual descriptions, and availability dates. Linked to transactions through ProductKey.
- **DimGeography:** Provides geographical context for customers, with data on city, state, country, postal code, and regional identifiers. Includes country names in English, Spanish, and French.
- **DimSalesTerritory:** Offers higher-level breakdowns of global sales regions, including territory name, country grouping, and visual identifiers to support regional analysis.


All tables form an integrated data model that enables robust cross-dimensional analysis. The dataset is fictional and provided exclusively for educational purposes, aligning with the structure and learning goals outlined in the original YouTube tutorial and this project. It serves as a practical foundation for developing analytical capabilities, data visualisation skills, and professional dashboard design in a simulated business context.

### Tools
- Microsoft Excel: Utilised for exploring, cleaning, transforming, and visualising the data through an interactive dashboard. The project also incorporates Power Query to load and shape multiple relational tables efficiently, forming the foundation of the data model

### Data Cleaning and Transformation
Power Query was used to load the six relational tables from the AdventureWorks workbook, establish connections, and select only the columns relevant to the dashboard analysis. 

**Selected Columns for Analysis**
From each table, only the fields necessary for visualisation and performance insights were retained:
- **FactInternetSales:** ProductKey	OrderDateKey	DueDateKey	ShipDateKey	CustomerKey	SalesTerritoryKey	OrderQuantity	UnitPrice	Cost	

- **DimCustomer:** 
- **DimDate:** 
- **DimProduct:** 
- **DimGeography:** 
- **DimSalesTerritory:** 






