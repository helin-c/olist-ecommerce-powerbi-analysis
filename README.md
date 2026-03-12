# Olist Brazilian E-Commerce: Sales, Delivery & Sentiment Analysis

## 🌍 Project Overview
The objective was to conduct an exploratory data analysis on the Olist Store, the largest department store in Brazilian marketplaces. Olist connects small businesses from all over Brazil to channels without hassle and with a single contract. 

Using the Brazilian eCommerce public dataset of orders (from 2016 to 2018), this project leverages Power BI to generate business insights and provide recommendations for improvement regarding sales trends, logistics, and customer satisfaction.


## 🛠️ Tools & Techniques
* **Power BI Desktop:** Used for comprehensive data modeling, DAX measure creation, and interactive dashboard design.
* **Advanced Analytics:** Implemented predictive forecasting for future sales trends and utilized text-mining/sentiment analysis techniques to evaluate customer reviews.
* **Data Modeling:** Integrated multiple relational datasets (Orders, Reviews, Customers, Products, etc.) into a cohesive star/snowflake schema.

## 📊 Key Dashboards & Business Insights

### 1. Sales & Predictive Forecasting
**Objective:** Visualize overall revenue and forecast future growth.
* **Insight:** The platform generated **$16.01M in Total Revenue** across **99.44K Total Orders**. A predictive line chart was implemented to forecast future sales trajectories based on historical 2016-2018 data, allowing stakeholders to anticipate demand spikes.

![Sales and Forecasting Dashboard](https://github.com/helin-c/olist-ecommerce-powerbi-analysis/blob/main/sales%20prediction%20&%20forecasting.png?raw=true)

### 2. Delivery Performance & Logistics
**Objective:** Track shipping efficiency and geographic distribution.
* **Insight:** The **Average Delivery Time is 12.09 days**, with an **Average Freight Value of $22.82**. The geographic mapping illustrates the concentration of orders across Brazilian states, helping to identify regions where logistics routing can be optimized to reduce delivery times and freight costs.

![Delivery Performance Dashboard](https://github.com/helin-c/olist-ecommerce-powerbi-analysis/blob/main/delivery%20performance.png?raw=true)

### 3. Customer Sentiment Analysis
**Objective:** Evaluate customer satisfaction and identify pain points.
* **Insight:** The overall **Average Review Score is 4.09 out of 5**. By categorizing the review comments, the sentiment analysis reveals the ratio of Positive, Neutral, and Negative feedback. Monitoring these scores by product category allows Olist to identify underperforming sellers or products that negatively impact the customer experience.

![Customer Sentiment Dashboard](https://github.com/helin-c/olist-ecommerce-powerbi-analysis/blob/main/customer%20satisfaction%20&%20root%20cause.png?raw=true)

## 🚀 Strategic Recommendations
1. **Logistics Optimization:** Target regions with delivery times significantly above the 12.09-day average for localized warehousing or alternative carrier partnerships.
2. **Quality Control:** Investigate the product categories generating the highest volume of negative sentiment to improve overall marketplace quality.
3. **Inventory Planning:** Utilize the predictive sales forecast to help Olist's small business partners proactively manage their inventory ahead of projected demand surges.


