# SAP Analytics Cloud | Supply Chain Inventory & Replenishment Control Tower

<p align="center">
  <img src="https://img.shields.io/badge/SAP%20Analytics%20Cloud-Hands--on-blue" alt="SAP Analytics Cloud">
  <img src="https://img.shields.io/badge/Supply%20Chain-Analytics-success" alt="Supply Chain Analytics">
  <img src="https://img.shields.io/badge/Business%20Intelligence-Dashboard-informational" alt="Business Intelligence">
  <img src="https://img.shields.io/badge/Project-Self--Directed-orange" alt="Self Directed Project">
</p>

<p align="center">
  <b>My First Hands-on SAP Analytics Cloud Project</b><br>
  From a raw supply-chain dataset to an executive-style analytical dashboard
</p>

---

## 📊 Dashboard Preview

<p align="center">
  <a href="assets/screenshots/09-final-dashboard.png">
    <img src="assets/screenshots/09-final-dashboard.png"
         alt="SAP Analytics Cloud Supply Chain Inventory and Replenishment Control Tower Dashboard"
         width="100%">
  </a>
</p>

<p align="center">
  <b>Supply Chain Inventory & Replenishment Control Tower</b><br>
  Inventory Health • Replenishment Risk • Supplier Performance • Demand Visibility
</p>

---

## 📌 Project Overview

This is my **first self-directed hands-on project using SAP Analytics Cloud (SAC)**.

I wanted to build something practical rather than simply follow a tutorial. I started with a raw supply-chain CSV dataset and worked through the SAC workflow step by step — from understanding the platform and creating a dataset to validating the data, configuring measures and calculations, building a story, and designing an executive-style dashboard.

The final solution is a **Supply Chain Inventory & Replenishment Control Tower** designed to bring important operational indicators into a single analytical view.

The dashboard focuses on:

- Inventory health
- Units sold
- Demand forecast
- Reorder points
- Order quantities
- Supplier lead times
- Inventory trends
- Replenishment visibility

This project demonstrates my ability to learn and apply SAP Analytics Cloud to a practical business scenario.

---

# 🎯 Project Objective

The main objective was to understand how SAP Analytics Cloud can transform raw operational data into a business-oriented analytical story.

The dashboard was designed to help answer questions such as:

1. **How much inventory is currently held?**
2. **How many units are being sold?**
3. **What does the monthly demand forecast look like?**
4. **How does inventory compare with reorder points?**
5. **What are the typical order quantities?**
6. **How much supplier lead-time variation exists?**
7. **Can multiple supply-chain indicators be brought together into one management view?**

---

# 🏭 Business Context

Supply-chain teams need visibility into inventory, demand and replenishment to make informed operational decisions.

A single inventory number does not provide enough context. Inventory levels can fluctuate over time, demand can change by month, suppliers can have different lead times, and reorder points and order quantities influence replenishment decisions.

For this project, I created a simplified analytical control tower that combines these indicators into one dashboard.

### Business areas covered

| Area | Dashboard Focus |
|---|---|
| Inventory | Total inventory and inventory trend |
| Sales | Units sold |
| Demand | Monthly demand forecast |
| Replenishment | Reorder point and order quantity |
| Supplier Management | Supplier lead-time comparison |
| Decision Support | KPI cards and analytical charts |

---

# 🛠️ Technology & Tools

| Category | Technology |
|---|---|
| Analytics Platform | SAP Analytics Cloud |
| Data Source | Supply-chain CSV dataset |
| Data Preparation | SAP Analytics Cloud Dataset |
| Visualization | SAP Analytics Cloud Stories |
| Story Type | Canvas Story |
| Dashboard | Supply Chain Inventory & Replenishment Control Tower |
| Analysis | Measures, Dimensions & Calculations |

---

# 📂 Dataset

## Dataset Name

`SC_Inventory_Replenishment_Analytics`

The source dataset contains **91,251 rows across 15 fields** and was designed to support analysis of inventory, demand, replenishment, supplier lead time and related operational measures.

### Important SAC Trial Account Note

Because this project was developed using an **SAP Analytics Cloud trial account**, the interactive dataset view available for analysis exposed **2,000 records**.

However, the **2,000-record view should not be interpreted as the size of the original dataset**.

The original source contained:

> **91,251 rows**

The SAC trial analysis view exposed:

> **2,000 records**

I also performed **full dataset validation**, which covered the underlying **91,251 source rows**.

SAC returned:

> **"Your dataset has no issues."**

This distinction was important because it confirmed that the complete source dataset was validated even though the trial environment displayed only 2,000 records for interactive analysis.

### Dataset Summary

| Dataset Attribute | Details |
|---|---|
| Dataset Name | `SC_Inventory_Replenishment_Analytics` |
| Source | Supply-chain CSV |
| Original Source Rows | **91,251** |
| SAC Interactive Analysis View | **2,000 records** |
| Fields | **15** |
| Full Dataset Validation | **Passed** |
| Validation Result | **No issues** |

---

# 🧩 Dataset Structure

The dataset contains measures and dimensions used throughout the dashboard.

## Measures

- `Units_Sold`
- `Inventory_Level`
- `Supplier_Lead_Time_Days`
- `Reorder_Point`
- `Order_Quantity`
- `Unit_Cost`
- `Unit_Price`
- `Promotion_Flag`
- `Stockout_Flag`
- `Demand_Forecast`

## Dimensions

- `Date`
- `SKU_ID`
- `Warehouse_ID`
- `Supplier_ID`
- `Region`

These fields provided the analytical context needed to examine supply-chain performance by time, product, warehouse, supplier and region.

---

# 🔄 Project Workflow

The complete project followed this workflow:

```text
Raw CSV Dataset
       ↓
SAP Analytics Cloud
       ↓
Dataset Creation
       ↓
Dataset Configuration
       ↓
Full Dataset Validation
       ↓
Measures & Calculations
       ↓
Story Creation
       ↓
Chart Configuration
       ↓
KPI Cards
       ↓
Dashboard Design
       ↓
Supply Chain Control Tower
