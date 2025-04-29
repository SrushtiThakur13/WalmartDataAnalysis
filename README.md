# Walmart Sales Data Analysis and Dashboard

This project analyzes Walmart’s retail sales using SQL and Tableau.  
It explores sales trends, customer behavior, and product performance across time, regions, and branches.  
A Tableau dashboard was built to visualize KPIs and answer key business questions derived from SQL-based exploratory data analysis (EDA).

---

## 🧠 Key Questions Answered

- Which branch sells the most?
- What time of day sees the highest number of sales?
- Which product lines are most profitable?
- Which customer type brings in the most revenue?
- What days of the week receive the best average ratings?
- Does gender or payment method impact product preference?
- Which city pays the most in VAT?

---

## 📊 Features & Analysis Performed

- **Time-of-Day Feature Engineering** using SQL `CASE` statements
- Added fields for:
  - `time_of_day`: Morning, Afternoon, Evening
  - `day_of_week`: Day name from date
  - `month_name`: Month name from date
- **KPIs Analyzed**:
  - Total Sales
  - Average Rating
  - Most Selling Product Line
  - City and Customer Type with Highest Revenue
- **Insights Extracted Using SQL**:
  - Sales and VAT by customer type
  - Most common product by gender
  - Sales patterns across weekdays and branches
  - Top-performing time slots and days for rating
