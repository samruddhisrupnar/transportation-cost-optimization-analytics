# Project Documentation & Business Analysis Artifacts

This folder contains the analytical frameworks and business analysis methodologies used to drive cost optimization for Sairaja Roadways.

## 1. Business Requirements Document (BRD) - Summary
* **Objective:** Reduce operational overhead across the logistics network by identifying and mitigating leakage in fuel, toll, and maintenance workflows.
* **Core Problem:** Lack of centralized operational visibility leading to undetected variance in vehicle maintenance cycles and fuel consumption.
* **Scope:** Analysis of fleet data spanning fuel receipts, toll logs, and ServiceNow maintenance ticket lifecycles.

## 2. KPI Framework & Performance Measures
To evaluate operational performance, the following metrics were tracked and built into ServiceNow reports:
* **Fuel Efficiency Variance:** Actual vs. expected fuel consumption per route.
* **Maintenance Turnaround Time (TAT):** Time taken from a breakdown incident ticket creation in ServiceNow to asset deployment.
* **Toll Cost Variance:** Discrepancy between optimized GPS-mapped toll routes and actual driver expenditures.
* **Delivery On-Time SLA:** Percentage of successful deliveries completed within the committed operational window.

## 3. ServiceNow Configuration Notes
* **Data Sources:** Combined native ServiceNow incident/asset tables with external vehicle logistics data via Excel.
* **Report Types Created:** Trend charts for monthly maintenance logs, bar graphs mapping cost drivers, and single-score widgets tracking current active SLAs.
