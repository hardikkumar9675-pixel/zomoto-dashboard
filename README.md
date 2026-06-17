# zomoto-dashboard
# Zomato Data Analysis Dashboard (Power BI)

A comprehensive, multi-page Power BI dashboard designed to analyze and visualize Zomato's operational performance across multiple cities. This project delivers actionable insights into sales trends, user engagement, and regional market penetration.

---

## 📊 Project Overview

This dashboard analyzes Zomato's ecosystem across **822 cities**, tracking over **77,900+ users** and **150,000+ orders**. It provides a granular look at revenue metrics, ordering patterns, demographic behaviors, and city-wise performance to aid data-driven decision-making.

### Key Metrics Tracked:
* **Total Revenue/Amount:** 987M
* **Total Sales Value:** 2M
* **Total Orders:** 150K
* **Total Ratings Received:** 148K

---

## 🗂️ Dashboard Structure & Screenshots

The Power BI report is divided into 4 main views for seamless navigation and targeted analysis:

### 1. Index Page (Landing View)
* A visually striking, branded splash screen that introduces the project and serves as the main navigation portal.

![Index Page](c81597f0-ef0f-4fe6-afb3-b8abebd1ddc1)

---

### 2. Overview Dashboard
* **High-Level KPIs:** Displays Total Amount, Sales Value, Rating Count, and Order Count.
* **Category Breakdown:** Compares **Veg (122M)** vs. **Non-Veg (106M)** vs. **Other (24M)** food preferences along with their respective rating counts.
* **Dynamic Filters:** Built-in toggles to view data by *Amount* or *Quantity*, and N-tier filters (Top 5, Top 10, Top 20, etc.).
* **Sales Trend:** A line chart showcasing the revenue trajectory over the years (2017–2020), highlighting a peak in 2018 at 0.41Bn.

![Overview Dashboard](fab9a0ce-7fb3-45d4-aee7-a5314efb6f5e)

---

### 3. User Performance
* **User Growth:** Tracks user acquisition with clear indicators for **Gain Users (60K)** and **Lost Users (81K)**.
* **Demographic Analysis:** An age-distribution bar chart displaying which age groups are driving the maximum order volume.
* **Engagement KPIs:** Highlights active users vs. total user base.

![User Performance](f1e93646-a725-4fe2-ad3a-877dcd212669)

---

### 4. City Performance
* **Geographical Mapping:** A global/regional map visualization plotting operational distribution.
* **Top Performing Cities:** Bar charts ranking cities based on *Sales*, *Ratings*, and *Total Users*.
* **Granular Data Table:** A breakdown matrix displaying explicit *Order Count* and *Sales Value* for specific localities (e.g., Abids & Koti Hyderabad, Adajan Surat, etc.).

![City Performance](a8a45562-5c20-4573-bf79-c0b0a3f4a141)

---

## 🛠️ Tech Stack & Tools Used

* **Data Visualization:** Power BI Desktop
* **Data Transformation:** Power Query (ETL process)
* **Modeling Language:** DAX (Data Analysis Expressions) for dynamic calculations and time-intelligence metrics.
* **Design & Theme:** Customized UI with integrated side-navigation panel for a clean, web-app feel.

---

## 💡 Key Insights Derived

1.  **Food Preference:** Vegetarian items yield higher revenue (122M) compared to Non-Vegetarian items (106M) within the analyzed dataset.
2.  **Peak Performance:** The year 2018 marked the highest sales performance (~0.41Bn) before witnessing a gradual decline in subsequent years.
3.  **User Retention Challenge:** The dashboard reveals a critical insight—lost users (81K) outpaced gained users (60K), signaling a need for enhanced customer retention strategies.

---

## 🚀 How to View the Project

1. Clone this repository:
```bash
   git clone [https://github.com/your-username/zomato-powerbi-dashboard.git](https://github.com/your-username/zomato-powerbi-dashboard.git)
