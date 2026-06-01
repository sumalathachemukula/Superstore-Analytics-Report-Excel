# Superstore Analytics Dashboard

An interactive Excel analytics dashboard designed to track, visualize, and analyze retail performance data. This project transforms raw transactional data into actionable business insights regarding sales trends, profitability, geographical distribution, and shipping logistics.

---

## 📊 Dashboard Preview

Below is a preview of the main reporting interface, which can be found in the repository as `Screenshot 2026-06-01 084447.png`:

![Dashboard Preview](Screenshot%202026-06-01%20084447.png)

---

## 📈 Key Metrics & Performance Insights

The dashboard monitors several high-level KPIs and business segments based on the current dataset:

*   **Total Sales:** ₹ 1,924.34K
*   **Total Orders:** 1,952
*   **Total Profit:** ₹ 224.08K
*   **Average Profit:** 114.8

### Operational Breakdown
*   **Top State by Sales:** California (> ₹ 250k) followed by New York.
*   **Top Cities:** Los Angeles and New York City dominate total sales revenue.
*   **Logistics Preference:** "Regular Air" and "Delivery Truck" handle the bulk of shipment distributions.
*   **Underperforming Areas:** Identifies the 5 lowest-performing subcategories (including Rubber Bands and Labels) to isolate operational inefficiencies.

---

## 🎛️ Interactive Filters

The dashboard is built with dynamic slicers to allow users to drill down into specific data layers seamlessly:
*   **Ship Mode:** Delivery Truck, Express Air, Regular Air
*   **Product Container:** Filter from Jumbo Boxes down to Small Packs and Wrap Bags
*   **Product Category:** Furniture, Office Supplies, Technology
*   **Region:** Central, East, South, West
*   **Order Priority:** Critical, High, Medium, Low, Not Specified

---

## 📁 Repository Structure

The files included in this repository are mapped as seen in `Screenshot 2026-06-01 101924.png`:

*   `Superstote Analytics Dashboard.xlsx` - The core interactive Excel workbook containing the dashboard interface, pivot tables, and data visualizations.
*   `Sales Data Set for Dashboard.xlsx` - The underlying raw retail dataset used to populate the analytics report.
*   `Screenshot 2026-06-01 084447.png` - A high-resolution image preview of the completed dashboard.

---

## 🚀 How to Use

1. **Clone the repository** or download the `.xlsx` files directly.
2. Open `Superstote Analytics Dashboard.xlsx` using Microsoft Excel (2016 or newer recommended for optimal slicer compatibility).
3. Use the **Orange Slicer Panels** on the right side of the sheet to interactively filter the entire dataset by region, priority, or category.
