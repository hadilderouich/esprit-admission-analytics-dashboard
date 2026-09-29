# Smart Power BI Dashboard for ESPRIT

An interactive **Business Intelligence and AI analytics platform** developed as part of an academic PIdev project at **ESPRIT**.

The project focuses on transforming admission-related data into meaningful visual insights to support **admission process monitoring, data analysis, and strategic decision-making**.

## About the Project

The **Smart Power BI Dashboard** provides an interactive environment for analyzing historical and real-time admission data.

The solution combines **Power BI, SQL Server, and Python-based analytics** to transform raw data into interactive dashboards and actionable insights.

The platform was designed to help decision-makers monitor admission activities, identify trends, and better understand the evolution of admission-related data.

## Main Features

- Interactive admission monitoring dashboards
- Historical data analysis
- Real-time data visualization
- Admission statistics and KPIs
- Strategic insights from data
- Interactive filters and drill-down analysis
- Data preparation and transformation
- AI-powered analytics
- Visual representation of admission trends
- User-friendly and interactive interface

## Technology Stack

### Business Intelligence

- Power BI
- Power BI Service
- Data Visualization
- KPI Dashboards

### Database

- SQL Server
- SQL
- Data Warehouse

### Data Engineering

- ETL
- Data Preparation
- Data Transformation

### AI & Analytics

- Python
- Machine Learning
- Predictive Analytics

## Project Architecture

```text
                 ┌──────────────────────┐
                 │   Source Data        │
                 │  Admission Records   │
                 └──────────┬───────────┘
                            │
                            ▼
                 ┌──────────────────────┐
                 │     SQL Server       │
                 │   Database / DWH     │
                 └──────────┬───────────┘
                            │
                            │ ETL
                            ▼
                 ┌──────────────────────┐
                 │   Data Processing    │
                 │   & Transformation   │
                 └──────────┬───────────┘
                            │
                 ┌──────────┴───────────┐
                 │                      │
                 ▼                      ▼
        ┌─────────────────┐    ┌─────────────────┐
        │     Power BI    │    │     Python      │
        │   Dashboards    │    │ AI / Analytics  │
        └────────┬────────┘    └────────┬────────┘
                 │                      │
                 └──────────┬───────────┘
                            ▼
                 ┌──────────────────────┐
                 │ Strategic Insights  │
                 │ & Decision Support  │
                 └──────────────────────┘








https://github.com/user-attachments/assets/3beab82f-c076-4ef1-8f8f-33c9dea13316



