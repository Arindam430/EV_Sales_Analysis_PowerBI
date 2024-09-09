# 🚗 Electric Vehicle Sales Analysis - PowerBI

As part of the Codebasics Monthly Resume Challenge #12, I worked on this Electric Vehicle Sales Analysis project.

📌 [Challenge Link](https://codebasics.io/challenge/codebasics-resume-project-challenge)  
📊 [Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYTBkNmY2OTgtZjE3MS00M2UxLWEyYjMtNTQ0Y2IzOTkwNjdhIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)  
🔗 [LinkedIn Post](https://www.linkedin.com/posts/arindam430_electric-vehicle-sales-analysis-activity-7237154748016013315-mLLI?utm_source=share&utm_medium=member_desktop)

## 📝 Problem Statement

AtliQ Motors, a prominent automotive leader from the USA specializing in electric vehicles, has seen its market share in North America's electric and hybrid vehicle segment grow to 25% over the past five years. As part of its global expansion, the company aims to introduce its top-selling models in India, where its current market share is below 2%. To support this initiative, AtliQ Motors conducted an in-depth study of the existing EV and hybrid vehicle market in India.

### 📋 Task List

As a data analyst, I was provided with sample data and a PDF containing primary and secondary business questions. My task was to complete the following:

- Develop metrics based on the primary and secondary questions provided by the business stakeholders.
- Create a dashboard following the stakeholder mock-up, ensuring it is self-explanatory and easy to understand.
- Generate additional insights beyond the provided metrics and mock-up. I could incorporate additional data from my own research to support my recommendations.

### 🗄️ Dataset Understanding

Understanding the available data is crucial before analysis. Here's a breakdown:

- **Dimension Table**: Contains static data related to dates and fiscal years.
- **Fact Table**: Includes electric vehicle sales data from manufacturers and states.

#### dim_date

- 🌍 `date`: Ranges from April 1, 2021, to March 1, 2024.
- 👥 `fiscal_year`: Since the company's fiscal year starts in April, the fiscal years listed are from 2022 to 2024.
- 📅 `quarter`: Corresponds to the fiscal years' quarters.


#### Electric Vehicle Sales by State

- 🗓️ `Date`: The date on which the data was recorded (Format: DD-MMM-YY). Data is recorded monthly.
- 🏙️ `State`: The name of the state where the sales data is recorded, representing the geographical location within India.
- 🚗 `vehicle_category`: Indicates whether the vehicle is a 2-Wheeler or a 4-Wheeler.
- 🔋 `electric_vehicles_sold`: The number of electric vehicles sold in the specified state and category on the given date.
- 📊 `total_vehicles_sold`: The total number of vehicles (both electric and non-electric) sold in the specified state and category on the given date.

#### Electric Vehicle Sales by Makers

- 🗓️ `Date`: The date on which the sales data was recorded (Format: DD-MMM-YY). Data is recorded monthly.
- 🚗 `Vehicle Category`: Indicates whether the vehicle is a 2-Wheeler or a 4-Wheeler.
- 🏭 `Maker`: The name of the manufacturer or brand of the electric vehicle.
- 🔋 `Electric Vehicles Sold`: The number of electric vehicles sold by the specified maker in the given category on the given date.

### Additional Calculated Metrics:
- `Penetration Rate`: This metric represents the percentage of total vehicles that are electric within a specific region or category. It is calculated as:
<p align="center">
    <img src='https://github.com/Arindam430/EV_Sales_Analysis_PowerBI/blob/main/Resources/Penetration%20Rate%20Formula.png' height="100">
</p>

### 📥 Importing Data into PowerBI

Imported three CSV files from SharePoint directly into PowerBI using the required account credentials.

## 🗂️ Data Model

<p align="center">
    <img src='https://github.com/Arindam430/EV_Sales_Analysis_PowerBI/blob/main/Resources/Data%20Model.png' height="400">
</p>

## 📊 Home Page

<p align="center">
    <img src='https://github.com/Arindam430/EV_Sales_Analysis_PowerBI/blob/main/Resources/1.%20Home%20Page.gif' width="600">
</p>

## 🏭 Makers Page

<p align="center">
    <img src='https://github.com/Arindam430/EV_Sales_Analysis_PowerBI/blob/main/Resources/2.%20Makers%20Page.gif' width="600">
</p>

## 🏙️ States Page

<p align="center">
    <img src='https://github.com/Arindam430/EV_Sales_Analysis_PowerBI/blob/main/Resources/3.%20States%20Page.gif' width="600">
</p>

## 🌍 Statewise Comparison Page

<p align="center">
    <img src='https://github.com/Arindam430/EV_Sales_Analysis_PowerBI/blob/main/Resources/4.%20Statewise%20Comparison%20Page.gif' width="600">
</p>
