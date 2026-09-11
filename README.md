# VirtuBox Data Analyst Assessment

LIVE DASHBOARD: https://datastudio.google.com/reporting/b8baf7cc-0f13-4201-9b09-82820e8bf021

## Project Overview
This project was completed as part of the Data Analyst Assessment for VirtuBox Infotech Private Limited.

The analysis focuses on understanding sales, profit, product-category performance, geographic performance, and business opportunities using an Indian E-Commerce dataset.

## Dataset
**Dataset:** Indian E-Commerce Sales Dataset  
**Source:** Kaggle – E-Commerce Data by Ben Roshan  
**Period:** April 2018 – March 2019

The dataset contains three related files:
- List of Orders
- Order Details
- Sales Target

The primary joining key is Order ID.

## Data Processing
The data was cleaned and integrated before analysis. The processing included:
- Checking missing values
- Checking duplicate records
- Standardizing data
- Joining related datasets using Order ID
- Preparing the data for analysis
- Creating calculated business metrics

Python/Pandas and spreadsheet-based analysis were used during the project.

## Business Analysis
The analysis examined:
- Sales and profit by category and sub-category
- Geographic sales performance
- Monthly sales trends
- Sales volume versus profitability
- Performance against available sales targets

## Key Findings
1. Electronics is one of the strongest categories by sales.
2. Clothing shows strong profitability.
3. Furniture generates meaningful sales but comparatively weaker profitability.
4. Sales performance varies across states.
5. Sales and profit fluctuate over time.
6. High sales volume does not necessarily result in high profitability.

## Recommendations
1. Review Furniture pricing, costs, discounts, and sub-category profitability.
2. Focus inventory and business expansion on strong-performing categories and products.
3. Develop targeted strategies for high- and low-performing geographic markets.

## Dashboard
An interactive Looker Studio dashboard was created containing:
- Total Sales
- Total Profit
- Total Quantity
- Profit Margin
- Monthly Sales Trend
- Profit by Category
- Top States by Sales
- Top Sub-Categories by Profit
- State and Category filters

The dashboard link is available in the supporting project files.
**Dashboard**: https://datastudio.google.com/reporting/b8baf7cc-0f13-4201-9b09-82820e8bf021
streamlit: https://indian-ecommerce-dashboard-yk4ra5a8fbv6ky9ddukz78.streamlit.app/

## Limitations
The dataset covers only April 2018 to March 2019. It also does not contain important variables such as marketing expenditure, customer acquisition cost, inventory costs, operating costs, and detailed pricing/discount information.

Therefore, causal conclusions about why profitability differs cannot be made safely from this dataset alone.

## AI Usage
ChatGPT was used for brainstorming business questions and hypotheses, structuring insights and recommendations, explaining analysis concepts, and supporting documentation.

All calculations, dashboard results, business interpretations, and final conclusions were checked against the actual project data and modified where necessary.

## Project Files
The repository contains the supporting files for the completed assessment, including the dataset, analysis/code, presentation, and project documentation.
