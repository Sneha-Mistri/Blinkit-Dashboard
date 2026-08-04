# ⚡ Blinkit Analysis

The Blinkit Analysis dashboard provides a comprehensive evaluation of Blinkit's sales performance, customer satisfaction, and inventory distribution to identify key insights and opportunities for optimization using various KPIs and visualizations in Power BI.

---

## 📌 Short Description / Purpose

The **Blinkit Analytics Dashboard** provides an end-to-end visual analysis of **$1.20M in total sales** across **8,523 items**. Designed for operations managers, category heads, and retail strategists, this dashboard uncovers revenue drivers, customer preferences (such as Fat Content segmentation), outlet establishment trends, and geographical performance across Tier 1, Tier 2, and Tier 3 cities.

---

## 📂 Tech Stack

* **Power BI Desktop** – Used for dashboard layout, custom color palettes, and data visualization.
* **Power Query** – Executed data transformation, numeric formatting, handling missing values, and column structuring.
* **DAX (Data Analysis Expressions)** – Applied for dynamic metrics including $1.20M Total Sales, $141 Avg Sales, item counts, and average customer rating metrics.
* **Data Modeling** – Built a clean data model linking item inventory, outlet metadata, location tiers, and transaction metrics.
* **File Format** – `.pbix` (Power BI Report File) & High-Resolution Preview Images.

---

## 📊 Data Source

* **Dataset:** Blinkit Retail & Sales Operations Dataset.
* **Granularity:** Includes granular records for 8,500+ items spanning 16 product categories, outlet size tiers (Small, Medium, High), outlet types (Supermarket Types 1–3, Grocery Store), establishment years (2011–2022), and location tiers.

---

## 🎯 Features / Highlights

### • Business Problem
Quick-commerce and grocery platforms need to optimize inventory across different outlet sizes and regional tiers. Without a structured visual reporting system, identifying which product categories drive the most revenue, how outlet size impacts overall sales, and whether customer satisfaction remains high across different fulfillment types is difficult.

### • Goal of the Dashboard
* Monitor primary revenue KPIs (Total Revenue, Avg Ticket Size, Items Sold, Ratings).
* Compare category-level sales (e.g., *Fruits and Vegetables* vs. *Seafood*).
* Analyze consumer preference based on Fat Content (*Low Fat* vs. *Regular*).
* Evaluate revenue across Outlet Size, Location Tiers (Tier 1, 2, 3), and Outlet Types.

---

### • Walkthrough of Key Visuals

#### **Executive KPIs**
* **Total Sales:** The overall revenue generated from all items sold ($1.20M).
* **Average Sales:** The average revenue per sale ($141).
* **Number of Items:** The total count of different items sold (8,523).
* **Average Rating:** The average customer rating for items sold (3.9 / 5.0).

#### **Granular Requirements**
* **Total Sales by Fat Content:** Analyzes the impact of fat content on total sales and evaluates variations across secondary KPIs (*Average Sales, Item Count, Rating*).
* **Total Sales by Item Type:** Identifies top and bottom performing product categories in terms of total revenue generation.
* **Fat Content by Outlet for Total Sales:** Compares total sales across different outlet tiers segmented by Low Fat vs. Regular items.
* **Total Sales by Outlet Establishment:** Evaluates how the age or establishment year of an outlet influences total sales performance over time.

#### **Chart Requirements**
* **Percentage of Sales by Outlet Size:** Analyzes the correlation between store size (*Medium, Small, High*) and overall revenue contribution.
* **Sales by Outlet Location:** Assesses the geographic distribution of sales across Tier 1, Tier 2, and Tier 3 cities.
* **All Metrics by Outlet Type:** Provides a comprehensive matrix view of all key metrics (*Total Sales, Average Sales, Number of Items, Average Rating, Item Visibility*) broken down by outlet type (*Supermarkets vs. Grocery Stores*).

---

## 📈 Business Impact & Insights Summary

By analyzing peak sales drivers, category heads can optimize inventory to ensure top-revenue categories like *Fruits & Vegetables* and *Snack Foods* ($0.18M each) remain continuously stocked during high-demand hours. Operations teams can use store-size performance data to guide regional expansions, prioritizing **Medium-sized dark stores** which delivered the highest total revenue ($507.9K). Marketing teams can capitalize on strong quick-commerce adoption in **Tier 3 cities**—the top-performing geographical segment at $472.13K in sales—by scaling localized campaigns. Finally, merchandisers can shift product strategy to dedicate nearly two-thirds of shelf space to **Low Fat items**, catering directly to the strong consumer preference that generated $776.32K in total revenue.

---

## 🖼️ Dashboard Preview

![Dashboard Preview](https://github.com/Sneha-Mistri/Blinkit-Dashboard/blob/main/Blinkit_Dashboard_Screenshot.png)
