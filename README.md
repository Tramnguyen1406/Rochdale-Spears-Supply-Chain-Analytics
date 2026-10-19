<div align="center">

# 📊 Supply Chain Performance Analytics

### Rochdale Spears Group | Power BI Portfolio Project

**Supply Chain Analytics • Business Intelligence • Data Visualization**

![Power BI](https://img.shields.io/badge/Power_BI-Dashboard-F2C811?style=for-the-badge)
![Excel](https://img.shields.io/badge/Excel-Dataset-217346?style=for-the-badge)
![DAX](https://img.shields.io/badge/DAX-Analytics-7B61FF?style=for-the-badge)
![Supply Chain](https://img.shields.io/badge/Supply_Chain-Performance-2563EB?style=for-the-badge)

</div>

---

## 01. 📌 Project Overview

### Background

This project explores the supply chain operations of
**Rochdale Spears Group** through data analysis and
interactive Power BI dashboards.

The dataset represents the operational activities of a
wholesaler, including procurement, inventory management,
customer order fulfillment, and demand forecasting.

The project combines **Design Thinking and Business Intelligence**
to transform operational data into meaningful insights
that support supply chain decision-making.

### 🎯 Project Objectives

- Evaluate supplier shipment reliability.
- Monitor customer order fulfillment performance.
- Analyze inventory levels and stock availability.
- Assess inventory coverage against forecasted demand.
- Identify potential supply chain risks and inefficiencies.
- Develop interactive dashboards to support operational decisions.

### Project Information

| Category | Description |
|---|---|
| Project | Supply Chain Performance Analytics |
| Case Study | Rochdale Spears Group |
| Business Function | Supply Chain Management |
| Primary Stakeholder | Supply Chain Manager |
| Data Source | Excel Workbook |
| BI Tool | Microsoft Power BI |
| Methodology | Design Thinking & Data Analytics |
| Key Skills | Power Query, DAX, Data Modeling, Data Visualization |

---

## 02. 📂 Dataset Overview

### 2.1 Dataset Description

**Source:** `Data_supply chain baselining_202306.xlsx`

The dataset contains operational records related to
procurement, inventory management, customer orders,
and demand forecasting.

The source workbook includes **five main datasets**
representing interconnected supply chain activities.

### 2.2 Dataset Summary

| Dataset | Description | Time Coverage |
|---|---|---|
| Purchase Order | Purchase orders placed with manufacturers | Previous 12 months |
| Wholesaler Inventory Record | Monthly inventory snapshots | Previous 12 months |
| Wholesaler Customer Order Record | Customer orders received and shipped | Previous 15 months |
| Wholesaler Order Forecast | Forecasted customer demand | Next 12 months |
| SKU Mapping | Product attributes and master data | Reference table |

### 2.3 Dataset Details

#### 📦 Dataset 1 — Purchase Order

Contains procurement transactions between the wholesaler
and manufacturers.

**Main attributes:**

- Vendor Code
- Purchase Order Number
- SKU
- Order Acceptance Date
- Confirmed Ship Date
- Actual Ship Date
- Order Quantity

**Analytical purpose:**

Evaluate supplier reliability, shipment delays,
and procurement performance.

#### 🏭 Dataset 2 — Wholesaler Inventory Record

Contains monthly inventory snapshots at the
distribution center.

**Main attributes:**

- SKU
- Inventory Snapshot Date
- Inventory Quantity

**Analytical purpose:**

Monitor inventory levels, identify stock variations,
and evaluate inventory availability.

#### 🚚 Dataset 3 — Wholesaler Customer Order Record

Contains customer orders received and shipped
by the wholesaler.

**Main attributes:**

- Customer Code
- Customer Order Number
- Order Receipt Date
- Earliest Ship Date
- Latest Ship Date
- Actual Ship Date
- SKU
- Order Quantity

**Analytical purpose:**

Analyze customer demand, shipment performance,
and order fulfillment reliability.

#### 📈 Dataset 4 — Wholesaler Order Forecast

Contains forecasted customer demand at SKU level.

**Analytical purpose:**

- Analyze future demand.
- Evaluate inventory coverage.
- Identify potential stock shortages.
- Support inventory planning.

#### 🏷️ Dataset 5 — SKU Mapping

Contains product reference information.

**Main attributes:**

- SKU
- Style
- Color
- Size

**Analytical purpose:**

Support product segmentation and connect
operational datasets through SKU identifiers.

---

## 03. 🧠 Design Thinking Methodology

The project follows a **human-centered Design Thinking approach**
to ensure that dashboard development addresses
stakeholder needs and relevant business questions.

The methodology consists of five stages:

**Empathize → Define → Ideate → Prototype → Test**

### Step 1 — Empathize

**Objective:** Understand the dataset, business context,
and stakeholder expectations.

| Sub-step | Activities | Output |
|---|---|---|
| 1.1 Dataset Discovery | Identify dimensions, measures, and relevant attributes | Dataset understanding |
| 1.2 Stakeholder Identification | Identify dashboard users and responsibilities | Supply Chain Manager |
| 1.3 Stakeholder Needs | Understand reporting expectations and information needs | Stakeholder requirements |
| 1.4 Business Context | Explore procurement, inventory, and fulfillment processes | Business understanding |

**Key questions:**

- Who will use the dashboard?
- What is the purpose of the analysis?
- What information does the stakeholder need?
- Which business decisions should the dashboard support?

### Step 2 — Define

**Objective:** Translate stakeholder needs into
specific analytical problems.

| Sub-step | Activities | Output |
|---|---|---|
| 2.1 Define Point of View | Analyze challenges from the stakeholder perspective | Business POV |
| 2.2 Identify Pain Points | Identify potential supply chain performance issues | Business challenges |
| 2.3 Define Business Questions | Translate challenges into analytical questions | Business questions |
| 2.4 Define North Star Metric | Identify a primary performance indicator | Customer On-Time Fulfillment Rate |

**Problem Statement:**

> How can Rochdale Spears Group improve end-to-end
> supply chain visibility to identify operational
> performance gaps and support better decisions?

### Step 3 — Ideate

**Objective:** Develop the analytical framework
and dashboard design concept.

| Sub-step | Activities | Output |
|---|---|---|
| 3.1 KPI Selection | Define performance indicators | KPI framework |
| 3.2 Analytical Dimensions | Identify time, supplier, customer, and product dimensions | Analytical structure |
| 3.3 Dashboard Planning | Organize analytical perspectives | Dashboard structure |
| 3.4 Visualization Selection | Select charts according to business questions | Visualization plan |
| 3.5 Wireframing | Plan the visual layout | Dashboard mockup |

### Step 4 — Prototype

**Objective:** Develop the Power BI analytical solution.

| Sub-step | Activities | Output |
|---|---|---|
| 4.1 Data Preparation | Clean and transform datasets | Prepared data |
| 4.2 Data Modeling | Establish analytical relationships | Data model |
| 4.3 DAX Development | Create analytical measures | KPI calculations |
| 4.4 Dashboard Development | Build Power BI visualizations | Dashboard |
| 4.5 Interactive Features | Configure slicers and filters | Interactive reporting |

### Step 5 — Test & Iterate

**Objective:** Evaluate analytical accuracy,
dashboard usability, and business relevance.

| Sub-step | Activities | Expected Output |
|---|---|---|
| 5.1 KPI Validation | Verify calculation consistency | Reliable KPIs |
| 5.2 Usability Review | Assess navigation and readability | Usability improvements |
| 5.3 Business Relevance | Review alignment with business questions | Analytical validation |
| 5.4 Dashboard Refinement | Improve layout and visualizations | Refined dashboard |
| 5.5 Insights & Recommendations | Translate findings into business actions | Recommendations |

### Design Thinking Summary

| Stage | Main Focus | Deliverable |
|---|---|---|
| Empathize | Understand stakeholder needs | Dataset & stakeholder analysis |
| Define | Identify business problems | Problem statement & KPIs |
| Ideate | Develop analytical solutions | Dashboard concept |
| Prototype | Build Power BI dashboard | Analytical dashboard |
| Test | Validate and improve | Refined solution |

---

## 04. ⚙️ Data Preparation & Transformation

**Tool: Power Query**

The data preparation framework focuses on
improving data quality and preparing the
source tables for analysis.

### Data Preparation Activities

| Step | Description |
|---|---|
| Data Profiling | Review data structure, missing values, and data quality |
| Data Type Validation | Standardize dates, quantities, and identifiers |
| Duplicate Verification | Identify duplicate records while preserving valid order lines |
| Data Consistency | Verify SKU, supplier, and customer identifiers |
| Data Transformation | Prepare fields required for analytical reporting |
| Data Validation | Review consistency after transformation |

---

## 05. 🔗 Data Modeling

The analytical model connects procurement,
inventory, customer orders, forecasts,
and product information.

The SKU identifier serves as a common
reference across the source tables.

### Source Table Relationships

| Table | Key | Analytical Role |
|---|---|---|
| Purchase Order | SKU | Supplier performance |
| Inventory Record | SKU | Inventory analysis |
| Customer Order Record | SKU | Customer fulfillment |
| Order Forecast | SKU | Demand planning |
| SKU Mapping | SKU | Product dimension |

### Power BI Data Model

![Power BI Data Model](images/data-model.png)

*Figure 1. Power BI data model and table relationships.*

---

## 06. 📐 KPI Development

The dashboard uses supply chain KPIs
to evaluate operational performance.

| Analytical Area | Key Performance Indicators |
|---|---|
| Supplier Performance | Supplier On-Time Rate, Average Delay Days |
| Customer Fulfillment | Customer On-Time Shipment Rate |
| Inventory Management | Ending Inventory, Inventory Trends |
| Demand Planning | Forecast Demand, Months of Supply |

### Supplier On-Time Shipment Rate

Measures the proportion of eligible supplier
shipments dispatched on time.

**Formula:**

`On-Time Supplier Shipments / Total Eligible Shipments × 100`

### Customer On-Time Shipment Rate

Measures the proportion of eligible customer
orders shipped within their committed timelines.

**Formula:**

`On-Time Customer Orders / Total Eligible Customer Orders × 100`

### Supplier Delay Days

Measures the difference between actual
and confirmed shipment dates.

**Formula:**

`Actual Ship Date - Confirmed Ship Date`

### Months of Supply (MOS)

Estimates inventory coverage based on
forecasted customer demand.

**Formula:**

`Ending Inventory / Average Monthly Forecast Demand`

*Note: Final KPI calculations depend on the
business rules and DAX measures implemented
in the Power BI model.*

---

## 07. 📊 Power BI Dashboard

The Power BI report provides interactive
visualizations to explore supply chain performance.

### Dashboard 1 — Supply Chain Overview

**Business Question:**

How effectively is the overall supply chain performing?

![Supply Chain Overview](images/dashboard-overview.png)

*Figure 2. Supply Chain Performance Overview.*

### Dashboard 2 — Supplier Performance

**Business Question:**

Are suppliers meeting shipment commitments?

![Supplier Performance](images/supplier-performance.png)

*Figure 3. Supplier Performance Analysis.*

### Dashboard 3 — Customer Fulfillment

**Business Question:**

Are customer orders being shipped on time?

![Customer Fulfillment](images/customer-fulfillment.png)

*Figure 4. Customer Fulfillment Analysis.*

### Dashboard 4 — Inventory & Demand

**Business Question:**

Are inventory levels aligned with forecasted demand?

![Inventory and Demand](images/inventory-demand.png)

*Figure 5. Inventory and Demand Analysis.*

---

## 08. 🔍 Key Insights

This section presents the main findings
identified through the Power BI analysis.

| Analytical Area | Key Finding | Business Implication |
|---|---|---|
| Supplier Performance | To be completed | To be completed |
| Customer Fulfillment | To be completed | To be completed |
| Inventory Management | To be completed | To be completed |
| Demand Planning | To be completed | To be completed |

---

## 09. 💡 Business Recommendations

Business recommendations will be developed
based on the analytical findings.

Potential improvement areas include:

- Supplier delivery reliability.
- Customer order fulfillment.
- Inventory planning.
- Demand forecasting.
- Supply chain performance monitoring.

---

## 10. 🛠️ Tools & Technologies

| Tool | Application |
|---|---|
| Microsoft Excel | Source dataset |
| Power Query | Data cleaning and transformation |
| Power BI | Data modeling and visualization |
| DAX | KPI calculations |
| Design Thinking | Stakeholder analysis and problem definition |

---

## 👩‍💻 Author

**Mai Tram Nguyen**

MBA Graduate in Logistics & Supply Chain Management

**Professional Interests:**

Supply Chain Analytics • Data Analytics •
Business Intelligence • Inventory Management •
Demand Planning

**Technical Skills:**

Power BI • SQL • Excel • Power Query • DAX

---

## 📌 Project Status

Portfolio documentation in progress.

Dashboard screenshots, analytical findings,
and business recommendations will be updated
as the project documentation is finalized.
