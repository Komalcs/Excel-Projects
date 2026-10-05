# 📊 Swiggy Sales Analytics Dashboard

## 📌 Overview

The **Swiggy Sales Analytics Dashboard** provides a comprehensive view of sales performance, customer ratings, order trends, food-type preferences, and geographical sales distribution across India.

The dashboard is designed to transform raw sales data into meaningful visual insights that can help understand business performance and identify important sales trends.

---

## 🎯 Objectives

- Analyze overall Swiggy sales performance.
- Track total sales and total orders.
- Monitor average customer ratings.
- Analyze average order value.
- Compare sales between Veg and Non-Veg food types.
- Identify top-performing states and cities.
- Analyze monthly, daily, and weekly sales trends.
- Compare sales, ratings, and orders across quarters.
- Provide an interactive and easy-to-understand business dashboard.

---

## 📊 Key Performance Indicators (KPIs)

| KPI | Value |
|---|---:|
| 💰 Total Sales | ₹53.01M |
| ⭐ Average Rating | 4.34 |
| 🛒 Average Order Value | ₹268.51 |
| ⭐ Rating Count | 5.59M |
| 📦 Total Orders | 1971.43K |

---

## 📈 Dashboard Visualizations

### 1. Monthly Sales Trend

A line chart represents the monthly sales performance from **January to August**.

**Key Insight:**
- Sales fluctuate throughout the months.
- Sales show a decline around February.
- Sales recover during March and April.
- May records a relatively strong performance.
- Sales fluctuate again during June and July before increasing in August.

---

### 2. Sales by Food Type

A doughnut chart compares sales between:

- 🥗 Veg
- 🍗 Non-Veg

**Key Insight:**
- Veg food contributes approximately **66%** of total sales.
- Non-Veg food contributes approximately **34%** of total sales.
- This indicates a significantly higher sales contribution from Veg food orders.

---

### 3. Sales by States

The geographical map displays sales distribution across different states of India.

**Key Insight:**
- The map helps identify high- and low-performing regions.
- States are represented using different shades according to their sales contribution.
- This visualization can help businesses identify regions with stronger demand and opportunities for expansion.

---

### 4. Daily Sales Trend

The column chart compares sales across different days of the week.

| Day | Sales |
|---|---:|
| Sunday | ₹7.6M |
| Monday | ₹7.4M |
| Tuesday | ₹7.4M |
| Wednesday | ₹7.5M |
| Thursday | ₹7.7M |
| Friday | ₹7.6M |
| Saturday | ₹7.8M |

**Key Insight:**
- **Saturday** has the highest sales at approximately ₹7.8M.
- **Thursday** also performs strongly.
- Monday and Tuesday record comparatively lower sales.

---

### 5. Quarterly Sales, Rating & Orders

The dashboard compares sales, average rating, and total orders by quarter.

| Quarter | Sales | Rating | Orders |
|---|---:|---:|---:|
| Q1 | ₹19.7M | 4.3 | 73.1K |
| Q2 | ₹19.9M | 4.3 | 74.2K |
| Q3 | ₹13.4M | 4.3 | 50.2K |

**Key Insight:**
- **Q2** records the highest sales and number of orders among the displayed quarters.
- Customer ratings remain consistently around **4.3**.
- Q3 shows a noticeable decline in both sales and orders.

---

### 6. Top 5 Cities by Sales

The horizontal bar chart displays the five highest-performing cities.

| Rank | City | Sales |
|---:|---|---:|
| 1 | Bengaluru | Highest |
| 2 | Lucknow | ₹3.12M |
| 3 | Hyderabad | ₹3.02M |
| 4 | Mumbai | ₹3.02M |
| 5 | New Delhi | ₹2.83M |

**Key Insight:**
- **Bengaluru** is the top-performing city in the displayed analysis.
- Lucknow, Hyderabad, Mumbai, and New Delhi are also major contributors to sales.

---

### 7. Weekly Sales Trend

The weekly sales chart tracks sales performance across multiple weeks.

**Key Insight:**
- Weekly sales remain relatively stable for most of the displayed period.
- A few weeks show noticeable increases.
- The final displayed period shows a significant drop compared with the preceding weeks.

---

## 🔍 Important Business Insights

- Total sales generated are approximately **₹53.01M**.
- The average customer rating of **4.34** indicates strong customer satisfaction.
- Veg food accounts for approximately **66% of sales**, making it the dominant food category.
- Saturday records the highest daily sales.
- Q2 performs strongly in terms of both sales and orders.
- Bengaluru is the leading city among the displayed top five cities.
- Sales performance varies considerably across Indian states.
- Weekly sales remain relatively consistent for most of the period.

---

## 🛠️ Dashboard Features

- 📌 KPI Cards
- 📈 Monthly Sales Trend
- 📊 Daily Sales Analysis
- 📅 Weekly Sales Trend
- 🍴 Food Type Analysis
- 🗺️ State-wise Sales Map
- 🏙️ Top 5 Cities by Sales
- 📊 Quarterly Sales, Ratings & Orders
- 🎛️ Month Filter/Slicer
- 📱 Interactive Dashboard Layout

---

## 🎨 Dashboard Design

The dashboard uses a **Swiggy-inspired orange and white theme** with:

- Clean KPI cards
- Rounded visual containers
- Interactive filtering
- Geographic visualization
- Multiple sales trend charts
- Consistent typography and layout
- Business-focused visual presentation

---

## 📂 Dashboard Structure

```text
Swiggy Sales Analytics Dashboard
│
├── KPI Cards
│   ├── Total Sales
│   ├── Average Rating
│   ├── Average Order Value
│   ├── Rating Count
│   └── Total Orders
│
├── Sales Analysis
│   ├── Monthly Sales Trend
│   ├── Daily Sales Trend
│   └── Weekly Sales Trend
│
├── Category Analysis
│   └── Sales by Food Type
│
├── Geographic Analysis
│   ├── Sales by States
│   └── Top 5 Cities by Sales
│
└── Performance Analysis
    └── Quarterly Sales, Rating & Orders
