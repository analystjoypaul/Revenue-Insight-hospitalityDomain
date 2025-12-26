# Revenue Insights - Hospitality Domain 

## Project Overview
This project focuses on building an **end-to-end Revenue Insights Dashboard** for a hospitality company using **Power BI**.  
The dashboard enables leadership to track revenue sources, occupancy, booking behavior, and operational KPIs across cities, hotels, room types, and time periods.

The project uses **realistic hotel booking data (May 2022 – July 2022)** and applies data cleaning, modeling, DAX measures, and interactive visualizations to support **data-driven business decisions**.

![Revenue Insight](https://github.com/analystjoypaul/Revenue-Insight-hospitalityDomain/blob/main/revenue_insight.png)
##  Business Context
**AtliQ Hotels** owns multiple hotel chains across various cities in India.  
The **Managing Director** wanted to incorporate **Business Intelligence & Data Analytics** to:

- Identify revenue sources
- Track performance across locations and platforms
- Monitor occupancy, cancellations, and customer behavior
- Enable strategic decision-making using KPIs



##  Business Objective
Develop a **KPI-driven Power BI Dashboard** that:
- Tracks revenue and booking performance
- Provides both **high-level** and **granular insights**
- Allows stakeholders to slice and dice data using filters
- Highlights actionable insights for revenue growth



## Problem Statement / Project Scope
- Identify relevant data sources for revenue management
- Clean and transform raw data for analysis
- Build a robust data model
- Create a dynamic and interactive revenue dashboard
- Enable filtering by multiple business dimensions



## Dataset Description
The project uses **5 tables**:

### Dimension Tables
- **Date**
- **Hotel**
- **Room**

### Fact Tables
- **Bookings**
- **Aggregated Bookings**



## Tools & Technologies
- **Power BI**
- **Power Query** – Data cleaning & transformation
- **Power Pivot** – Data modeling & relationships
- **DAX** – KPI calculations and measures



## Data Processing & Modeling
- Cleaned and transformed data using **Power Query**
- Built star-schema relationships using **Power Pivot**
- Ensured correct granularity and data integrity for analysis



## Key Measures & KPIs (DAX)

### Core Metrics
- **Revenue** = Sum of `revenue_realized`
- **Total Bookings** = Count of `booking_id`
- **Average Rating**
- **Total Capacity**
- **Total Successful Bookings**

### Derived Metrics
- **Occupancy Rate (%)**
- **Total Cancelled Bookings**
- **Cancellation Rate (%)**
- **Average Stay Duration (Days)**



## Dashboard Features & Visuals

### Visualizations Included
- **Revenue by Platform** – Bar Chart
- **Revenue by Room Type** – Donut Chart
- **Bookings by Status** – Pie Chart
- **KPI Matrix** – City & Hotel-level performance
- **KPI Cards** – Revenue, Occupancy, Ratings, Bookings

### Filters / Slicers
- Month-Year
- City
- Room Type
- Week Number

> All visuals are **interactive** and dynamically update based on filters.



## Key Business Insights

### Revenue & Location
- **Mumbai** generated the highest revenue.
- **Delhi** generated the least revenue despite high occupancy.
- Action: Focus on monetization strategies in Delhi.

### Occupancy & Booking Behavior
- Occupancy is **consistently higher on weekends**.
- Opportunity to increase weekend pricing or promotions.

### Booking Outcomes
- **70%** of bookings result in checkouts.
- **5%** are no-shows.
- **75%** of bookings generate revenue.
- Action: Analyze and reduce cancellations.

### Customer Experience
- Average rating ranges between **3.4 – 3.8**.
- Average stay duration is **2.4 days**.
- Compare performance with industry benchmarks.


##  Business Impact
- Enabled leadership to track revenue drivers in real time
- Improved visibility into occupancy and cancellations
- Supported strategic decisions on pricing, promotions, and city-level focus
- Demonstrated strong use of **Power BI, DAX, and business analytics**


##  Dashboard Preview
*(Add Power BI screenshots or GIFs here)*



## Conclusion
This project showcases the complete **BI lifecycle** — from raw data to actionable insights — and demonstrates strong skills in:
- Business understanding
- Data modeling
- DAX calculations
- Dashboard storytelling


## Author
**Joy Paul**  
Data Analyst   



## Useful Links
- LinkedIn: https://www.linkedin.com/in/joy-paul-analytics/

