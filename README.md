# Zoomcharts-CRM-Data Visualization Project Report

## Title:
CRM Sales Performance for the Year 2024 Dashboard 
## Objective:
To analyze and evaluate the performance of the sales team across countries, industries, and agents to uncover insights that can help optimize deal closure rates, reduce lost leads, and improve sales conversion efficiency.
---
## Problem Statement
- What is the overall conversion rate of sales leads across countries and agents?
- Which industries and products generate the most closed deals?
- Which agents are top performers in terms of deal value closed?
- What is the average deal cycle duration and how can it be reduced?
- Where are we losing the most leads in the sales funnel?
---
## Tools Used
Power BI
---
## Visualization Approach
- I loaded the data  into Power BI.
- I used DAX for calculating KPIs such as Total Closed Deal Value, Conversion Rate, Lost Leads %, and Avg Days to Close a Deal.
- I Created KPI cards for quick insights:
  - Total Deals: 3000
  - Total Deal Closed: $931,275
  - Conversion Rate: 11.60%
  - Avg Days to Close a Deal: 63.17
  - Avg Deal Value: $2,758.4
  - Lost Leads %: 2.03%
- I used Bar Charts to visualize:
    - Deal Value Closed by Agent
    - Closed Deal Value by Industry
    - Leads by Stage (Sales Funnel)
- I used a Pie Chart to represent:
     - Product Distribution by Closed Deals (SAAS, Services, Custom Solutions)
- I used Matrix Table:
    - Country-wise breakdown of total leads, deals closed, conversion rate, avg. time to close, lost leads %, and avg deal value.
- Then I added Filters based on:
    - Country, Product, Month, Industry, Agent, Organization
---
## Dashboard Picture 
![Dashboard](Screenshot%20(90).png)
## Key Observations
- France and Germany have the highest number of leads (474 and 420 respectively), but Italy has the highest Closed Deal Value ($220.01K) with a strong average deal value ($2,751.16).
- Switzerland has the highest Conversion Rate at 13.16%, followed closely by Italy (13.75%) and Netherlands (15.00%).
- Laura Thompson and Michael Brown lead the sales agents in total deal value closed.
- Transportation, Banking, and Government sectors show the highest closed deal values by industry.
- SAAS (38.36%) and Custom Solutions (38.16%) dominate product-wise closed deals.
- In the sales funnel, Initial Contact (220) and Nurturing (140) stages show the highest drop-off, signaling potential bottlenecks.
- Overall conversion rate is 11.60%, indicating room for improvement.
- Lost Leads % is low (2.03%), suggesting relatively efficient sales engagement.
---
## Summary of Findings
- Strong deal value performance in Italy, Switzerland, and the Netherlands.
- Transportation and Banking sectors are critical drivers of closed revenue.
- Most deals are closed in SAAS and Custom Solution segments, with lesser traction in Services.
- Some sales agents (Laura, Michael) significantly outperform others — clear best-practice candidates.
- Majority of leads drop off at the early stages (Initial Contact, Nurturing).
- Average time to close (63.17 days) may be optimized further through streamlined processes.
---
## Recommendations
- Improve Conversion Rate:
    - Provide sales training focused on early-stage lead conversion.
    - Use targeted automation for lead nurturing to reduce drop-offs.
- Enhance Agent Performance:
    - Study practices of top agents like Laura Thompson and replicate across the team.
    - Introduce performance-based incentives tied to deal values and conversion rates.
- Target High-Performing Industries:
    - Focus more efforts on Transportation, Banking, and Government sectors.
    - Customize offerings for industry needs to increase penetration.
- Product Strategy:
    - Invest more in SAAS and Custom Solutions marketing, as they yield higher closed deals.
    - Review why Services underperform and adjust product-market fit or sales approach.
- Funnel Optimization:
    - Analyze bottlenecks at Initial Contact and Nurturing stages.
    - Introduce AI-based lead scoring and qualification to accelerate funnel movement.
---
## Data Source
ZoomCharts Data Competition 
---
## Technical Details
- Tool Used : Power Bi
- Visuals used : Card KPIs, Bar Charts, Pie Chart, Matrix Table
- Techniques Displayed: DAX Calculations, Filtering, Slicer Panels, Custom Measures
- Dataset used: CRM_data, Date Table
- Features Used: Drill-through, Dynamic Filters, Slicers by Region/Product/Month
