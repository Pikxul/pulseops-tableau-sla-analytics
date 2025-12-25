PulseOps – Real-Time SLA Risk & Executive Operations Dashboard

PulseOps is a real-time operational intelligence solution built on Tableau Cloud that helps organizations monitor Service Level Agreement (SLA) performance and proactively identify operational risk. Instead of relying on static reports, PulseOps translates raw metrics into executive-ready risk signals that enable faster, data-driven decisions.

🚀 Overview

Operations teams often track order volumes and SLA performance through separate reports, making it difficult for leaders to quickly understand overall operational health. By the time issues are identified, SLA breaches may have already occurred.

PulseOps addresses this gap by providing a single Executive Pulse view that:

Visualizes key operational trends

Interprets SLA performance using business rules

Clearly signals whether operations are SAFE, AT RISK, or CRITICAL

This approach shifts analytics from passive reporting to actionable decision support.

🧩 What PulseOps Does

PulseOps provides:

Monitoring of Total Orders over time

Calculation of SLA % using On-Time Orders vs Total Orders

Automatic classification of SLA health into:

SAFE

AT RISK

CRITICAL

An Executive Pulse Dashboard that summarizes operational health at a glance

The solution helps stakeholders:

Detect SLA degradation early

Understand operational risk instantly

Take timely corrective actions

🏗️ System Architecture

PulseOps follows a simple and transparent architecture:

Data Source
Operational data is provided via a CSV file containing:

Order Date

Total Orders

On-Time Orders

Tableau Cloud
The dataset is ingested into Tableau Cloud, which serves as the analytics and visualization platform.

Calculated Fields
Business logic is implemented using Tableau calculated fields:

SLA % = On-Time Orders / Total Orders

SLA Status classification (SAFE / AT RISK / CRITICAL) based on defined thresholds

Dashboards
Multiple dashboards are created:

SLA % Trend

Total Orders Trend

Executive Pulse dashboard

Business Decisions
Dashboards enable:

SLA monitoring

Early risk detection

Faster executive decision-making

Architecture diagram:
See architecture/pulseops_architecture.png

🛠️ How It Was Built

PulseOps was built entirely on Tableau Cloud using the following steps:

Prepared a clean operational dataset in CSV format

Connected the dataset to Tableau Cloud

Created calculated fields for SLA % and SLA Status

Designed trend-based visualizations following Tableau best practices

Assembled an Executive Pulse dashboard focused on clarity and usability

Published and tested the solution to ensure consistent performance

The project prioritizes simplicity, interpretability, and real-world business value.

⚠️ Challenges Faced

Translating business SLA rules into correct Tableau calculations

Understanding Tableau’s aggregation behavior

Designing dashboards that are executive-friendly without oversimplifying data

Ensuring the solution tells a clear story rather than just showing charts

These challenges helped refine both the technical and design aspects of the solution.

🏆 Accomplishments

Built a fully functional Tableau Cloud solution

Implemented actionable SLA risk classification logic

Designed a clean, executive-ready dashboard

Delivered a real-world operational analytics use case

📚 What I Learned

Tableau calculated fields can effectively encode business logic

Strong analytics focus on decisions, not just visualizations

Executive dashboards must prioritize clarity and actionability

Storytelling and architecture are as important as charts

🔮 What’s Next for PulseOps

With more time, PulseOps could be extended with:

Automated data ingestion via APIs

Predictive SLA forecasting

Tableau Extensions for alerts and annotations

Deeper segmentation by region, team, or product

Integration with operational systems for proactive incident management

🧰 Built With

Tableau Cloud

Tableau Calculated Fields

Tableau Dashboards & Visual Analytics

CSV Data Source

▶️ Try It Out

Demo Video: https://youtu.be/Do_32JqaVlM

Live Tableau Dashboard:
https://prod-in-a.online.tableau.com/t/mrityunjoyop123-5792b0803b/views/PulseOps-SLAMetrics/SLATrend

Note: Due to Tableau Cloud trial restrictions, the dashboard may require authentication. Full functionality is demonstrated in the demo video, and access can be provided for judging if required.
