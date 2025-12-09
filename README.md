# Google-Data-Analytics-Cyclistic-Case-Study

## Cyclistic Rider Conversion Strategy

This project is the capstone case study for the **Google Data Analytics Professional Certificate**. It analyzes public bike-share trip data to understand user behavior and proposes strategies to convert casual riders into annual members.

---

## 1. Business Task (Ask)

**Problem:**  
Understand how annual members and casual riders use Cyclistic bikes differently.

**Goal:**  
Design a marketing strategy based on data insights to increase annual memberships.

**Stakeholders:**  
- Lily Moreno (Director of Marketing)  
- Cyclistic Marketing Analytics Team  
- Cyclistic Executive Team  

---

## 2. Data Preparation & Cleaning (Prepare & Process)

**Data Source:**  
13 monthly files of public trip records from Divvy / City of Chicago.  
**Time Frame:** October 2024 - October 2025.  

**Data Integrity:**  
Verified using the ROCCC framework (Reliable, Original, Comprehensive, Current, Cited).

**Cleaning & Transformation Steps:**  
- Merged all 13 files, resulting in 5,539,521 rows.  
- Converted `started_at` and `ended_at` columns to datetime format.  
- Removed 141,967 invalid trips (less than 1 minute or longer than 24 hours), leaving 5,397,554 trips.  
- Added new columns: ride duration, day of week, month, and hour.  

---

## 3. Key Findings & Insights (Analyze & Share)

Annual members primarily ride on weekdays for commuting, while casual riders use bikes mostly on weekends and in summer for leisure.  

| Metric | Annual Members | Casual Riders | Insight |
|--------|----------------|---------------|--------|
| Total Usage | 64.5% | 35.5% | Members dominate overall usage |
| Average Ride Duration | 12.0 min | 20.2 min | Casual riders take longer trips |
| Peak Days | Tue & Thu | Sat & Sun | Members commute; casuals ride for leisure |
| Peak Season | Steady | July & August | Weather drives casual usage |
| Bike Type | 61.08% Electric | 62.6% Electric | Both groups prefer electric bikes |


---

## 4. Recommendations (Act)

### 1. Weekend Membership Discount  
**Strategy:** Offer a discount on annual memberships for casual riders who ride on weekends.  

### 2. Summer Free Ride   
**Strategy:** Offer free rides during July and August to casual riders who purchase an annual membership.  

### 3. E-Bike + Peak Hours Discount For The First Month
**Strategy:** Provide a discount on the first month of e-bike usage upon membership purchase.  

---

## Repository Structure & Deliverables

- **Code:** `Cyclistic_Analysis.ipynb` ([full data processing and analysis](https://github.com/3BoOoD97/Google-Data-Analytics-Cyclistic-Case-Study/blob/main/Code/notebooks/Cyclistic_Analysis.ipynb))  
- **Report:** `Cyclistic_Bike-Share_Case_Study.pdf` ([view full report](https://github.com/3BoOoD97/Google-Data-Analytics-Cyclistic-Case-Study/blob/main/Report/Cyclistic%20Bike-Share%20Case%20Study.pdf))  
- **Tools:** Python (Pandas, Matplotlib), Jupyter Notebook
