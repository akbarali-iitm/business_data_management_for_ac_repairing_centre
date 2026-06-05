# Optimizing Operational Efficiency and Seasonal Profitability for an Air Conditioner Repair Center

## Overview

This project presents a comprehensive data-driven operational analysis of an air conditioner repair center, focused on improving procurement efficiency and workforce planning through historical business data analysis.

The study was conducted using real-world operational data collected from an air conditioner servicing business, covering the period from **January 2023 to December 2024**. The objective was to identify inefficiencies in procurement and staffing practices and propose optimized, data-backed business strategies.

The project applies **statistical analysis, forecasting techniques, and mathematical optimization models** to support operational decision-making and improve cost efficiency.

> **Recognition:** This project received the **"Best Course Project for Business Data Management"** award under the **IIT Madras BS Degree Program** for excellence in applied business analytics and problem-solving.


---

## Business Problem

The business faced two major operational challenges:

### 1. Procurement Cost Management and Inventory Optimization

The repair center experienced fluctuations in spare part prices and inconsistent purchasing patterns across different seasons.

Key issues included:

* High procurement costs during peak demand periods
* Overstocking of low-demand spare parts
* Shortages of critical components during seasonal spikes
* Lack of data-driven purchasing strategies

### 2. Workforce Optimization

The business maintained a fixed workforce throughout the year despite seasonal fluctuations in service requests.

This resulted in:

* Overstaffing during low-demand periods
* Understaffing during peak summer demand
* Increased operational costs
* Service delays during high-demand months

---

## Objectives

The primary objectives of this project were:

* Analyze historical spare-part demand and pricing trends
* Identify seasonal procurement patterns
* Forecast future inventory requirements
* Optimize workforce allocation based on demand
* Reduce operational inefficiencies and unnecessary costs
* Propose a scalable, data-driven decision-making framework

---

## Dataset

The analysis was performed on **real-world business data** collected from operational records of an air conditioner repair center.

### Data Period

**January 2023 – December 2024**

### Data Categories

#### Procurement Data

* Spare part names
* Seasonal unit costs
* Historical demand
* Quantity purchased
* Procurement trends

#### Workforce Data

* Monthly service requests
* Number of hired workers
* Worker handling capacity
* Required workforce estimation
* Workforce shortage and excess analysis

The original records were manually maintained and later digitized into spreadsheets for structured analysis.

---

## Technology Stack

### Programming & Analysis

* Python
* Google Colab
* Pandas
* NumPy

### Forecasting & Optimization

* ARIMA Time Series Forecasting
* Linear Programming (Simplex Method)

### Data Visualization

* Matplotlib
* Statistical Graphs
* Seasonal Trend Analysis

---

## Methodology

### 1. Data Cleaning and Preprocessing

The raw business data was cleaned and standardized before analysis.

Key preprocessing steps included:

* Missing value handling
* Data validation
* Standardization of formats
* Type consistency checks
* Data transformation into structured datasets

---

### 2. Procurement Cost Analysis

Seasonal demand and procurement cost trends were analyzed by dividing the year into three operational periods:

* **January – March**
* **April – July**
* **August – December**

Historical pricing and demand data were analyzed to identify:

* Seasonal cost spikes
* High-demand inventory items
* Cost-efficient purchasing windows

The findings indicated that spare-part prices increased significantly during the **April–July period**, making early procurement more cost-effective.

---

### 3. Demand Forecasting Using ARIMA

To improve procurement planning, an **ARIMA (1,1,1)** time-series forecasting model was implemented.

The model was trained using historical spare-part demand data and used to forecast future inventory requirements.

This approach enabled:

* Better procurement planning
* Reduced emergency purchasing
* Prevention of overstocking
* Improved inventory utilization

---

### 4. Workforce Optimization

Monthly service demand was analyzed to calculate the required workforce based on worker capacity.

The formula used:

```text
Required Workers =
Total Service Requests / Requests Handled Per Worker
```

A **Linear Programming (LP)** model using the **Simplex Method** was developed to optimize staffing levels while minimizing labor costs.

The proposed workforce strategy included:

* Maintaining a lean permanent workforce
* Hiring temporary staff during peak demand periods
* Reducing idle labor costs

---

## Key Findings

### Procurement Insights

* Demand consistently peaked during the **April–July** period.
* Spare-part prices increased significantly during peak seasons.
* Strategic early procurement can reduce operational costs.

### Workforce Insights

* Fixed staffing resulted in inefficiencies.
* Peak months required significantly higher workforce capacity.
* Off-season periods suffered from workforce excess and unnecessary salary expenditure.

### Recommended Strategy

A hybrid operational model was proposed:

* Forecast-based procurement planning
* Seasonal purchasing optimization
* Dynamic workforce allocation
* Contract-based staffing during peak demand

---

## Results

The project successfully demonstrated how data-driven decision-making can improve operational efficiency in service-based businesses.

Expected business improvements include:

* Lower procurement costs
* Better inventory management
* Reduced workforce inefficiencies
* Improved seasonal preparedness
* Enhanced operational profitability

---

## Repository Structure

```text
├── dataset/
│   ├── procurement_data.csv
│   └── workforce_data.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── reports/
│   ├── proposal_report.pdf
│   ├── midterm_report.pdf
│   └── final_report.pdf
│
├── visuals/
│   ├── seasonal_demand_analysis.png
│   ├── arima_forecast.png
│   └── workforce_optimization.png
│
├── src/
│   ├── preprocessing.py
│   ├── forecasting.py
│   └── workforce_optimization.py
│
├── requirements.txt
└── README.md
```

---

## Recognition

This project was recognized as the **Best Course Project for Business Data Management** under the **IIT Madras BS Degree Program**.

The recognition was awarded for the effective application of:

* Data Analytics
* Business Problem Solving
* Forecasting Techniques
* Optimization Models
* Real-world Data-Driven Decision Making

The project demonstrated practical implementation of statistical modeling and operational optimization using authentic business data from an air conditioner service center.

---

## Future Improvements

Potential future enhancements include:

* Machine learning-based demand forecasting
* Interactive business dashboard using Power BI or Streamlit
* Real-time inventory monitoring system
* Automated procurement recommendations
* Workforce scheduling automation

---

## Academic Context

This project was completed as part of the **Business Data Management (BDM) Capstone Project** under the **IIT Madras BS Degree Program**.

The project focused on solving a real-world business optimization problem through applied analytics, forecasting, and mathematical optimization techniques.

The work was later recognized as the **Best Course Project for Business Data Management**, highlighting its practical impact, analytical depth, and real-world applicability.


---

## Author

**Akbar Ali**

BS Degree Program
Indian Institute of Technology Madras
