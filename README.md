# Task-2-SofiaAhmed
Repository for Task 2 ( EDA Report )

# E-Commerce Exploratory Data Analysis (EDA) Project

## 📌 Project Overview

This repository contains the Exploratory Data Analysis (EDA) phase of the data analytics lifecycle for the cleaned E-Commerce dataset. Following the initial data preparation and cleaning stage, this project focuses on uncovering hidden patterns, identifying sales trends, analyzing customer behavior, and extracting actionable business insights using statistical summaries and data visualizations.

The objective of this analysis is to answer key business questions, detect anomalies, and provide data-driven recommendations to optimize marketing strategies, inventory management, and overall operational efficiency.

## 🛠️ Tools & Technologies

* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## 🔍 Core Analysis Areas

The exploratory analysis is structured into the following key dimensions:

1. **Descriptive Statistics:** Summary statistics (mean, median, standard deviation) to understand the distribution, central tendency, and spread of numerical features like `Quantity`, `UnitPrice`, and `TotalPrice`.
2. **Sales & Revenue Trends:** Time-series analysis of orders to identify peak sales hours, days of the week, and monthly growth trends.
3. **Product Performance Analysis:** Identification of top-performing products by total revenue and order volume, as well as underperforming items.
4. **Customer Behavior & Demographics:** Analysis of purchasing patterns based on `PaymentMethod`, `Referral Source`, and geographic distribution via `ShippingAddress`.
5. **Correlation & Relationship Testing:** Evaluating relationships between variables (e.g., how `Quantity` or `ItemsInCart` correlates with overall discounts/coupons and revenue).

## 📊 Key Insights & Findings

* **Peak Performance:** Sales revenue peaks during `[e.g., Weekends / Q4 / Evening hours]`, indicating a prime window for targeted marketing campaigns.
* **Top Revenue Drivers:** `[Product Category/Name]` emerged as the highest revenue-generating category, accounting for `[X]%` of total sales.
* **Acquisition Channels:** The most effective customer acquisition channel was `[e.g., Social Media / Direct Traffic]`, yielding the highest conversion and average order value (AOV).
* **Payment Preferences:** `[e.g., Credit Card / Digital Wallet]` is the most preferred payment method among users, representing `[X]%` of all processed transactions.


## 📈 Visualizations Included

The Jupyter Notebook features several industry-standard visualizations built using Seaborn and Matplotlib:

* **Histograms & KDE Plots:** To assess the distribution and skewness of order values and pricing.
* **Box Plots:** Implemented for robust outlier detection across financial metrics, helping to visually isolate extreme values and understand data variance.
* **Pie Charts:** Used to represent the proportional market share and distribution of categorical variables, such as payment methods and referral traffic sources.
* **Bar Charts:** To compare categorical data such as top products and referral traffic performance.
* **Line Charts:** To plot continuous time-series data for tracking revenue trends over the batch period.
* **Heatmaps:** A correlation matrix displaying the strength of relationships between numerical features.

## 🚀 Strategic Recommendations

1. **Inventory Optimization:** Increase stock levels for top-tier products ahead of identified peak sales periods to avoid stockouts.
2. **Targeted Marketing:** Reallocate ad spend toward the highest-performing `Referral Source` to maximize return on investment (ROI).
3. **Checkout Streamlining:** Optimize the checkout experience for the most popular `PaymentMethod` to reduce cart abandonment rates.
