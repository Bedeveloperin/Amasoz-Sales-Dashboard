# Amasoz-Sales-Dashboard

# Amazon Sales Dashboard

## Dashboard Link https://app.powerbi.com/links/D_KfW7wz03?ctid=9bbc0c7a-2e1d-458e-a996-4b1766a1c1a9&pbi_source=linkShare

https://app.powerbi.com/links/D_KfW7wz03?ctid=9bbc0c7a-2e1d-458e-a996-4b1766a1c1a9&pbi_source=linkShare&portalSessionId=17a84ca3-9f3a-459b-a6d5-c37fdc175747&fromEntryPoint=share
 



## Problem statement
The goal of this project is to develop a comprehensive sales dashboard for Amazon sellers. This dashboard will provide real-time insights into sales metrics,total porfit,total cost,region based, and other key performance indicators (KPIs). By leveraging this dashboard, sellers can enhance their operational efficiency, identify sales trends, and improve their overall profitability.

## Key Features

Sales Analytics

Daily, monthly , years sales trends: Visual representation of sales over different time periods.
Top-selling products: Identification of the best-performing products.
Sales by category: Breakdown of sales by product category.
Revenue metrics: Gross and net revenue calculations.

Customer Insights

Customer demographics: Information on customer age, gender, location, etc.

Order Management

Order tracking: Status updates on current orders.
Shipping performance: Analysis of shipping times and delays.
Order history: Detailed records of past orders.

Sales Channal: Analysis of sales offlin and online.
Financial Metrics

Profit margins: Calculation of profit margins for products.
Expenses: Tracking of various expenses such as shipping, advertising, and Amazon fees.


## Challenges
Data Integration: Integrating data from multiple sources including Amazon’s Seller Central, inventory management systems, and financial tools.
Real-time Data Processing: Ensuring the dashboard displays real-time or near-real-time data for timely decision-making.
User-Friendly Interface: Designing an intuitive and easy-to-navigate interface for users with varying levels of technical expertise.
Scalability: Ensuring the dashboard can handle a large volume of data and scale as the business grows.
Security and Privacy: Protecting sensitive business and customer information.
## Skills
Python , Jupyter notebook , Numpy , Pandas , PowerBI , Data Cleaning , Data Exploration , Data Transformation , Data Visualization , Key Performance Indicators (KPIs) , Reporting and Dashboarding

## Demo

import numpy as np
import pandas as pd
df = pd.read_csv("Amazon Sales data.csv")
df.head(10)
df.duplicated()

df.dtypes

df.info()
df['year sales'] = pd.DatetimeIndex(df['Order Date']).year
df['month sales'] = pd.DatetimeIndex(df['Order Date']).month
df

df.max()
df.min()
df.to_csv("Amazon Sales data.csv")



## 🔗 Links
[![portfolio](https://github.com/Bedeveloperin)](https://github.com/)
[![linkedin](https://www.linkedin.com/in/durgesh-ahirwar-410258237)](https://www.linkedin.com/)



## Screenshots

![Capturebi1](https://github.com/Bedeveloperin/Amasoz-Sales-Dashboard/assets/109737267/508a226c-96c8-4560-981b-5ddb9ba41543)
![Capturebi3](https://github.com/Bedeveloperin/Amasoz-Sales-Dashboard/assets/109737267/3dc4d73d-9b6e-4453-9d5d-27982e3d9f58)
![Capturebi](https://github.com/Bedeveloperin/Amasoz-Sales-Dashboard/assets/109737267/3872dc9b-7a38-4b8c-8eb1-703746fde9fb)
