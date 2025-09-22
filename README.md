# Electronics Sales Analysis (End-to-End Data Analytics Project)

## Project Goal
Conduct a comprehensive analysis of electronics sales data, including the generation of a synthetic dataset, data cleaning, exploratory data analysis (EDA), and customer segmentation using RFM analysis. The main goal is to uncover key insights on sales, customer base, and product assortment to provide strategic recommendations for revenue growth and customer retention.

---

## Key Skills and Technologies
- Python, Pandas, NumPy  
- Synthetic data generation with Faker  
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- RFM analysis and customer segmentation  
- Data visualization (Matplotlib, Seaborn)  

---

## Data Description
The synthetic dataset includes retail and wholesale orders for 2023–2024. After cleaning, the dataset contains the following columns:  

| Column | Description |
|--------|------------|
| order_id | Unique order identifier |
| customer_id | Customer identifier |
| order_date | Order date |
| product_name | Product name |
| product_category | Product category (Laptop, Phone, Tablet, Accessory) |
| quantity | Quantity of items in the order |
| price | Unit price |
| payment_method | Payment method (Card, Cash, Online) |
| channel | Sales channel (Online/Offline) |
| country | Customer's country |
| revenue | Total order value (price × quantity) |

---

## Project Steps
1. **Synthetic Dataset Generation**  
   - Creating orders considering product categories, regions, sales channels, and payment methods  
   - Modeling accessories and product bundles  

2. **Data Cleaning and Preprocessing**  
   - Checking for missing values and duplicates  
   - Standardizing text data  
   - Correcting prices and calculating revenue  

3. **Exploratory Data Analysis (EDA)**  
   - Sales trends over time and by category  
   - Analysis by countries, channels, and payment methods  
   - Customer base analysis and AOV  

4. **RFM Customer Analysis**  
   - Segmenting customers by Recency, Frequency, and Monetary value  
   - Identifying high-value and low-value segments  
   - Drawing insights on retention and reactivation priorities for key customer segments

5. **Conclusions and Recommendations**  
   - Optimizing product assortment  
   - Marketing strategies for different customer segments  
   - Cross-sell strategies and retention of VIP and potential clients  

---

## Key Results
- Generated a synthetic dataset simulating realistic sales scenarios  
- Identified VIP and potential customers generating over 50% of revenue  
- Revealed seasonal and product sales peaks  
- Optimized marketing strategies and product assortment
