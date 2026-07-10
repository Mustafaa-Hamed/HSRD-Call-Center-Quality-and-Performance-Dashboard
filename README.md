# HSRD-Call-Center-Quality-and-Performance-Dashboard
End-to-End Business Intelligence Project

Overview
This project demonstrates the complete Business Intelligence lifecycle for a Call Center Quality Assurance environment, transforming raw operational data into executive dashboards that support strategic decision-making.



The dashboard provides management with a comprehensive view of:

Overall Quality Performance
Supervisory Performance
Critical Calls Monitoring
Escalation Analysis
Branch Performance
Regional Performance
Operational Efficiency
Customer Experience Indicators
Brand Identity & Design System

To maintain consistency throughout the project, a unified visual identity was applied across every report page.

Primary Color Palette
Color	Usage
Primary Blue      #0F4650
Primary Green     #31976C
Light Green       #95BD92
Accent Orange     #F0A92E
Soft Orange       #F9D2A1
Light Blue Gray   #BDCECF
Panel Gray        #EAEAE7
Background White  #FDFCFC

The visual language was intentionally designed to provide:

Professional corporate appearance
Easy KPI recognition
Clear comparison between metrics
Minimal cognitive load
Executive-friendly dashboards

Adobe tools were used to create all dashboard covers, icons, visual assets, and branding elements.

Data Disclaimer

Important Notice

The data presented throughout this project is NOT real organizational data.

All values, numbers, branch statistics, KPIs, call volumes, and performance scores were generated exclusively for demonstration purposes.

This approach was taken due to the confidentiality, sensitivity, and privacy requirements associated with Call Center Quality Assurance data.

The dashboards are intended to demonstrate the analytical methodology, data modeling techniques, KPI calculations, and visualization capabilities only.

Project Workflow

The project follows a complete Business Intelligence pipeline.

1. Data Collection

The data was gathered from multiple operational sources including:

CRM System
Quality Assurance Team
Supervisory Team
Internal Operational Reports
Additional extracted datasets generated from CRM activities

2. Data Cleaning & Preparation
Before analysis, all datasets were cleaned and standardized using:

Python
Power Query

The cleaning process included:
Removing duplicates
Handling missing values
Data type correction
Standardizing branch names
Standardizing regional names
Merging datasets
Creating calculated columns
Preparing fact and dimension tables

3. Data Modeling
The semantic model was developed in Power BI.
The data model combines concepts from both:
Star Schema (Galaxy Model)
Snowflake Schema

This hybrid approach was selected because several business processes share common dimensions while other dimensions require normalization.

The final model improves:
Query performance
Model scalability
Reusability
Relationship management
DAX calculation efficiency
4. Dashboard Development

Power BI was used for:
Data Modeling
DAX Calculations
KPI Development
Interactive Reports
Drill-down Analysis
Geographic Mapping
Executive Dashboards
KPI Calculation Methodology
Overall Quality Performance Index (QPI)


Page 1 — Executive Overview
<img width="1296" height="725" alt="1" src="https://github.com/user-attachments/assets/54fcdf20-5d09-4b16-9fc7-f4e8e47b4e0d" />
---
<img width="1297" height="730" alt="2" src="https://github.com/user-attachments/assets/6f31298f-4a69-46c4-804d-70b7d554a1af" />



This page serves as the executive landing page of the dashboard.

It provides senior management with a high-level overview of operational performance across all regions.

Main KPIs
Total System Calls
Quality Performance Index (QPI)
Supervision Score
Total Team Calls
Total Critical Calls
Escalated Calls
Quality & Supervision by Region

Compares:

Overall Quality Score
Overall Supervision KPI

Purpose:

Identify best-performing regions
Detect regions requiring management attention
Compare supervision effectiveness with service quality
Critical Calls vs Target

Compares:

Actual Critical Call Percentage
Target Percentage

Purpose:

Monitor operational risks
Detect branches exceeding acceptable thresholds
Branch Distribution Map

Shows the geographical distribution of branches.

Purpose:

Geographic monitoring
Regional performance overview
Coverage analysis
Team Calls Trend

Displays monitored team calls by region.

Managers can quickly identify:

Monitoring coverage
Team workload
Operational consistency

Page 2 — Quality & Supervision Analysis
<img width="1276" height="692" alt="3" src="https://github.com/user-attachments/assets/1d1d5309-8713-4071-b236-0c8cd0a61ddd" />

This page focuses on measuring service quality and supervisory performance.

Left Gauges
Quality Performance Index

Displays the overall quality percentage.

Supervision Score

Displays supervisory performance.

Detailed Quality KPIs

Three major indicators are presented.

Session Quality Score

Measures evaluation quality.

Quality Compliance

Measures compliance with quality standards.

Reduction of Low Quality Sessions

Measures quality improvement.

Detailed Supervision KPIs
Supervisory Monitoring Compliance

Supervisor commitment.

Supervisory Monitoring Quality

Review quality.

Post-Supervision Improvement Rate

Improvement after coaching.

Branch Map

Displays branch locations across Saudi Arabia.

Purpose:

Regional monitoring
Branch comparison
Geographic analysis
Branch Ranking

Compares every branch based on:

Overall Quality Score
Overall Supervision KPI

This visualization quickly highlights:

Top-performing branches
Underperforming branches
Performance gaps


Page 3 — Critical Calls Dashboard
<img width="1297" height="730" alt="2" src="https://github.com/user-attachments/assets/a59c725b-b1b8-4cb6-b7be-7942b0d948ea" />
<img width="1277" height="712" alt="4" src="https://github.com/user-attachments/assets/f14332fe-b2bf-4888-ab48-2c7fc797ed3f" />

This page focuses on operational risks.

It enables management to identify high-risk branches and monitor escalation activities.

Critical Calls Gauge

Displays:

Critical Calls %

KPI Cards
Sessions Requiring Escalation
Number of Critical Calls
Team Calls
Calls Comparison Chart

Compares:

Total Calls
Team Calls
Critical Calls
Overall Quality Score

Purpose:

Identify whether increases in call volume affect quality.

Average Call Duration

Shows average handling time by region.

Managers can identify:

Long handling times
Training opportunities
Process bottlenecks
Business Value

This dashboard enables decision-makers to:

Monitor quality performance in real time.
Evaluate supervisory effectiveness.
Identify operational risks early.
Compare regional and branch performance.
Detect branches requiring coaching.
Monitor critical call trends.
Improve customer experience.
Support data-driven management decisions.
Optimize operational efficiency.
Enhance continuous improvement initiatives.
Technology Stack
Category	Technology
Programming	Python
Data Cleaning	Python, Power Query
Data Modeling	Power BI
Data Model	Hybrid Galaxy + Snowflake Schema
BI Development	Power BI
DAX	KPI Calculations & Business Logic
Visualization	Power BI
Design	Adobe Creative Suite
Data Sources	CRM System, QA Team, Supervisory Team, Internal Operational Reports
Final Note

This project demonstrates a complete enterprise Business Intelligence solution, covering the full analytical lifecycle—from data collection and cleansing to semantic modeling, KPI engineering, and executive dashboard development. By integrating Python, Power Query, Power BI, DAX, and Adobe Creative Suite, the solution delivers a scalable and visually consistent reporting platform. Although the underlying data is entirely fictional to protect confidential business information, the architecture, methodology, and analytical approach reflect real-world Business Intelligence practices used in modern call center operations.
