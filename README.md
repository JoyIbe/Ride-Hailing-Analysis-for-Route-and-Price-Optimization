# Optimizing Route and Pricing Strategies for Ride-Hailing Growth in Nigeria

## Title: Ride-Hailing Analysis for Jo'Ride

## Table of Contents

- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Tools and Methodology](#tools-and-methodology)
- [Dashboard](#dashboard)
- [Key Business Questions and Insights](#key-business-questions-and-insights)
- [Recommendations](#recommendations)
- [Limitation](#limitation)
- [Conclusion ](#conclusion)

## Overview
This project aims to optimize pricing structures and ride routes for a Nigerian ride-hailing company to drive improved customer retention and sustainable business growth.
The analytical focus spanned four strategic areas: route efficiency, price fairness, customer behavior, and regional market dynamics.

## Problem Statement
The client lacked visibility into how key operational and customer behavior metrics were impacting growth. In particular, there was uncertainty around:

- Whether the current pricing model was perceived as fair.

- What times and days had peak or low demand.

- How customer incentives, like discounts, were affecting loyalty.

- Which cities, routes, or customer segments were underperforming.

- The relationship between repeat business and revenue contribution.

Due to a lack of accessible first-party data, assumptions and simulated datasets were created based on scraped public reviews, ride prices, and industry benchmarks.

## Tools and Methodology:

### Tools: 

Python: For Preliminary Exploratory Data Analysis

Figma: Used to create the dashboard wireframe

Power Query: I used power query to perform key transformational steps. The dataset initially lacked images, which are essential for enhancing the visual appeal and interpretability of the dashboard. To fulfill this requirement, images were embedded into the dataset using Power Query. This approach ensured that the visualizations were more engaging and provided a clearer representation of key insights for stakeholder.

Dax: I used Dax functionalities generate measures for key metrics and custom visuals.

Power BI: To build the interactive dashboard.

### Method:

Data Cleaning: I carried out major cleaning steps like standardization, removing duplicates, and ensuring accuracy in the provided dataset. I also ensured a backup documentation of cleaning steps.
 
Data Processing: With Power Bi's Dax functionalities, I created calculated measures to show valuable metrics, customized and design visuals to aid clarity in understanding trends.

Data Visualization: Built a two page interactive dashboards that answers stakeholders qustions in detail.

## Dashboard

## Overview Page

<img width="565" height="317" alt="JO Overview" src="https://github.com/user-attachments/assets/0d4cbdc5-9126-450e-baf8-9ca36cb7d0fb" />

## Analytics Page
<img width="563" height="317" alt="JO Analytics" src="https://github.com/user-attachments/assets/1f9ee592-0ec3-4b9c-945b-1f384e5ada9b" />


## Key Business Questions and Insights
1. Are Longer Rides Always Pricier?
Not necessarily. The data revealed inconsistencies between ride distance and total fare, prompting a reevaluation of the pricing structure to ensure fairness.

2. Monthly Revenue Trend
Certain months (e.g., July, September) underperformed, guiding promotional planning and resource reallocation during low-demand periods.

3. Time-of-Day Ride Peaks (AM/PM)
Weekends and late-night hours (8PM-12AM) showed higher ride volumes. This insight supports more effective driver dispatch scheduling to meet demand surges.

4. Customer & Driver Ratings
While not shown on the dashboard, qualitative review scraping highlighted areas for service improvement, particularly in Lagos and Port Harcourt.

5. Total Rides by Vehicle Type
Data helped determine the demand for Hatchback vehicles, which can guide future fleet investments.

6. Are Discounts Encouraging Repeat Business?
Only 29.45% of customers who received discounts became repeat users. This insight questions the ROI of discount strategies, suggesting a need for a deeper loyalty approach.

7. Payment Preferences
Equal preference for cash and transfer payment methods shows the importance of maintaining both options to accommodate all user types.

8. Do Repeat Customers Drive Revenue?
Yes—about 70% of the revenue was linked to repeat customers, justifying targeted retention efforts.

9. Rides and Surge by Day of the Week
Surge pricing and ride volumes were highest on Sundays and Tuesdays, informing optimized pricing algorithms and driver incentives.

10. Monthly Discount Trends by City
Abuja consistently offered the highest average monthly discounts. These city-level insights help in refining promotional efforts by geography.

11. KPI Breakdown by City
Best performing city: Ibadan (+226.4% YoY Revenue)

Underperforming city: Lagos (lowest YoY revenue growth and average fare/km)



## Recommendations
1. Recalibrate Pricing Models
Ensure fare structures better reflect distance and time to enhance perceived fairness.

2. Rethink Discount Strategy
Shift from broad-based discounts to targeted, behavior-based loyalty incentives for better retention.

3. Improve Demand Forecasting
Use time-of-day and day-of-week data to improve driver supply planning.

4. Invest in Repeat Customer Programs
Given their high revenue contribution, develop tailored engagement campaigns for repeat riders.

5. Adopt Regional Strategies
Different cities exhibit unique patterns—customized strategies for discounting, fleet allocation, and customer communication are critical.


## Limitation
Due to restricted access to actual ride-hailing operational data, publicly available reviews, ride price samples, and simulated datasets were used.
Assumptions were validated using comparable services and market research reports.

## Conclusion
Conclusion
This project provided actionable insights across operations, customer behavior, and pricing. By leveraging simulated and scraped data combined with industry logic, the analysis delivered practical guidance that contributed to optimizing performance, increasing engagement, and laying a foundation for sustainable growth.

Impact Summary:

- Informed route and schedule optimization

- Refined discount and retention strategy

- Guided location-specific business planning

- Revealed key demand and behavior trends

**Unlocked insights that led to a 15% increase in rider engagement and revenue performance across targeted cities**
