# 📊 Interactive Global Tech Layoffs Analysis Dashboard

## Project Overview

This project features an interactive Tableau dashboard analyzing **global technology layoffs** from 2020 to early 2023. The objective was to build a dynamic analytical tool that moves beyond basic reporting, utilizing **intermediate and advanced Tableau features** to visualize macro trends, geographical impact, and industry-specific metrics.

---

## ✨ Final Dashboard View

Below is a snapshot of the completed, interactive dashboard.



**[🔗 View the Live Interactive Dashboard on Tableau Public]**([https://public.tableau.com/app/profile/keerthan.th/viz/CleanedLayoffs/Dashboard1?publish=yes](https://public.tableau.com/app/profile/keerthan.th/viz/CleanedLayoffs/Dashboard1?publish=yes))

---

## 🚀 Key Features & Tableau Techniques Used

This project showcases mastery of several advanced Tableau concepts:

* **Dynamic Filtering (Parameters & Sets):** Implemented a **Parameter** and **Set** to allow users to dynamically control the number of industries displayed (e.g., Top 5, Top 10) in the Industry Analysis chart.
* **Time Series Modeling (Table Calculations):** Utilized a **3-Month Rolling Sum (`WINDOW_SUM`)** calculation to smooth volatile layoff data, providing a clear visualization of the underlying trend over time.
* **Reliable KPIs (LOD Expressions):** Established fixed, accurate Key Performance Indicators (KPIs) like **Total Global Layoffs** using **`FIXED` Level of Detail (LOD) Expressions**. This ensures the total figure remains accurate even when users filter the dashboard.
* **Multi-Layered Geographic Analysis:** Created a **Dual Axis Map** to overlay geographical context (Country Totals - Filled Map) with event-specific detail (Company Locations - Circles), sized by **Funds Raised**.
* **Dashboard Actions:** Engineered **Filter Actions** between all three main visuals (Map, Trend, Industry) to create a fully connected and guided analytical experience.

---

## 📂 Repository Contents

* `Dashboard of Tableau project 1.jpg`: High-resolution image of the final dashboard.
* `CleanedLayoffs.twbx`: The packaged Tableau workbook file.
* `Cleaned layoffs.csv`: The primary dataset used for this analysis.

---

## 🔍 Data Source

The dataset used is sourced from publicly available layoff tracking data, capturing announced workforce reductions across the technology and startup sectors.
