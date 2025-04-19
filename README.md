# 📊 Jenson USA – SQL Analysis Project (Milestone-2)

Hello! I'm Mandeep Kumar, and this is my submission for the **Milestone-2 Project** under WsCube Tech’s Data Analytics Program. In this project, I performed structured SQL analysis for **Jenson USA**, focusing on uncovering insights related to customer behavior, inventory, staff performance, and store operations.

---

## 🧠 Objective

To use SQL queries on the Jenson USA dataset to answer business-critical questions across multiple domains such as sales, inventory, and staffing. The goal was to extract meaningful insights that can help stakeholders make data-driven decisions.

---

## 📂 Dataset

The dataset provided contains information about:
- Stores
- Products
- Categories
- Orders
- Customers
- Staff

**Dataset Link**: [📎 Google Drive Folder](https://drive.google.com/drive/folders/1feFkClnYME7Be3kjmz-TD2PV1uVkXNAN)

---

## ✅ Key Insights & SQL Queries

Below are the business questions I tackled using SQL:

1. **Total Products Sold Per Store**
   - Query used `JOIN` and `GROUP BY` to count quantities per store.

2. **Cumulative Quantity Sold Per Product Over Time**
   - Used window functions like `SUM() OVER (PARTITION BY ... ORDER BY ...)`.

3. **Top-Selling Product by Category (Revenue-Based)**
   - Calculated `quantity * price` and used `ROW_NUMBER()` to find top products.

4. **Top Spending Customer**
   - Aggregated total spend by joining customer orders with product pricing.

5. **Most Expensive Product by Category**
   - Retrieved maximum price with category-wise filtering.

6. **Orders Placed by Each Customer per Store**
   - Joined orders with customers and grouped by both.

7. **Staff with No Sales**
   - Identified staff not associated with any successful order.

8. **Top 3 Products Sold (by Quantity)**
   - Sorted by quantity and limited results using `RANK()`.

9. **Median Price of All Products**
   - Used percentile logic (or window functions if supported) to find the median.

10. **Products Never Ordered**
    - Used `NOT EXISTS` to filter products missing from the orders table.

11. **Staff with Above-Average Sales**
    - Compared each staff’s sales count to the average using a subquery.

12. **Customers Who Ordered from Every Category**
    - Applied `GROUP BY` and `HAVING COUNT(DISTINCT category) = total_categories`.

---

## 📊 Presentation Deliverable

I compiled a PowerPoint presentation that includes:
- 📌 Each problem statement
- 💻 Corresponding SQL query
- 📷 Screenshots or description of results
- 🎯 Key insights and takeaways

---

## 🧾 Conclusion

This project sharpened my SQL skills and enhanced my ability to:
- Break down business questions into query logic
- Leverage `JOIN`, `GROUP BY`, `HAVING`, window functions, subqueries, and set logic
- Present analytical insights in a clear, structured manner

---

## 💡 About Me

I'm Mandeep Kumar – passionate about data, problem-solving, and storytelling through numbers. I'm currently advancing my skills in data analytics with WsCube Tech.

---

## 🚀 Submission Complete!

✅ **Milestone-2 Project Submitted**  
🗓️ Timeline: Completed within the deadline  
✨ Motto followed: **"Done is better than perfect!"**

---

## 📬 Contact

- 📧 Email: Mandeep0110.2@gmail.com
- 💼 LinkedIn: https://www.linkedin.com/in/mandeep0110/
