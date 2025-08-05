# Hotel Booking Demand Analysis

## 📌 Overview

This project dives deep into a real-world hotel booking dataset to uncover patterns, trends, and behaviors that directly impact the hospitality industry. Using Python and Power BI, I built a fully interactive business dashboard that helps stakeholders understand what drives cancellations, booking changes, guest types, and revenue differences between resort and city hotels.

The goal is to provide hotel managers and decision-makers with actionable insights that can help reduce cancellations, optimize pricing strategies, and improve customer satisfaction — all through data.

---

## 🧠 Objectives

- Explore and analyze a large hotel booking dataset
- Handle missing values and perform data cleaning using Python
- Create key performance indicators (KPIs) to measure business outcomes
- Build interactive dashboards in Power BI to visualize the insights
- Help businesses understand customer behavior and improve operational decisions

---

## 🛠️ Tools & Technologies Used

### 🔹 Python (Jupyter Notebook)
- **Pandas** – Data cleaning, transformation, and exploration  
- **NumPy** – Handling numerical operations  
- **Matplotlib & Seaborn** – Data visualization for initial exploration

### 🔹 Power BI
- **Cards, KPIs, Gauge Charts** – For highlighting key metrics  
- **Line and Column Charts** – To analyze trends and patterns over time  
- **Treemaps and Donut Charts** – For category-based breakdowns  
- **Map Visual** – To analyze global booking distribution  
- **Filters & Slicers** – For interactive analysis by hotel type, market segment, and customer type

---

## 🧹 Data Cleaning & Preparation

- Filled missing values in key columns such as `children`, `agent`, and `company`
- Converted month names to numbers using conditional logic in DAX
- Rounded float-type columns to integers for cleaner visuals
- Created new KPIs and calculated columns such as:
  - Repeated Guest %
  - Booking Changes
  - Total Special Requests
  - Daily Average Rate (ADR)

---

## 📊 Dashboards & Insights

### 1️⃣ **Hotel Booking Dashboard**

A complete view of booking performance metrics:

- **KPI Cards** show total bookings, average daily rate (ADR), cancellation rate, repeated guest %, and booking changes
- **Gauge Chart** shows ADR performance vs target
- **Donut Charts** compare resort vs city hotel bookings, and customer types
- **Line Chart** visualizes daily average booking volume, showing peaks around holidays and weekends

**Key Insight:**  
City hotels received more bookings overall, but resort hotels had longer stays and higher ADR. Most cancellations came from city hotels, suggesting possible overbooking or last-minute plan changes.

---

### 2️⃣ **Global Booking Insights**

An interactive map showing the global distribution of hotel bookings.

- Each country is color-coded by the number of bookings
- Tooltips show exact booking counts by country

**Key Insight:**  
Most bookings came from Portugal, the UK, and France, indicating strong European market concentration. Opportunities exist to expand into underrepresented regions.

---

### 3️⃣ **Total Distribution Channels**

A breakdown of how customers booked their stay:

- **Bar Charts** showing the most common booking agents and channels
- **Treemap** of agent-wise bookings
- **Filters** to explore changes over years and hotel types

**Key Insight:**  
Most bookings were made via offline travel agents, followed by direct bookings. Resort hotels had a higher percentage of bookings through third-party channels.

---

## 🔍 Key Business Findings

- **Cancellation Rate** is higher for city hotels and guests with longer lead times
- **Repeated Guests** are a small segment (under 5%) but they show lower cancellation behavior
- **Special Requests** and booking changes are more common in resort hotels
- **Customer Types**: Most bookings come from transient guests; very few are part of group bookings
- **Peak Booking Months**: July and August show clear spikes, aligning with travel seasons

