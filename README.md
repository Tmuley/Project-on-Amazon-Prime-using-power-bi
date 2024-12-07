# Amazon Prime Video Analytics Dashboard

## Overview
This Power BI dashboard provides an in-depth analysis of Amazon Prime Video's content library. It showcases key performance indicators (KPIs) and interactive visualizations to help understand the platform's offerings, trends, and content distribution.

### **Dashboard Link**
https://github.com/Tmuley/Project-on-Amazon-Prime-using-power-bi/blob/main/Amazon%20prime%20Power%20BI.pbix

---

## Problem Statement
Amazon Prime Video, one of the leading OTT platforms, has a vast and diverse content library. However, gaining insights into the distribution of genres, ratings, and content trends can be challenging. This dashboard addresses the need to:
- Visualize the content distribution across genres, ratings, and release years.
- Analyze the balance between movies and TV shows.
- Highlight the geographical spread of content availability.

The dashboard provides actionable insights into improving content curation and regional focus.

---

## Key Insights
### **[1] Overview Metrics**
- **Total Titles:** 9,655  
- **Total Ratings:** 25  
- **Total Genres:** 519  
- **Total Directors:** 5,771  
- **Content Timeline:** From **1920** to **2021**


### **[2] Content Distribution**
- **Rating Analysis**:
  - Majority of content is rated for audiences aged **13+** with over 2.1K titles.
  - Content for audiences under **PG-13** is minimal.
- **Genre Trends**:
  - Top Genres: Drama (988 titles), Comedy (536 titles), and Drama Suspense (399 titles).
- **Movies vs. TV Shows**:
  - 80.82% of the content comprises TV shows, while 19.18% are movies.

### **[3] Geographical Spread**
The map visual reveals:
- Regions with the highest content availability.
- Gaps in specific regions that could benefit from increased content offerings.

### **[4] Release Year Analysis**
A trendline visual shows a significant increase in the number of titles released after 2000, indicating rapid growth in recent years.

---

## Steps Followed
### **Data Preparation**
1. Dataset loaded into Power BI Desktop.
2. Power Query Editor used for data cleaning:
   - Checked column quality, distribution, and profiling.
   - Addressed null values in rating and genre fields.

### **Dashboard Design**
1. Created KPIs for Total Titles, Ratings, Genres, and Directors.
2. Designed the following visuals:
   - Bar chart for **Ratings by Total Shows**.
   - Bar chart for **Genres by Total Shows**.
   - Map for **Total Shows by Country**.
   - Donut chart for **Movies vs. TV Shows**.
   - Line chart for **Total Shows by Release Year**.
3. Applied a dark theme for a visually engaging design.


![Screenshot 2024-12-08 004328](https://github.com/user-attachments/assets/bffb7833-d0c2-4ad8-80bd-1a60df6cede2)

### **Interactivity**
1. Added slicers for dynamic filtering by:
   - Country
   - Release Year
   - Type (Movie/TV Show)
2. Linked visuals for cross-filtering.

---

## Tools Used
- **Power BI Desktop**: For designing the dashboard.
- **Dataset**: Amazon Prime Video dataset with attributes like ratings, genres, release years, and availability by region.

---

## How to Use
1. **Clone the Repository**:
   ```bash
  https://github.com/Tmuley/Project-on-Amazon-Prime-using-power-bi


## Conclusion 
The Amazon Prime Video Analytics Dashboard is a powerful tool for understanding and visualizing content trends, genres, and geographical spread. It provides valuable insights for decision-makers to improve content strategies and regional focus.

---
