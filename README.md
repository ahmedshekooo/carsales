📊 Retail Sales Performance Analysis (2003-2005)

This repository contains the data, analysis, and comprehensive review of retail sales performance spanning the years 2003 to 2005, focusing on identifying key revenue drivers, geographic contributions, and sales seasonality.

The goal of this project was to provide an executive summary and actionable insights for strategic planning, particularly focusing on maximizing performance in the subsequent quarter.

📁 Files in This Repository

File Name

Description

Location

sales_data_sample.csv

The raw transactional dataset containing order details, quantity, price, customer information, and geographic data.

Root Directory

notebook.ipynb

A Jupyter notebook containing the Python code (using Pandas and Matplotlib) for data cleaning, aggregation, and generating the core visualizations.

Root Directory

RETAIL SALES PERFORMANCE REVIEW (1).pdf

The final executive presentation and performance review document, summarizing all key findings and recommendations.

Root Directory

charts/

This folder contains all the visualizations generated during the analysis.

charts/ Directory

📈 Key Insights & Executive Summary

The analysis revealed several critical factors driving performance, which are detailed in the RETAIL SALES PERFORMANCE REVIEW (1).pdf:

1. Extreme Q4 Seasonality

The business exhibits strong Q4 seasonality, with the final quarter driving over one-third ($>1/3$) of total annual revenue.

November is the undisputed peak sales month, with sales volumes exceeding the trough month (September) by over 4x.

2. Product Line Performance

The Classic Cars product line is the dominant revenue driver, accounting for 39.07% ($3.92M) of total sales.

High-value product lines like Classic Cars and Trucks/Buses consistently generate a high average order value (over $3,700 per transaction).

3. Geographic Contribution

The market is highly concentrated, with EMEA and North America (NA) acting as the core markets, responsible for over 83% of total revenue.

Specifically, the USA is the top-performing country, contributing 44.92% ($3.63M) of the total geographic revenue analyzed.

4. Deal Size Distribution

The majority of transactions are characterized by Medium and Small deal sizes (94.8% of transactions), suggesting a strong foundation of repeat-purchase and customer loyalty.

🖼️ Charts & Visualizations

The following charts illustrate the key findings from the analysis, with source files located in the charts/ directory.

Monthly Sales Seasonality (Q4 Focus)

This chart highlights the significant revenue spike in the fourth quarter, particularly in November (Month ID 11).

![Monthly Sales Seasonality](charts/Screenshot 2025-11-17 215554.png)

Product Line Revenue Breakdown

A clear view of product line contribution, where Classic Cars dominates the sales landscape.

![Product Line Revenue Breakdown](charts/Screenshot 2025-11-17 222629.png)

Geographic Revenue Contribution (Top Countries)

This visualization demonstrates the heavy reliance on the USA market for overall revenue.

![Geographic Revenue Contribution](charts/Screenshot 2025-11-17 224957.png)

Deal Size Distribution

A pie chart showing the high proportion of Medium and Small deal sizes, confirming a transaction-frequency-driven model.

![Deal Size Distribution](charts/Screenshot 2025-11-17 232101.png)

🚀 Setup and Usage

To replicate the analysis or explore the data further:

Data: Ensure sales_data_sample.csv is in the root directory.

Code: Open notebook.ipynb using a Jupyter environment (like VS Code, JupyterLab, or Google Colab).

Dependencies: The notebook requires standard Python libraries: pandas, numpy, and matplotlib.

pip install pandas numpy matplotlib


The notebook contains all the steps used to clean the data and generate the charts.