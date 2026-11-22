# Customer Behavior Analytics Project

## Project Overview

This project demonstrates an end-to-end data analytics workflow, covering data loading, exploratory data analysis (EDA), data cleaning, SQL analysis, dashboard development, and business reporting.

The objective is to transform raw data into meaningful insights using Python, SQL, and Power BI, and present the findings through an interactive dashboard and a business-focused report.

## Dataset

- **Dataset:** [Dataset Name]
- **Source:** [Dataset Source / URL]
- **Records:** [Number of Rows]
- **Fields:** [Number of Columns]
- **Domain:** [Sales / Marketing / Finance / Retail / Other]

The dataset was imported into Python for initial exploration, data quality assessment, and preprocessing before further analysis.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data processing, analysis, and automation |
| Pandas & NumPy | Data manipulation and cleaning |
| Matplotlib & Seaborn | Exploratory data analysis and visualization |
| Jupyter Notebook | Interactive analysis and documentation |
| SQL (PostgreSQL / MySQL / SQL Server) | Data querying and business analysis |
| Power BI | Interactive dashboard development |
| PowerPoint | Presentation of findings and recommendations |
| Git & GitHub | Version control and project documentation |

## Project Workflow

### 1. Data Loading
- Imported the dataset into Python using Pandas.
- Reviewed dataset structure, dimensions, column names, and data types.
- Evaluated initial data quality and completeness.

### 2. Exploratory Data Analysis (EDA)
- Analyzed distributions, trends, patterns, and relationships between variables.
- Identified potential outliers and anomalies.
- Used statistical summaries and visualizations to understand the dataset.
- Developed initial observations and analytical questions.

### 3. Data Cleaning & Preparation
- Handled missing and duplicate values.
- Corrected data types and inconsistent formats.
- Standardized column names and categorical values.
- Addressed data quality issues and prepared the dataset for analysis.

### 4. SQL Analysis
- Loaded the cleaned dataset into a SQL database.
- Developed SQL queries to answer business questions.
- Used aggregations, joins, CTEs, subqueries, and window functions where applicable.
- Analyzed key metrics, trends, performance drivers, and segment-level insights.

### 5. Power BI Dashboard
- Connected Power BI to the prepared dataset.
- Developed data relationships and measures using DAX.
- Designed an interactive dashboard to monitor key performance indicators (KPIs).
- Added filters, slicers, and visualizations to support detailed analysis.

### 6. Reporting & Business Insights
- Consolidated findings from Python, SQL, and Power BI.
- Identified key trends, performance gaps, and business opportunities.
- Developed actionable recommendations based on the analysis.
- Created a concise business report summarizing insights and recommendations.

### 7. PowerPoint Presentation
- Created a presentation using the key findings from the analysis.
- Highlighted important metrics, trends, and business implications.
- Presented recommendations in a clear, structured, and business-focused format.

## Dashboard

The Power BI dashboard provides an interactive view of the dataset and its key performance indicators.

**Dashboard Highlights**
- KPI overview
- Trend analysis
- Category and segment performance
- Comparative analysis
- Interactive filtering and drill-downs
- Key performance drivers and insights

> Add dashboard screenshots here.

![Dashboard Preview](images/dashboard.png)

## Key Results & Insights

The analysis identified key trends, patterns, and performance drivers within the dataset.

- **Key Insight 1:** [Describe the most important finding.]
- **Key Insight 2:** [Describe a trend or performance comparison.]
- **Key Insight 3:** [Describe an opportunity, risk, or performance gap.]

### Business Recommendations

- [Recommendation based on Insight 1.]
- [Recommendation based on Insight 2.]
- [Recommendation based on Insight 3.]

## Project Structure

```text
data-analytics-project/
│
├── data/
│   ├── raw/
│   │   └── dataset.csv
│   └── processed/
│       └── cleaned_dataset.csv
│
├── notebooks/
│   ├── 01_data_loading_and_eda.ipynb
│   └── 02_data_cleaning.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── dashboard/
│   └── analytics_dashboard.pbix
│
├── reports/
│   ├── business_report.pdf
│   └── presentation.pptx
│
├── images/
│   └── dashboard.png
│
├── requirements.txt
└── README.md
```

## How to Run

### Prerequisites

Install the following:

- Python 3.10+
- Jupyter Notebook
- PostgreSQL, MySQL, or SQL Server
- Power BI Desktop

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/data-analytics-project.git
```

```bash
cd data-analytics-project
```

### 2. Set Up Python Environment

```bash
python -m venv venv
```

Activate the environment:

**Windows**
```bash
venv\Scripts\activate
```

**macOS/Linux**
```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Python Analysis

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebooks in the `notebooks/` folder and execute the cells sequentially.

### 5. Run SQL Queries

- Create a database in your preferred SQL platform.
- Import the cleaned dataset into the database.
- Open the SQL scripts in the `sql/` folder.
- Execute the queries to reproduce the analysis.

### 6. Explore the Power BI Dashboard

Open the `.pbix` file located in the `dashboard/` folder using Power BI Desktop.

Refresh the dataset if required and interact with the dashboard filters and visuals.

## Project Deliverables

- Python notebooks covering data loading, EDA, and data cleaning.
- SQL scripts containing business analysis queries.
- Interactive Power BI dashboard.
- Business report documenting key findings and recommendations.
- PowerPoint presentation summarizing the project.

**Author - Arun Jyoti Naskar**
Marketing & Sales Analytics | Python | SQL | Power BI
