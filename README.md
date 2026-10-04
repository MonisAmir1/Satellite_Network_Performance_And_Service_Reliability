# Satellite Network Performance & Service Reliability
> Analysed satellite network outages and service performance to identify reliability risks, customer impact, and opportunities to reduce service disruptions.

## **View the Full Project →**

## About the Project

ABC Communications is a fictional Luxembourg-based satellite communications operator providing broadband, mobility, and secure connectivity services across Europe, the Middle East, Africa, and selected global markets.

This project investigates **network performance and service reliability** across a multi-satellite fleet and ground station network, using 24 months of outage and service performance data from **January 2024 to December 2025**.

The analysis focuses on where outages occur, how long they last, which customers and services are most affected, and which factors drive SLA breaches, with the goal of supporting targeted reliability improvements.

## Objective

The objective was to understand:

- Where service outages are concentrated across regions, ground stations, and satellites.
- Which customers and customer segments are most affected by disruptions.
- Which service types are missing reliability / SLA targets.
- What the main causes of outages are.
- How these findings can inform prioritised actions to improve network reliability and reduce customer impact.

## Project Approach

The investigation followed a structured operational analytics approach:

**Business Question → Data Modelling → Overall Reliability Baseline → Geographic & Station Analysis → Customer & Service Impact → Root Cause Focus → Strategic Recommendations**

This allowed the analysis to move from high-level reliability metrics to specific locations, customers, services, and causes that the business can act on.

## Technical Stack

**Data Modelling & Preparation**
- Microsoft SQL Server (T-SQL)
- Dimensional data modelling
- Synthetic operational data generation
- Fact and dimension table design

**Analysis**
- T-SQL exploratory analysis
- Outage frequency, duration, and SLA breach analysis
- Regional, station, customer, and service-level performance analysis

**Business Intelligence**
- Power BI Desktop
- Star-schema style data model
- DAX measures for reliability KPIs
- Interactive 3-page dashboard (Executive Overview, Network & Location Performance, Customer & Service Impact)

## Key Result

The analysis found that **ABC Communications recorded 5,840 outages** over the 24-month period, with an average duration of **57 minutes**. Critically, **27.7% of outages resulted in an SLA breach**.

Key findings included:
- Outages were heavily concentrated in **Western and Central Europe**, particularly at ground stations in Germany and Luxembourg.
- High-value **Enterprise and Government customers** were among the most frequently affected.
- Several **critical high-SLA services** (including secure government and infrastructure services) showed elevated breach rates.
- **Equipment Failure** was by far the dominant cause of outages.

These findings were translated into three strategic priorities: prioritising high-outage ground stations, strengthening reliability on critical services, and addressing Equipment Failure as the primary root cause.

## Data

This project uses a **real-world style synthetic dataset** created specifically for portfolio purposes. It does not contain real company, customer, or confidential commercial data.

## Full Project

The complete case study contains the detailed business context, analytical approach, key insights, strategic recommendations, expected business impact, technical implementation, dashboard, and lessons learned.

## **View the Full Project →**
