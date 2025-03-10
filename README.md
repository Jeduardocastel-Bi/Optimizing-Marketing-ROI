# 6.-Showz-Marketing-Expenses-Optimization 📊

## 🚀 Project Description
After successfully completing the TripleTen course, you were offered an internship in the analytics department at Showz, a ticket sales company. Your main task is to optimize marketing expenses and analyze how customers interact with the service.

* The analysis addresses the following key questions:

1. How do customers use the service?
2. When do they start making purchases?
3. How much revenue does each customer generate for the company?
4. At what point do revenues cover customer acquisition costs?
5. This project combines data analysis and metric-driven decision-making to improve marketing efficiency and maximize profitability.

## 📊 Data Description
The analysis is based on three main tables:

visits: Records of website visits.
* uid: Unique user identifier.
* device: User's device.
* start_ts: Session start date and time (format: YYYY-MM-DD).
* end_ts: Session end date and time (format: YYYY-MM-DD).
* source_id: Identifier for the advertisement source.

orders: Data on completed orders.
* uid: Unique identifier for the user who made the order.
* buy_ts: Order date and time.

revenue: Revenue generated from the order.
* source_id: Identifier for the advertisement source.
* dt: Date of the expense.
* costs: Amount spent on marketing for a specific day.
  
## 🎯 Key Analysis Goals
1. Understand user behavior on the website and analyze their purchasing journey.
2. Calculate key performance metrics, such as:
* Customer Acquisition Cost (CAC).
* Customer Lifetime Value (CLV).
* Return on Investment (ROI) for marketing.
3. Identify the most profitable advertisement sources.
4. Determine the breakeven point between revenue and acquisition costs.


## 📊 Analysis Results  

### 🔍 User Behavior and Purchase Trends  
- **Analysis Period:** June 2017 - May 2018.  
- **Total visits:** 359,400.  
  - **73% on desktop**.  
  - **27% on touch devices**.  
- **Average visitors:**  
  - **907 per day**.  
  - **23,228 per month**.  
- A **spike in sessions was observed in November and December 2017**, driven by **Black Friday and Christmas**.  
- On average, **each user makes 5 purchases**.  

### 📈 Recommendations for the Marketing Team  

1️⃣ **Customer Retention Strategies**  
   - **Retention rate is high in the first months**, but users tend to become inactive over time.  
   - Implementing a **loyalty or points accumulation program** is recommended to encourage repeat purchases.  

2️⃣ **Strategies to Convert Visitors into Buyers**  
   - Some users **take days or even months to complete a purchase**.  
   - Sending **reminder emails** with offers or discounts could help close this gap and improve conversion rates.  

3️⃣ **Optimization of Acquisition Costs**  
   - **Acquisition source number (3) has significantly high costs** compared to the revenue it generates.  
   - It is recommended to **reduce spending on this source and increase investment in source number (1)**, as it delivers higher profitability.  

4️⃣ **Business Profitability and Sustainability**  
   - The company is **solid and profitable**, as the **Customer Lifetime Value (LTV) is 7 times higher than the Customer Acquisition Cost (CAC)**.  
   - This indicates that the investment in customer acquisition is well balanced with the long-term revenue generated.  

## 🛠️ Technologies Used
* Programming Languages: Python
* Data Analysis: Pandas, NumPy, SciPy
* Data Visualization: Matplotlib, Seaborn

## 📈 Skills Developed
* Data Cleaning and Preparation.
* Calculation of relevant business metrics.
* Effective data visualization and reporting.
* Data-driven decision-making to optimize marketing strategies.

## 🔗 Project Link:
