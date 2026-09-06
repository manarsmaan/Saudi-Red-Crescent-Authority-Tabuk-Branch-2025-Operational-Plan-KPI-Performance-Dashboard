# 🚑 Saudi Red Crescent Authority (Tabuk Branch) - 2025 Operational Plan Dashboard

Interactive **Power BI** dashboard tracking and analyzing the **2025 Operational Plan & KPIs** for the Saudi Red Crescent Authority (Tabuk Branch - Deputy Sector), using **2024 performance metrics as a baseline comparison**.

---

## 📌 Project Overview
This project converts static Excel operational sheets into dynamic data-driven dashboards. It monitors **13 Key Performance Indicators (KPIs)** across **4 Strategic Objectives**, enabling leadership to evaluate progress, track monthly/quarterly targets, and analyze workload distribution among goal owners.

---

## 🏗️ Data Model & Structure
The data architecture consists of **3 main tables** structured in a Star Schema:
* **`Bridge` (Dimension Table):** Connects KPI IDs with Strategic Objectives, Sub-goals, and Goal Owners.
* **`المؤشرات` (Quarterly Fact Table):** Contains Q1–Q4 target distributions and KPI weightings.
* **`المخطط والفعلي` (Monthly Fact Table):** Tracks monthly Planned vs. Actual progress across all 12 months.

---

## 🎯 Strategic Objectives & KPIs (13 KPIs Total)

* **Patient Journey Optimization (تحقيق رحلة مريض نموذجية):** 7 KPIs (Response times, 8-min emergency calls, CPR success rate, dispatch compliance, and unit downtime).
* **Robust Organizational Structure (تطوير بنية تنظيمية راسخة):** 1 KPI (National ambulance service standards compliance).
* **Fostering a Motivating Culture (خلق ثقافة محفزة):** 3 KPIs (Participatory management, employee dues clearance within 30 days, and employee engagement).
* **Branch General Administration (الإدارة العامة للفرع):** 2 KPIs (Non-SRCA emergency support operational hours and asset safety compliance).

---

## 👥 Goal Owners (توزيع المسؤوليّات)
* **Hussam Al-Saleh:** 6 KPIs (Operational, emergency, and dispatch workflows).
* **Majed Mohammed Al-Enazi:** 6 KPIs (Supply chain, fleet maintenance, organizational culture, and safety).
* **Abdulaziz Aqeeli:** 1 KPI (National quality & medical standards).

---

## 📸 Dashboard Preview

*(Replace these image paths with your actual screenshot file names)*

![Executive Overview](./screenshots/dashboard_overview.png)
*Figure 1: Executive Performance Overview*

![Planned vs Actual](./screenshots/planned_vs_actual.png)
*Figure 2: Monthly Planned vs. Actual KPI Progress*

---

## 🛠️ Tools & Technologies Used
* **Power BI Desktop:** Dashboard design, DAX measures, and visual modeling.
* **Power Query:** Data transformation, reshaping, and cleaning.
* **Microsoft Excel:** Source dataset structure.

---

## 💡 How to Add Media (Screenshots / GIF / Video)
1. **GIF:** Record a 10-second interactive preview using **ScreenToGif** and place it under `Project Overview`.
2. **Screenshots:** Take 2-3 clean screenshots, save them in a folder named `screenshots/`, and update the image paths above.
3. **Video:** Upload a short walk-through to YouTube/Loom and add the link at the end.
