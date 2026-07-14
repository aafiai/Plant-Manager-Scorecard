# Plant Manager Performance Scorecard

An interactive Power BI report ranking plant manager performance across MENA operations — tracking on-time delivery rate, delay frequency, and average delay days — to support performance benchmarking and identify best practices across regions.

<img width="2110" height="1218" alt="Scorecard" src="https://github.com/user-attachments/assets/9d56dc2f-f99e-4ed7-933d-f4600e9aa984" />
<img width="2200" height="1214" alt="Manager Details" src="https://github.com/user-attachments/assets/20240b5c-a212-4c21-b88a-9ba5b4a8ede2" />

## 📋 Overview
This report ranks every plant manager against three outcomes for their completed outages: **% On Time**, **% Early**, and **% Delayed**, alongside their **average delay days**. A matrix visual with conditional formatting (color-coded data bars) surfaces top and bottom performers within each region at a glance, rolling up from individual managers to regional and overall totals.

A drillthrough page lets you click into any manager to see their complete, filtered event history — every plant, equipment, planned vs. actual dates, and delivery outcome for that person specifically.


## 📊 Data
This project uses a **fully synthetic dataset** modeling the structure and statistical patterns of a real fleet outage scheduling system. No proprietary or confidential company data is used — it was recreated from scratch specifically for this portfolio.

## ✨ Key Features
- Region → Plant Manager matrix scorecard with conditional formatting (data bars)
- KPI summary cards: Total Completed Events, % On Time, % Early, % Delayed
- Drillthrough page: click any manager for their full event-level history
- DAX measures for delivery classification and performance metrics
