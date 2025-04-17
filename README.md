# E-commerce-Sales-and-Payment-Performance-Analysis


![Image](https://github.com/user-attachments/assets/ce4d3ef8-6ca4-4560-8d13-59257d8f2dd8)

# Introduction

**ElectroSphere Global** is a fast-growing multinational e-commerce company specializing in electronic gadgets and accessories, such as laptops, smartphones, smartwatches, tablets, and headphones. With operations across **North America, Europe, Asia, Africa, and Australia**, ElectroSphere provides customers with a seamless online shopping experience, offering flexible payment methods and worldwide shipping.

As the business scales, it faces increasing complexity in managing **sales performance, regional variations, and customer payment behaviors**. To sustain growth and remain competitive, the company seeks to make smarter, data-driven decisions.

# Problem Statement

Despite achieving $36.35 million in revenue and over 81,000 unit sales, ElectroSphere Global faces several pressing challenges. Sales performance is inconsistent across regions, indicating uneven market engagement. A high volume of failed and pending payment transactions is also affecting revenue realization and customer trust. Additionally, shifting demand across product categories complicates inventory and sales planning. Compounding these issues is the lack of real-time visibility into key sales and payment metrics, making it difficult for the company to respond quickly and make informed decisions. A data-driven approach is essential to address these challenges and drive operational efficiency.


### 1. Monitor Core Sales KPIs

   * Track total orders, units sold, and revenue.

   * Compare current sales performance with previous months to evaluate growth trends.

### 2. Evaluate Payment Method Performance

# Data Dictionary 

| Column Name         | Description                                                    | Data Type |
|---------------------|----------------------------------------------------------------|-----------|
| Order ID            | Unique identifier for each order                              | Integer   |
| Date                | Date when the order was placed                                 | Date      |
| Customer ID         | Unique identifier for each customer                           | String    |
| Product ID          | Unique identifier for each product                             | Integer   |
| Product Name        | Name of the product ordered                                    | Text      |
| Category            | Product category (e.g., Electronics, Accessories)              | Text      |
| Quantity            | Number of units ordered                                        | Integer   |
| Price per Unit      | Cost of a single unit of the product                           | Float     |
| Total Sale Amount   | Total revenue generated from the order (Quantity × Price/Unit) | Float     |
| Payment Method      | Mode of payment used by the customer                           | Text      |
| Payment Status      | Status of the payment (Pending, Completed, Failed)             | Text      |
| Country             | Country from which the order was placed                        | Text      |
| Continent           | Continent of the customer's country                            | Text      |




# Methodology

## Data Preparation and Visualisation

The dataset was sourced from Kaggle and imported into Power BI Desktop for analysis. A new calendar table was created using DAX functions to support time-based analysis and enable advanced time intelligence features.

This calendar table was then linked to the e-commerce dataset through the order date field to enhance the performance and accuracy of DAX formulas. Establishing this relationship ensured efficient data modeling, streamlined calculations, and more insightful visualizations.

## Preview of the e-commerce table

  ![Image](https://github.com/user-attachments/assets/6be83e24-afd0-4861-9499-a28ce344788a)

## Preview of the modeling

![Image](https://github.com/user-attachments/assets/9094a5fb-c6aa-4801-a219-666cdf108475)


## Key Performance Indicators (KPI's)

![Image](https://github.com/user-attachments/assets/27108eaf-ca59-42b7-a94c-daf2af133848)

# Dashboard Visual

![Image](https://github.com/user-attachments/assets/6f9cc52f-f059-454b-b0f2-ecfed8c6f5c5)

# Key Insights from E-commerce-Sales-and-Payment-Performance-Analysis:

## 1.  Overall Performance Metrics 
* **Total Orders**: 27.00K
* **Total Units Sold**: 81.29K
* **Total Sales**: $36.35M

## 2. Sales by Payment Method

### The sales distribution across different payment methods is relatively balanced:

![Image](https://github.com/user-attachments/assets/b5f15193-6ad2-4b7e-b35c-86a961ea72ea)

 * **PayPal**: $12.28M sales (33.78%)

 * **Credit Card**: $12.07M sales (33.20%)

 * **Bank Transfer**: $12.00M sales (33.02%)

## 3. Sales by Payment Status

### The sales distribution across different payment statuses:

![Image](https://github.com/user-attachments/assets/ca18f068-b5a9-4e38-9558-9acde4d4562b)

* **Completed**: $12.26M sales (33.74%)

* **Pending**: $12.19M sales (33.52%)

* **Failed**: $11.90M sales (32.74%)

## 4. Sales by Product Name

### The breakdown of sales across different product names is as follows: 

![Image](https://github.com/user-attachments/assets/46045800-8277-4462-91cc-54ab09b784e7)

* **Laptop**: $16M

* **Smartphone**: $11M

* **Tablet**: $5M

* **Smartwatch**: $3M

* **Headphones**: $1M

## 4. The summary of the Order, Units Sold, and Sales across Product Identity is as follows:


![Image](https://github.com/user-attachments/assets/4c5c8e8c-b007-46ee-b29a-b15d7146841c)

* **Product ID 3001**: 5,303 orders, 16,009 units sold, and sales amounting to $16,009,000.00

* **Product ID 3002**: 5,422 orders, 16,360 units sold, and sales totaling $818,000.00

* **Product ID 3003**: 5,369 orders, 16,197 units sold, and sales worth $11,337,900.00

* **Product ID 3004**: 5,454 orders, 16,432 units sold, and sales reaching $4,929,600.00

* **Product ID 3005**: 5,452 orders, 16,294 units sold, and sales of $3,258,800.00

## 5. Sales Trend Analysis Based on Current and Previous Month Comparison:

![Image](https://github.com/user-attachments/assets/31f15f99-d8d5-435a-92d4-e8bd1f5dd108)

* **January** recorded the **highest sales at $3,178,300.00**, which was **14.86%** higher than February, the **lowest performing month** with **$2,767,200.00** in sales.

* **A positive correlation** was observed between **Sales** and **Sales PM (Previous Month Sales)**, indicating that trends in past performance tend to align with current sales outcomes.

* **January** alone contributed **8.74%** of the total annual sales, highlighting it as a key revenue-driving month.

* **The largest divergence** between **Sales** and **Sales PM** occurred in **February**, where **Sales PM** exceeded **actual Sales** by **$411,100.00**, suggesting a significant drop in sales performance compared to the previous month.


## 6. Regional Sales 

* The map is designed to illustrate sales performance across countries within each continent. The size of each bubble represents the level of sales, with larger bubbles indicating higher sales performance. This visualization provides a quick geographical overview of regional market strength and highlights top-performing countries at a glance.


![Image](https://github.com/user-attachments/assets/bb5215aa-39ea-4734-9cc1-d0af620b0063)


# Recommendations:

Based on the findings from the E-commerce Sales and Payment Performance Analysis, several strategic recommendations can be made to improve ElectroSphere Global's operational efficiency, drive consistent sales growth, and enhance customer satisfaction. The following recommendations are tailored to address the key challenges and trends identified in the analysis:


## 1. Develop Strategic Campaigns to Stabilize Monthly Sales Fluctuations:

January recorded the highest sales, while February saw a sharp drop in performance. To ensure consistent monthly revenue, ElectroSphere should implement seasonal campaigns such as New Year promotions, limited-time discounts, and customer re-engagement emails—especially in historically underperforming months like February.

## 2. Resolve Payment Friction to Maximize Revenue Realization:

With over 65% of transactions either pending or failed, there's a significant revenue leakage. The company should optimize payment gateways, implement real-time error alerts, and provide users with clearer transaction feedback. This will improve conversion rates and reduce cart abandonment due to payment failures.

## 3.  Prioritize High-Yield Product Categories and Reevaluate Low Performers:

Products such as Laptops and Smartphones contribute the most to total sales. To boost profitability, ElectroSphere should increase stock levels for top-performing items, run upselling campaigns, and introduce bundle deals. Simultaneously, low-performing products like Headphones should be re-evaluated for redesign, promotion, or potential phase-out.

## 4.  Leverage Regional Sales Data for Targeted Expansion:

The regional map shows uneven sales distribution across continents. To enhance market penetration, the company should focus on high-performing countries by replicating successful strategies. Additionally, tailoring marketing and product offerings to fit the cultural and economic context of each region will strengthen local engagement and drive sales growth.

![Image](https://github.com/user-attachments/assets/a0645e25-7114-4c59-be4c-a3d7b283cd3b)

For any collaborative work or gigs, reach out to me at:

📧 Email: oladejoidris55@gmail.com
📱 +234 7025062857
