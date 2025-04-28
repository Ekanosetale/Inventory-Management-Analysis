# Inventory-Management-Analysis

## About the Project

Efficient inventory management is crucial for balancing supply and demand while minimizing costs. This challenge explores key aspects such as stock levels, supplier performance, warehouse utilization, and reorder strategies. By analyzing the provided dataset, this project aims to identify trends, optimize restocking decisions, and assess cost efficiency. The goal is to uncover actionable insights that enhance inventory operations and decision-making. Statistical techniques, visualization tools, and storytelling approaches are leveraged to support findings. Ultimately, the challenge is to optimize inventory performance and improve supply chain efficiency. Let's dive 
in and explore the data!

## About the Dataset

*Column Name Description*

Product_ID Unique identifier for the product

Product_Name Name of the product

Category Category to which the product belongs

Unit_Price Price per unit of the product

Stock_Quantity Quantity of the product available in stock

Stock_Level Stock level category (e.g., Low, Medium, High)

Reorder_Point Minimum quantity at which reordering is triggered

Lead_Time_Days Number of days it takes to receive the product after ordering

Last_Restock_Date Date when the product was last restocked

Supplier_ID Unique identifier for the product supplier

Warehouse_Location Location of the warehouse storing the product

Min_Order_Quantity Minimum quantity required when placing a restock

Status Current status of the product (e.g., Active, Discontinued)

Entry_Date Date the product entry was added to the system

Country Country where the product is stored or distributed

Latitude Latitude coordinate of the warehouse location

Longitude Longitude coordinate of the warehouse location

## Statement of the Problem

From an industry-wide perspective, inefficiencies in inventory management contribute to supply chain imbalances, increased carrying costs, and lost sales opportunities. Whether in retail, manufacturing, or distribution, poor inventory visibility and inaccurate demand forecasting can result in stockouts, overstock situations, and elevated warehousing costs — all of which hinder operational agility and financial performance. Understanding the key factors contributing to inventory challenges such as data silos, demand variability, supplier reliability issues, inadequate tracking systems, storage limitations, and workforce constraints is crucial for implementing effective control mechanisms. By leveraging advanced analytics, inventory optimization algorithms, and real-time monitoring, organizations can enhance forecast accuracy, reduce excess stock, and ensure product availability. A strategic approach will not only build supply chain resilience but also improve service levels and drive cost-efficiency across operations.

## A Few Guiding Questions for Analysis

A. Stock Analysis & Inventory Levels

• Which product category has the highest total stock quantity?

• How many products have stock quantities below their reorder points?

• What minimum order quantity is needed to restock all products below their reorder point?

B. Supplier & Restocking Performance

• Which supplier has the highest average lead time for restocking?

• What is the average time since the last restock for out-of-stock products?

• Identify peak months for restocking activity and check for seasonal trends.

C. Cost & Pricing Analysis

• Identify the top 5 most expensive products and their categories.

• Which product category demonstrates the fastest turnover based on stock quantity and lead time?

D. Warehouse & Geographic Insights

• Which warehouse stores the highest number of products?

• Which country has the most stocked items? What are the top three countries by stock quantity across product categories?

1. Overall Inventory Health
   
 ![](ERD.png)

The company maintains a substantial inventory valued at $1.253 billion across over 5,000 products. Approximately 94% of products are fully in stock, reflecting healthy stock availability. However, 6% are either out of stock or close to depletion, posing a risk to continuity of sales and customer satisfaction. An average lead time of 15 days underlines the need for proactive replenishment management. The inventory value concentration among a few categories also highlights potential vulnerability if market demand shifts suddenly.
________________________________________
2. Stock Risk & Product Performance
   ![](ERD.png)
   
Categories like Books, Home & Garden, and Office Supplies face elevated stockout risks. Some products have zero inventory and value, suggesting obsolescence. Conversely, high-value products within Books and Office Supplies represent major investments, making their stock management critical to profitability. Inactive SKUs still occupying database and warehouse space generate hidden carrying costs including storage, administrative tracking, and system overhead.
________________________________________
3. Inventory Trends Over Time

   ![](ERD.png)
   
The inventory trend shows a sharp decline in 2024, followed by a major spike in 2025 and a slight correction in 2026. This volatility suggests reactionary planning, where restocking was delayed until inventory crisis points, leading to bulk, potentially costly replenishment later. Such trends increase risks of both stockouts and excess inventory, tying up working capital unnecessarily.

________________________________________
4. Supplier & Country Dependency
   ![](ERD.png)
   
The company relies heavily on suppliers from Italy, France, the United Kingdom, and Belgium. However, lead times vary significantly (from 1 to 29 days), which affects replenishment reliability. Concentrated supplier dependency also introduces supply chain vulnerability. Heavy concentration of suppliers and long lead times magnify vulnerability during events like port strikes, transportation bottlenecks, or geopolitical instability.
________________________________________
5. Warehouse & Stock Distribution
Stock is heavily clustered geographically. However, these clusters may not always align with actual customer demand regions, leading to longer fulfillment times and higher logistics costs. Warehouse locations closer to end-customers enable faster delivery times and reduce last-mile costs optimizing customer satisfaction and operational margins.
________________________________________
6. Operational Opportunities

Several opportunities emerge:

• Clean up obsolete and inactive products to free up working capital.

• Automate low-stock alerts and optimize reorder points to prevent stockouts.

• Diversify the supplier base and improve supplier performance tracking.

• Enhance warehouse distribution strategy to align inventory closer to customer demand.

## Recommendations

Based on the analysis, the following recommendations are proposed:

• Implement Demand Forecasting Models: Leverage predictive analytics to anticipate stock requirements more accurately.

• Optimize Reordering Processes: Automate reorder triggers based on real-time stock and demand levels.

• Supplier Risk Management: Develop alternative suppliers to reduce overreliance and mitigate lead time risks.

• Inventory Rationalization: Regularly audit products for obsolescence and phase out non-performing SKUs.

• Warehouse Rebalancing: Align inventory positioning with geographical demand to reduce shipping times and costs.

• Continuous Performance Monitoring: Introduce KPIs like Inventory Turnover Ratio, Stockout Rate, and Service Level Compliance.

## Conclusion

This inventory management analysis highlights that while the company maintains strong stock availability and significant inventory value, challenges remain around stockout risks, forecasting accuracy, supplier dependency, and warehouse optimization.By adopting data-driven forecasting, automation, supplier diversification, and geographic alignment strategies, the company can significantly enhance its inventory efficiency, reduce costs, and strengthen supply chain resilience. Through these improvements, inventory will not only support current operational goals but also drive sustainable growth, better service levels, and long-term profitability.



