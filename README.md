## Mobile Sales Data Analysis Dashboard

**Project Overview**

This project involves a comprehensive analysis of mobile sales data using Power BI. The goal was to transform raw sales data into an interactive dashboard that provides actionable

insights into sales performance, customer demographics, and brand trends across various regions in India and neighboring areas.

**Data Transformation (ETL Process)**

A significant part of this project involved cleaning and structuring the data within Power Query to ensure accurate time-intelligence reporting:

**Date Standardization:** Merged separate Day, Month, and Year columns into a single Date column using the custom formula =[day]&"-"&[month]&"-"&[year].

The data type was then converted to 'Date' to enable time-series analysis.

**Data Redundancy:** Removed the original split columns to optimize the data model.

**Consistency Fix:** Resolved inconsistent day naming (e.g., "Mon", "Monday","Sat","Saturday") by deleting the original column and extracting standardized Day Names for time saving

directly from the new Date column using Power BI's built-in date functions.

**Key Insights from the Dashboard**

**1. High-Level Metrics**

**Total Revenue:** ₹769M in total sales.

**Volume:** 19K units sold across 4K transactions.

**Customer Satisfaction:** Maintains a steady average rating of 3.69.

**2. Brand Performance**

Apple leads the market with ₹161.6M in sales, closely followed by Samsung at ₹160.0M.

Xiaomi holds the highest customer rating (3.72), suggesting high user satisfaction despite a lower total sales value compared to Apple.

The top three models by sales value are the iPhone SE (₹60M), OnePlus Nord (₹58M), and Galaxy Note 20 (₹56M).

**3. Sales Trends**

**Monthly Performance:** Sales peaked in July (₹70M) and October (₹65M), indicating seasonal surges.

**Daily Trends:** Saturday is the highest-performing day for sales (₹115M), with a gradual decline leading into the middle of the work week (Wednesday at ₹105M).

**4. Demographics & Payments**

**Target Audience:** The 30-year-old age bracket represents the highest transaction volume (500 transactions).

**Payment Preferences:** Payment methods are remarkably well-balanced, with UPI being the most preferred (26.36%), followed by Debit Cards, Credit Cards, and Cash.

**Dashboard Features**

**Dynamic Filtering:** Users can filter the entire report by Month or specific Date Ranges.

**Geographic Mapping:** Visual representation of sales distribution across major Indian cities (Bhopal, Lucknow, Hyderabad, etc.).

**Interactive Visuals:** Clickable charts that cross-filter data for deeper analysis into specific brands or payment methods.

## 📱 Mobile Sales Overview Dashboard

<img width="1047" height="672" alt="mobile sales dashboard" src="https://github.com/user-attachments/assets/84989740-bdc7-4e29-b493-834bf413a22d" />

**Author and Contact**

**Author:** MD Asim

**Email:** mdasim573@gmail.com

**LinkedIn:** https://www.linkedin.com/in/md-asim-56385017a

