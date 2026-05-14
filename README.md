# Major-project-II
A real-time E-Commerce Sales Analytics Dashboard built using Microsoft Power BI, Azure Data Factory, Azure SQL Database, and CSV data integration for automated sales insights and business intelligence.


# E-Commerce Sales Analytics Dashboard using Microsoft Azure and Power BI

## Project Overview

The **E-Commerce Sales Analytics Dashboard** is a cloud-integrated Business Intelligence (BI) project developed using **Microsoft Power BI** and **Microsoft Azure** to analyze and visualize e-commerce sales data in real time.

This dashboard provides meaningful business insights such as **total sales, profit, order trends, category performance, regional sales analysis, payment mode preferences, and top-selling products**.

The project uses **Azure Data Factory, Azure Blob Storage, and Azure SQL Database** to automate data ingestion and synchronization. Whenever new sales records are added to the CSV dataset, the Power BI dashboard updates automatically, enabling **real-time analytics and automated reporting**.

## Features

- Real-time dashboard updates
- Interactive Power BI visualizations
- Azure cloud integration
- Automated data pipeline
- Sales and profit analysis
- Region-wise and category-wise insights
- Payment mode analysis
- Monthly sales trend monitoring
- Top-selling products analysis
- KPI-based performance tracking

## System Architecture

```text
CSV Sales Dataset
        │
        ▼
Azure Blob Storage
        │
        ▼
Azure Data Factory Pipeline
        │
        ▼
Azure SQL Database
        │
        ▼
Microsoft Power BI Dashboard
        │
        ▼
Real-Time Business Insights

Technologies Used
Microsoft Power BI
Microsoft Azure
Azure Data Factory (ADF)
Azure SQL Database
Azure Blob Storage
SQL
CSV Dataset
Business Intelligence (BI)
Project Workflow
Sales data is collected in CSV format.
CSV file is uploaded to Azure Blob Storage.
Azure Data Factory transfers data to Azure SQL Database.
Power BI connects with Azure SQL Database.
Dashboard automatically refreshes when new data is added.
Real-time business insights are displayed.
Key Insights Generated
Total Sales Analysis
Total Profit Analysis
Category-wise Sales
Region-wise Sales
Monthly Sales Trends
Payment Mode Distribution
Top Products by Sales
Profit Margin Analysis
Real-Time Update Feature

The major feature of this project is automatic dashboard synchronization.

Whenever a new entry is added to the CSV dataset:

Azure Data Factory updates the database
Azure SQL synchronizes the latest records
Power BI refreshes automatically
Updated analytics are displayed instantly
Project Screenshots
Azure Resource Group

(Add Screenshot)

Azure Pipeline Execution

(Add Screenshot)

Azure SQL Database

(Add Screenshot)

Power BI Dashboard

(Add Screenshot)

Future Enhancements
AI-based sales prediction
Customer behavior analytics
Inventory management integration
Live API integration
Mobile dashboard support
