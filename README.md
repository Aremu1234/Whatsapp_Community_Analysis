# 📱 YDP WhatsApp Community Analysis

![Project Status](https://img.shields.io/badge/Status-Completed-success)
![Domain](https://img.shields.io/badge/Domain-Social%20Analytics-orange)
![Tool](https://img.shields.io/badge/Tool-PowerBI%20%2F%20PowerQuery-blue)

## 📖 Project Overview

The **YDP (Young Data Professionals) Communication Analysis** is a behavioral study of a specialized WhatsApp community over a 10-month period (Feb 2025 - Dec 2025). 

The purpose of this project was to understand engagement patterns, identify key influencers, and determine the "pulse" of the community. By parsing unstructured chat logs, this dashboard visualizes how professional discussions evolve over time, highlighting peak activity hours and content preferences.

---

## 📸 Dashboard Preview

You can explore the interactive Power BI dashboard using the link below.  
Click the `View Power BI Report` to open the live report:
[View Power BI Report](https://app.powerbi.com/view?r=eyJrIjoiZTNmOGJlZDctZmVjMS00ZDdlLThmMzgtMmYwMDI5MWVmMWM4IiwidCI6IjJiNjYwYWRiLTllNTEtNDRmMi1iOTJmLThkY2YxMWRmYWQxZiJ9)

---

## 🔑 Key Features

### 1. Community Health Metrics
* **Volume Tracking:** Analyzed **21,921 activities** across **596 active members**.
* **Retention Analysis:** Tracks member churn events, visualizing specific metrics for "Joined" (113), "Removed" (103), and "Left" (4)[cite: 2].
* **Activity Volume:** A KPI card highlighting an average of **75 messages per day**.

### 2. Temporal Behavior Analysis
* **Heatmaps:** A "Days vs. Hours" matrix identifying the exact intersections of high activity (e.g., Tuesday mornings).
* **Peak Hour Identification:** Pinpoints **10:00 AM** as the community's most active time.
* **Work-Week Trends:** A breakdown showing the split between Weekday (79.83%) and Weekend (20.17%) activity, confirming the professional nature of the group.

### 3. Contributor Leaderboards
* **Top Sender ranking:** Ranks the top 10 contributors based on activity volume.
* **Content Segmentation:** Breaks down user activity by type (Text, Link, Media). [cite_start]For example, the top contributor (`...5953`) is primarily a resource sharer, sending **657 links** compared to 399 texts.

---

## 🧠 Insights & Findings

1.  **Professional Focus:** The activity significantly drops on weekends (approx. 4K events) compared to weekdays (approx. 18K events), suggesting the group is treated as a formal workspace extension.
2.  **The "Resource Sharer" vs. "The Talker":**
    * The #1 ranked user (`...5953`) drives engagement through resource sharing (60%+ of their activity is Links).
    * The #3 ranked user (`...2573`) drives conversation, having the highest **Word Count (9,501)** despite having fewer total activities than the top user.
3.  **Active Moderation:** The proximity of "Joined" events (113) to "Removed" events (103) suggests strict community management or high turnover filtering[cite: 2].
4.  **Mid-Week Peak:** Tuesdays and Wednesdays appear to be the days with the highest sustained engagement.

---

## 🛠️ Data Pipeline & Tech Stack


1.  **Data Extraction:** Exported `_chat.txt` logs from WhatsApp.
2.  **Data Cleaning (Power Query):**
    * Cleansed and converted timestamps into date formats using Power Query M transformations.
    * Anonymized phone numbers (masked as `+234 ***`).
    * Categorized messages into `Media`, `Link`, and `Text`.
3.  **Visualization:** Built with `Power BI`.
4.  **Design Tool:** PowerPoint used for background layout.
---

## 👤 Author

**Aremu Ibrahim**
* [LinkedIn Profile](https://www.linkedin.com/in/aremu-theanalyst/)
* [Portfolio Link](https://aremuibrahim.carrd.co/)
