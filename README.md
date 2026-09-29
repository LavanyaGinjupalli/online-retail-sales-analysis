# 🛍️ Online Retail Sales Analysis

<p align="center">
  <strong>End-to-End Data Analytics Project | Python • Pandas • SQL • Plotly • Dash</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Plotly-Visualization-3F4F75?logo=plotly&logoColor=white" />
  <img src="https://img.shields.io/badge/Dash-Interactive%20Dashboard-00A4EF?logo=plotly&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-GitHub-black?logo=git&logoColor=white" />
</p>

---

## 📌 Project Overview

**Online Retail Sales Analysis** is an end-to-end data analytics project focused on transforming raw online retail transaction data into **clean, validated, business-ready datasets and actionable insights**.

The project follows a **Medallion Architecture** approach:

> 🥉 **Bronze → 🥈 Silver → 🥇 Gold**

The workflow covers data ingestion, data cleaning, exploratory analysis, business analytics, visualization, and interactive dashboard development.

The project also demonstrates a **Git-based collaborative development workflow** using feature branches, pull requests, code reviews, and environment-based deployments.

---

## 🎯 Business Objectives

The primary goal is to understand **what drives online retail sales and customer purchasing behavior**.

Key objectives include:

* 🧹 Clean and preprocess raw transaction data
* 🔍 Identify missing values, duplicates, and data-quality issues
* 📊 Analyze sales and customer behavior
* 🛍️ Identify high-performing products
* 🌎 Analyze revenue across countries
* 📅 Discover monthly and seasonal sales trends
* 👥 Identify customer purchasing patterns
* 📈 Build interactive business dashboards
* 🔄 Create a reproducible analytics workflow
* 🤝 Demonstrate professional Git/GitHub collaboration practices

---

# 🏗️ Project Architecture

## 🔷 Medallion Data Architecture

The project organizes data into three analytical layers.

```text
                 ┌─────────────────────┐
                 │    🥉 BRONZE        │
                 │     Raw Data        │
                 │  Original Dataset   │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │    🥈 SILVER        │
                 │   Cleaned Data      │
                 │ Validated & Structured│
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │     🥇 GOLD         │
                 │ Business Analytics  │
                 │ Aggregated Tables    │
                 └──────────┬──────────┘
                            │
                            ▼
                 ┌─────────────────────┐
                 │ 📊 DASHBOARD        │
                 │ Business Insights   │
                 │ Interactive Reports │
                 └─────────────────────┘
```

### 🥉 Bronze — Raw Data

Contains the original ingested dataset.

**Purpose:**

* Preserve source data
* Maintain data lineage
* Keep the raw dataset unchanged
* Provide a reproducible starting point

### 🥈 Silver — Cleaned Data

Contains cleaned and validated transaction-level data.

**Processing includes:**

* Missing-value handling
* Duplicate removal
* Data-type correction
* Validation
* Outlier handling
* Data-quality checks
* Feature preparation

### 🥇 Gold — Business-Ready Data

Contains aggregated datasets designed for analytics and visualization.

Examples include:

* Monthly revenue
* Weekly revenue
* Country revenue
* Product revenue
* Customer-level metrics

---

# 🌍 Environment Strategy

The project uses Git branches to represent different development environments.

| Environment | Branch | Purpose                                         |
| ----------- | ------ | ----------------------------------------------- |
| 🧪 **DEV**  | `dev`  | Development, experimentation, and testing       |
| 🔍 **UAT**  | `uat`  | Validation, review, and user acceptance testing |
| 🚀 **PRD**  | `main` | Stable and approved production code             |

### Development Flow

```text
Feature Branch
      │
      ▼
     DEV
      │
      ▼
     UAT
      │
      ▼
    PRD / main
```

This workflow helps maintain code quality and provides a structured approach to collaborative development.

---

# 📦 Dataset

The project uses transaction-level online retail sales data containing information such as:

| Field                   | Description                   |
| ----------------------- | ----------------------------- |
| 🧾 Invoice Number       | Unique transaction identifier |
| 🏷️ Stock Code          | Product identifier            |
| 🛍️ Product Description | Product name/description      |
| 🔢 Quantity             | Number of units purchased     |
| 💰 Unit Price           | Price per unit                |
| 👤 Customer ID          | Customer identifier           |
| 📅 Invoice Date         | Transaction date              |
| 🌎 Country              | Customer country              |

This structure allows analysis across **products, customers, geography, and time**.

---

# 🔍 Analytical Areas

## 🛍️ Product Performance

Analyze:

* Top-selling products
* Revenue by product
* Product demand
* Quantity sold
* Product contribution to total revenue

## 👥 Customer Behavior

Analyze:

* Customer purchasing patterns
* Purchase frequency
* Customer revenue contribution
* Repeat purchasing behavior
* Customer segmentation opportunities

## 📅 Sales Trends

Analyze:

* Monthly revenue
* Weekly revenue
* Sales seasonality
* Revenue growth patterns
* Period-over-period performance

## 🌎 Geographic Analysis

Analyze:

* Revenue by country
* Customer distribution
* Country-level purchasing patterns
* Geographic revenue contribution

---

# 🧱 Tech Stack

### 🐍 Programming & Data Analysis

* **Python**
* **NumPy**
* **Pandas**
* **SciPy**

### 📊 Visualization

* **Matplotlib**
* **Seaborn**
* **Plotly**

### 📈 Interactive Analytics

* **Dash**
* **Jupyter Notebook**

### 🛠️ Development

* **Git**
* **GitHub**
* **VS Code**
* **JupyterLab**

### 🏗️ Data Architecture

* **Medallion Architecture**
* Bronze → Silver → Gold

---

# 📁 Repository Structure

```text
online-retail-sales-analysis/
│
├── 📂 data/
│   ├── 📂 bronze/
│   │   └── Original raw dataset
│   │
│   ├── 📂 silver/
│   │   └── Cleaned & validated datasets
│   │
│   └── 📂 gold/
│       └── Business-ready analytical datasets
│
├── 📂 notebooks/
│   ├── bronze_ingestion.ipynb
│   ├── silver_cleaning.ipynb
│   └── gold_analytics.ipynb
│
├── 📂 dashboards/
│   └── retail_dashboard.py
│
├── 📂 scripts/
│   ├── bronze_ingest.py
│   ├── silver_clean.py
│   └── gold_transform.py
│
├── 📂 docs/
│   └── project_plan.md
│
├── 📄 .gitignore
├── 📄 CONTRIBUTING.md
└── 📄 README.md
```

---

# 🔄 Data Pipeline

```text
Raw Retail Data
       │
       ▼
┌───────────────┐
│ Data Ingestion │
└───────┬───────┘
        │
        ▼
🥉 Bronze Layer
        │
        │ Cleaning
        │ Validation
        │ Transformation
        ▼
🥈 Silver Layer
        │
        │ Aggregation
        │ Business Metrics
        ▼
🥇 Gold Layer
        │
        ▼
📊 Interactive Dashboard
        │
        ▼
💡 Business Insights
```

---

# 📊 Dashboard

The interactive dashboard provides a business-focused view of the analyzed retail data.

### Dashboard capabilities

* 📌 KPI cards
* 📈 Revenue trends
* 🛍️ Product performance
* 🌎 Country-level revenue
* 📅 Monthly and weekly analysis
* 🔎 Interactive filters
* 🏆 Top-N product analysis
* 📊 Interactive Plotly visualizations

> **Dashboard:** `dashboards/retail_dashboard.py`

---

# 🤝 Git & Collaboration Workflow

The project follows a branch-based Git workflow designed to keep development organized and reduce merge conflicts.

### 1️⃣ Clone the repository

```bash
git clone https://github.com/LavanyaGinjupalli/online-retail-sales-analysis.git

cd online-retail-sales-analysis
```

### 2️⃣ Create a feature branch

```bash
git checkout -b feature/<feature-name>
```

### 3️⃣ Make changes

Develop, test, and validate the changes locally.

### 4️⃣ Commit changes

```bash
git add .
git commit -m "Add retail sales analysis"
```

### 5️⃣ Push the branch

```bash
git push origin feature/<feature-name>
```

### 6️⃣ Create a Pull Request

Open a Pull Request and request review before merging into the appropriate environment branch.

---

# 🤝 Contribution Guidelines

See [`CONTRIBUTING.md`](CONTRIBUTING.md) for detailed guidelines covering:

* 🌿 Branch naming conventions
* 📝 Commit message standards
* 🔍 Pull Request process
* 👀 Code review practices
* 🧹 Code formatting standards
* ✅ Testing and validation

---

# 💡 Expected Business Insights

The project is designed to answer questions such as:

### 🏆 What products drive revenue?

Identify products contributing the highest sales volume and revenue.

### 👥 Who are the most valuable customers?

Analyze customer purchasing behavior and revenue contribution.

### 📅 When do customers buy the most?

Identify monthly, weekly, and seasonal sales patterns.

### 🌎 Which countries generate the most revenue?

Compare geographic revenue contribution and customer activity.

### 📈 How is revenue changing over time?

Analyze sales trends and identify growth or decline patterns.

---

# 🚀 Future Enhancements

The project can be extended with additional analytics capabilities:

### 👥 RFM Customer Segmentation

Segment customers based on:

* **Recency**
* **Frequency**
* **Monetary Value**

### 🔮 Sales Forecasting

Implement time-series forecasting to estimate future sales trends.

### 🤖 Machine Learning

Explore:

* Customer segmentation
* Product recommendations
* Customer lifetime value
* Purchase prediction

### 📊 Enhanced Dashboard

Potential enhancements include:

* Streamlit version
* Advanced KPI monitoring
* Dynamic Top-N analysis
* Customer segmentation views
* Forecasting visualizations

---

# 📈 Key Skills Demonstrated

This project demonstrates practical experience with:

`Python` · `Pandas` · `NumPy` · `SQL` · `Data Cleaning` · `EDA` · `Data Validation` · `Data Transformation` · `Data Visualization` · `Plotly` · `Dash` · `Business Analytics` · `Git` · `GitHub` · `Medallion Architecture`

---

# 👩‍💻 Author

**Lavanya Ginjupalli**

Data Analyst | Business Intelligence | Data Analytics

📌 Toronto, Canada

---

⭐ **If you find this project useful, consider giving the repository a star!**


