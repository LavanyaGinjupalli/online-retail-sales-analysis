# Online-retail-sales-analysis
Data cleaning, exploratory analysis, and visualization of an online retail sales customer dataset. Includes preprocessing workflows, customer behavior insights, sales trend analysis, and reproducible notebooks for collaborative data analysis.

<h2>📊 Project Overview</h2>

This repository contains a collaborative data science project focused on cleaning, analyzing, and visualizing online retail sales and customer transaction data. The goal is to build a reproducible workflow that uncovers insights about customer behavior, product performance, and sales trends. The project uses a team‑friendly Git workflow with branches, pull requests, and code reviews to ensure smooth collaboration and zero merge conflicts.

<h2>🚀 Project Architecture</h2>

<h3>🔷 Medallion Data Layers</h3>
1. Bronze — Raw ingested data (no cleaning)<br>
2. Silver — Cleaned, validated, structured data<br>
3. Gold — Aggregated, business‑ready analytics tables<br>

<h2> 🧪 Environments (Git Branches)</h2>

| Environment | Branch | Purpose |<br>
|------------|--------|---------|<br>
| **DEV** | `dev` | Experiments, early development, trial notebooks |<br>
| **UAT** | `uat` | Testing, validation, review |<br>
| **PRD** | `main` | Stable, approved production code |<br>

<h2>📦 Dataset Description</h2>

The dataset includes transaction‑level online retail sales records, containing:
1. Invoice numbers
2. Product descriptions and stock codes
3. Quantities purchased
4. Unit prices
5. Customer IDs
6. Invoice dates
7. Country information

This dataset enables analysis of customer behavior, product performance, and time‑based sales trends.


<h2>🎯 Project Objectives</h2>

1. Clean and preprocess raw retail transaction data
2. Handle missing values, duplicates, and outliers
3. Perform exploratory data analysis (EDA)
4. Visualize customer behavior and sales trends
5. Build interactive dashboards
6. Collaborate using GitHub workflows
7. Document insights and findings clearly


<h2>🧱 Tech Stack</h2>

This project uses a modern Python data science and visualization stack:
1. NumPy — numerical computing
2. pandas — data cleaning & manipulation
3. SciPy — statistical analysis
4. Matplotlib — foundational plotting
5. Seaborn — statistical visualizations
6. Plotly — interactive charts
7. Dash — interactive dashboards
8. Jupyter Notebooks
9. Git & GitHub
10. VS Code / JupyterLab
11. Medallion Architecture Principles


<h2>📁 Folder Structure</h2>

online-retail-sales-analysis/<br>
│<br>
├── data/<br>
│   ├── bronze/                # Original dataset (read-only)<br>
│   ├── silver/          # Cleaned datasets<br>
|   └── gold/          # Business-ready datasets<br>
│<br>
├── notebooks/<br>
│   ├── bronze_ingestion.ipynb<br>
│   ├── silver_cleaning.ipynb<br>
│   └── gold_analytics.ipynb<br>
│<br>
├── dashboards/<br>
│   └── retail_dashboard.py # Dash app<br>
│<br>
├── scripts/<br>
│   ├── bronze_ingest.py<br>
│   ├── silver_clean.py<br>
│   └── gold_transform.py<br>
│<br>
├── docs/<br>
│   └── project_plan.md<br>
│<br>
├── .gitignore<br>
├── CONTRIBUTING.md<br>
└── README.md<br>


<h2>🔄 Collaboration Workflow</h2>

This project uses a branch‑based workflow to avoid conflicts and ensure clean merges.

1. Clone the repository
   
   git clone https://github.com/<your-username>/online-retail-sales-analysis.git

2. Create a new branch

  git checkout -b feature/<your-task-name>

3. Make changes → Commit → Push

   git add .
   git commit -m "Your message"
   git push origin feature/<your-task-name>

4. Open a Pull Request

   All changes must go through a PR and be approved before merging.


<h2>🤝 Contribution Guidelines</h2>

See CONTRIBUTING.md for:

1. Branch naming rules
2. Commit message style
3. PR review process
4. Code formatting standards


<h2>📈 Expected Insights</h2>

This project aims to uncover:

1. Top‑selling products
2. Customer purchasing patterns
3. Seasonal and monthly sales trends
4. Revenue distribution across countries
5. Customer segmentation opportunities
6. Interactive dashboards for business insights

<h2>🧪 Future Enhancements</h2>

1. RFM customer segmentation
2. Time‑series forecasting
3. Dash or Streamlit dashboards
