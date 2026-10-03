# BookCycle SQL Analysis

## Project Overview

This project analyzes BookCycle's books, customers, and transaction data using SQL.

The analysis demonstrates practical SQL skills and shows how relational data can be used to answer business questions related to inventory, transactions, customers, and sales.

## Business Objective

The goal is to analyze BookCycle's data to identify patterns in books, transactions, customers, and store-level sales that can support data-driven business decisions.

## Dataset

The BookCycle database contains three related tables:

### Books

Contains book inventory and pricing information, including:

- Book ID
- Title
- Author
- ISBN
- Genre
- Condition
- Purchase Price
- List Price
- Date Acquired
- Current Location
- Quantity

### Customers

Contains customer information, including:

- Customer ID
- Join Date
- Membership Status
- ZIP Code
- Birth Year
- Preferred Store

### Transactions

Contains sales transaction information, including:

- Transaction ID
- Date and Time
- Store Location
- Customer ID
- Book ID
- Sale Price
- Payment Method
- Online/Offline Status

## SQL Skills Demonstrated

- Filtering with `WHERE`
- Aggregation with `SUM()`, `AVG()`, and `COUNT()`
- Grouping with `GROUP BY`
- Filtering aggregated results with `HAVING`
- Sorting with `ORDER BY`
- Joining multiple tables with `JOIN`
- Subqueries
- Common Table Expressions (CTEs)
- Window functions
- `ROW_NUMBER()`
- `PARTITION BY`

## SQL Analysis

The project answers several business questions, including:

1. Which books belong to the Classic Fiction genre?
2. Which books have a list price above the overall average?
3. What is the total list price of books at each location?
4. Which transactions have a sale price above the average?
5. Which customers have made more than five purchases?
6. How can customer, transaction, and book data be combined?
7. What is the top-selling book in each genre at each store?
8. Which customers have the highest total spending among customers with more than five purchases?

## Key Insights

- University has the highest total list price of books at **634.45**, followed by Downtown at **293.72** and Suburban at **172.83**.
- The analysis identifies books in the Classic Fiction genre and books priced above the overall average list price.
- High-value transaction analysis identifies transactions with sale prices above the overall transaction average.
- Among customers with more than five purchases, **C1023** had the highest total spending at **155.87** from 13 purchases.
- **C1012** made the highest number of purchases in this group, with 14 purchases.
- Top-selling books vary by store and genre. For example, at the University store, **The Catcher in the Rye** was the top-selling Classic Fiction book with 5 sales.

## Business Recommendations

1. **Monitor inventory value by location**  
   Review inventory allocation across stores and identify opportunities to balance book availability and inventory value.

2. **Identify frequently purchasing customers**  
   Consider targeted customer engagement or loyalty initiatives for customers with higher purchase frequency.

3. **Use store and genre sales patterns**  
   Use top-selling books by store and genre to support inventory planning and stocking decisions.

4. **Monitor high-value transactions**  
   Track higher-value purchases to better understand customer purchasing behavior.

5. **Continue analyzing sales trends**  
   Combine transaction data with time-based analysis to identify seasonal and monthly purchasing patterns.

## Tools

- Python
- Jupyter Notebook
- SQLite
- SQL
- Pandas

## Conclusion

This project demonstrates how SQL can be used to transform relational BookCycle data into business insights.

The analysis applies filtering, aggregation, subqueries, JOINs, CTEs, and window functions to investigate books, transactions, customers, and store-level sales patterns.

These techniques can support data-driven decisions related to inventory management, customer engagement, and sales planning.
