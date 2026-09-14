
# 📦 Inventory-And-Supply-Chain-Analysis

Data Analytics project showcasing Inventory and Supply Chain Analysis using Power BI

## 📌 Project Overview

**Inventory And Supply Chain Analysis** is an end-to-end **Power BI data analytics project** focused on analyzing inventory performance, warehouse utilization, transportation costs, sales trends, lead times, backorders, and regional inventory distribution.

The project transforms supply chain data into meaningful business insights through data preparation, KPI development, interactive visualizations, and dashboard-based analysis.

The main objective is to provide a centralized view of supply chain performance and help businesses make data-driven decisions related to inventory management, logistics, warehouse utilization, and order fulfillment.

## 🎯 Project Objectives

- Analyze overall inventory performance.
- Monitor warehouse utilization.
- Calculate and analyze Days Sales of Inventory.
- Evaluate inventory turnover ratio.
- Analyze transportation costs across regions and categories.
- Track yearly units sold and sales trends.
- Compare average lead time across product categories.
- Analyze backorders by order status.
- Evaluate inventory levels across regions and categories.
- Build an interactive Power BI dashboard.
- Generate actionable supply chain insights.

## 📂 Dataset

The project uses a **Supply Chain and Inventory dataset** containing information related to inventory, sales, transportation, warehouses, product categories, regions, lead times, and order status.

### Key Data Areas

- Product Categories
- Regions
- Inventory Levels
- Units Sold
- Transportation Cost
- Lead Time
- Warehouse Utilization
- Order Status
- Backorders
- Sales Information

## 🛠️ Tools & Technologies

| **Tool** | **Purpose** |
| -------- | ----------- |
| **Power BI** | Interactive dashboard and data visualization |
| **Power Query** | Data cleaning and transformation |
| **DAX** | KPI calculations and analytical measures |
| **Excel** | Data preparation and supporting analysis |
| **GitHub** | Project documentation and version control |

## 🔄 Project Workflow

Raw Dataset  
↓  
Data Loading  
↓  
Data Cleaning & Transformation  
↓  
Data Modeling  
↓  
DAX Measures & KPI Development  
↓  
Supply Chain Analysis  
↓  
Power BI Dashboard  
↓  
Business Insights  
↓  
Business Recommendations

## 🧹 1. Data Cleaning & Transformation

The dataset was prepared and transformed using **Power Query** before developing the final dashboard.

### Data Preparation Activities

- Reviewed dataset structure and fields.
- Checked data types.
- Identified and handled data quality issues.
- Standardized data fields.
- Prepared categorical and numerical columns.
- Validated inventory and sales-related data.
- Prepared the dataset for analytical modeling.

The transformed data was then used to create the Power BI data model and analytical measures.

## 📐 2. DAX & KPI Development

DAX was used to create important supply chain metrics and KPIs required for performance analysis.

### Key KPIs

| **KPI** | **Value** |
| ------- | --------- |
| **Warehouse Utilization** | 34.08 |
| **Days Sales of Inventory** | 15.56 |
| **Inventory Turnover Ratio** | 23.47 |

These KPIs provide a high-level view of inventory and warehouse performance.

## 📊 3. Power BI Dashboard

An interactive **Power BI dashboard** was developed to provide a comprehensive view of inventory and supply chain performance.

### Dashboard Includes

- Warehouse Utilization
- Days Sales of Inventory
- Inventory Turnover Ratio
- Transportation Cost by Region and Category
- Units Sold by Year
- Average Lead Time by Category
- Backorder by Order Status
- Inventory Level by Category and Region
- Region Filter
- Category Filter

The dashboard allows users to interact with the data and analyze supply chain performance across different regions and product categories.

## 🏭 4. Warehouse Utilization Analysis

The dashboard provides a dedicated view of warehouse utilization.

The current overall **Warehouse Utilization KPI is 34.08**, helping evaluate the utilization of available warehouse capacity.

This analysis can support warehouse planning and capacity management decisions.

## 🚚 5. Transportation Cost Analysis

Transportation costs are analyzed across different regions and product categories.

### Regions Analyzed

- North
- West
- East
- South

### Categories Analyzed

- Accessories
- Clothing
- Electronics
- Furniture

This analysis helps identify variations in transportation costs and potential areas for logistics optimization.

## 📈 6. Sales Trend Analysis

The dashboard analyzes **Units Sold by Year** to understand changes in sales volume over time.

The yearly trend provides visibility into demand patterns and helps evaluate overall sales performance.

## ⏱️ 7. Lead Time Analysis

Average lead time is analyzed across different product categories.

### Average Lead Time

| **Category** | **Average Lead Time** |
| ------------ | --------------------- |
| **Accessories** | 16.60 |
| **Electronics** | 15.68 |
| **Furniture** | 15.50 |
| **Clothing** | 15.29 |

Comparing lead times across categories helps identify potential supply chain delays and areas for operational improvement.

## 📦 8. Backorder Analysis

The dashboard analyzes backorders based on order status.

### Backorder Status

| **Order Status** | **Count** |
| ---------------- | --------: |
| **Fulfilled** | 838 |
| **Pending** | 248 |
| **Canceled** | 114 |

This analysis provides visibility into order fulfillment performance and helps identify pending and canceled orders.

## 🗺️ 9. Inventory Level Analysis

Inventory levels are analyzed by **product category and region**.

This helps businesses understand how inventory is distributed across different geographical regions and identify potential inventory imbalances.

The analysis can support better stock allocation and inventory planning decisions.

## 🎛️ Interactive Filters

The dashboard includes interactive slicers for:

- **Region**
- **Category**

These filters allow users to dynamically explore supply chain performance based on their selected region or product category.

## 📈 10. Key Insights

The analysis provides several useful supply chain insights:

- Warehouse utilization stands at **34.08**.
- Days Sales of Inventory is **15.56**.
- Inventory turnover ratio is **23.47**.
- Transportation costs vary across regions and product categories.
- Units sold show changes in sales performance across years.
- Average lead time differs across product categories.
- Fulfilled orders represent the largest share of analyzed backorder statuses.
- Pending and canceled orders highlight areas that may require further operational attention.
- Inventory levels vary across regions and categories.
- Regional and category-level analysis can support better inventory allocation decisions.

> Note: Detailed numerical findings and visual trends are available directly in the Power BI dashboard.

## 💡 11. Business Recommendations

Based on the analysis, businesses can:

- Optimize warehouse capacity utilization.
- Monitor inventory turnover regularly.
- Improve inventory replenishment planning.
- Identify categories with higher lead times.
- Evaluate transportation costs across regions.
- Optimize regional inventory allocation.
- Monitor pending and canceled orders.
- Improve order fulfillment processes.
- Use demand trends to support inventory planning.
- Develop region-specific supply chain strategies.

## 📁 Project Structure

```text
Inventory-And-Supply-Chain-Analysis/
│
├── Dataset/
│   └── Supply_Chain_Dataset.xlsx
│
├── PowerBI/
│   └── Inventory_And_Supply_Chain_Analysis.pbix
│
├── Screenshots/
│   └── dashboard-preview.png
│
└── README.md
````

## ▶️ How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/Inventory-And-Supply-Chain-Analysis.git
```

### Step 2: Open the Dataset

Open the dataset provided in the `Dataset` folder.

Review the available supply chain, inventory, sales, and operational data.

### Step 3: Open Power BI Dashboard

Open:

```text
PowerBI/Inventory_And_Supply_Chain_Analysis.pbix
```

### Step 4: Refresh the Dataset

If required, update the data source path and refresh the Power BI model.

### Step 5: Explore the Dashboard

Use the **Region** and **Category** slicers to interact with the dashboard and analyze supply chain performance from different perspectives.

## 📸 Dashboard Preview

![Inventory And Supply Chain Analysis Dashboard](Screenshots/dashboard-preview.png)

## 📄 Project Deliverables

This repository contains:

* ✅ Supply Chain Dataset
* ✅ Data Cleaning & Transformation
* ✅ Power BI Data Model
* ✅ DAX Measures & KPIs
* ✅ Interactive Power BI Dashboard
* ✅ Inventory Analysis
* ✅ Warehouse Analysis
* ✅ Transportation Cost Analysis
* ✅ Lead Time Analysis
* ✅ Backorder Analysis
* ✅ Regional Analysis
* ✅ Business Insights
* ✅ Business Recommendations
* ✅ Project Documentation

## 🚀 Skills Demonstrated

This project demonstrates practical skills in:

* Data Cleaning
* Data Transformation
* Data Modeling
* DAX
* Power BI
* KPI Development
* Inventory Analysis
* Supply Chain Analytics
* Operations Analytics
* Logistics Analysis
* Data Visualization
* Business Intelligence
* Dashboard Development
* Business Analysis
* Data Storytelling
* Analytical Thinking
* Problem Solving

## 💼 Business Value

This project demonstrates how supply chain and inventory data can be transformed into actionable business insights using **Power BI**.

The analysis can help businesses:

**Monitor Performance**
↓
**Identify Supply Chain Issues**
↓
**Optimize Inventory**
↓
**Improve Operational Efficiency**
↓
**Make Data-Driven Decisions**

## 👨‍💻 Author

**Kunal Rajput**

**Aspiring Data Analyst**

**Skills:** Power BI | SQL | Excel | Python | Data Analytics

---

## ⭐ If You Like This Project

If you find this project useful or interesting, please consider giving the repository a ⭐ on GitHub.

Thank you for visiting my project!

```

This version follows the **same professional README flow as your previous project**—Overview → Objectives → Dataset → Tools → Workflow → Analysis sections → Dashboard → Insights → Recommendations → Structure → Run → Deliverables → Skills → Business Value → Author. :contentReference[oaicite:0]{index=0}
```
