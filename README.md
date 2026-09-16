# small-food-business-sales-analysis
Data driven analysis of sales and product performance to uncover trends, identify top performing products, evaluate business KPI s and support better decision making

Dataset : Synthetic/Dummy
Period  : 24 Agustus 2023 - 24 Agustus 2026
Rows    : 10.000
Column  : 23
Category: Kue, Nasi, Sayur & Lauk


Dataset :

        Kolom         Data Type       Descriptiom
    Transaction Id      String    Unique Id Transaction
    Date                Date      Period Dates
    Day                 String    Transaction Day
    Month               String    Transaction Month
    Year                Integer   Transaction Year
    Product Id          String    Id Product
    Product Name        String    Name Product
    Category            String    Kue, Nasi, Sayur & Lauk
    Qty                 Integer   number of products produced
    Leftovers           Integer   umber of products remaining when the sale starts
    Clearance           Integer   The number of products from the remainder that were successfully sold on sale
    Distributor Price   Integer   Selling price from the merchant
    Selling Price       Integer   Normal Selling Price
    Clearance Price     Integer   Selling price after the sale
    Sold Normal Qty     Integer   Quantity sold before sale
    Sold Clearance      Integer   Amount sold through sale
    Total Sold          Integer   Total Sold (Normal + Clearance)
    Final_Balance       Integer   Products remaining after the sale
    Revenue             Integer   Revenue from regular sales + clearance sales
    Revenue Clearance   Integer   Income from clearance sales
    COGS                Integer   Payments for merchants
    Total Profit        Integer   Total Normal Revenue + Clearance
    Sell Through Rate   Float     Percentage of quantity successfully sold

Raw Sales Recoords ---> Data Transformation --> Business Metrics


Business Question : 
1. Which product sold the most over the three-year period?
2. Which product contributed the highest revenue?
3. Which category is the most dominant: Cakes, Vegetables & Side Dishes, or Rice?
4. Which product has the highest sell-through rate?
5. Which product most frequently has remaining stock?
6. Which products are most frequently included in sales promotions?\
7. What is the revenue contribution from sales promotions?
8. Do sales promotions help reduce excess inventory?
9. Which day had the highest sales?
10. How did sales trend over the three years?


Answer Question :

            Results                                                Insight
        1. Risol Mayo - 7435 Unit                  Becoming the product with the highest sales volume
        2. Kare Ayam  - Rp. 39.217.000             The highest revenue came from the Vegetables & Side                                                        Dishes category
        3. Kue - 126.104 -                         Unit Cakes account for the largest sales volume
        4. Nasi Kuning - 90,15% -                  Shows the highest rate of stock absorption
        5. Piscok - 1.233 unit leftovers -         Attention needs to be paid to production/stock planning.
        6. Pukis - 361 times                       Pukis is the product most frequently included in                                                           promotional sales campaigns, which may indicate the                                                        need for a specific strategy to accelerate sales.
        7. Rp27,675,500, approximately 3.04%       Sales through clearance events contribute additionally                                                     to revenue, although their share is relatively small                                                       compared to total turnover.
        8. Yes. A total of 10,923 units were sold  Clearance sales serve as a mechanism to help reduce                                                        excess inventory and convert a portion of the surplus                                                      stock into revenue.
        9. Saturday — Rp167,683,000 in revenue and 35,393 units sold  Saturday becoming day with the most performance revenue
        10. 2024: Rp301.15 million → 2025: Rp309.08 million. In 2026, it reached Rp193.75 million up to August 24.                                     Sales increased from 2024 to 2025. Data for 2026 covers an ongoing period, so it is not yet appropriate to compare it as full-year performance.
          

Dashboard :
<img width="917" height="453" alt="Dashboard" src="https://github.com/user-attachments/assets/aeac9765-a6f0-447a-bbb1-d721be49fa13" />



