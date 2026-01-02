# Bike-Sales-Data-Analysis
This project showcases an interactive Excel dashboard built to analyze customer behavior and purchasing patterns in a bike sales dataset. The goal was to transform raw data into actionable insights using pivot tables, slicers, and data visualization—similar to real-world business reporting.

# Data Cleaning & Preprocessing
## Duplicate Removal
- Identified and removed duplicate records using Excel Data Tools.
- 26 duplicate rows were removed.
- Final dataset contains 1,000 unique records, ensuring accurate analysis.

# Standardizing Categorical Variables
## Marital Status
M → Married
S → Single
## Gender
M → Male
F → Female

Standardizing these values improves readability and consistency across reports and visualizations.

# Feature Engineering
## Age Group Creation
I created a new column called “Age Group” to simplify analysis and improve the clarity of visualizations. While the original dataset contains individual ages ranging from 25 to 89, analyzing age as a continuous variable made it harder to identify meaningful patterns across customer segments.

To address this, I grouped ages into clearly defined demographic categories that are commonly used in business and market analysis. These groupings make trends easier to interpret and communicate to non-technical stakeholders.

I defined the age bins as follows:
0–12 → Children (future-use) 
13–19 → Teens (future-use) 
20–29 → Young Adults 30–39 → Adults 
40–59 → Middle-Aged Adults 
60+ → Seniors / Older Adults

Although the current dataset starts at age 25, I intentionally included younger age groups to make the structure scalable and future-ready in case new data is added later. These groupings follow commonly accepted demographic standards, making them easy to explain to both technical and non-technical stakeholders.

This transformation significantly improved the clarity of my pivot tables and dashboard visuals, allowing me to clearly compare bike purchasing behavior across different life stages and communicate insights more effectively in reports and presentations.

# Project Insight
1. Middle-aged adults and adults purchase more bikes compared to young adults and seniors.
2. Customers who purchased bikes earn more on average than those who did not, with males earning slightly more than females overall.
3. North America has the most customers overall but also more non-buyers, while the Pacific region has more buyers than non-buyers, and Europe is nearly evenly split.
4. Customers with a bachelor’s degree tend to commute more than 10 miles.
5. Customers in Management and Professional occupations purchase more bikes than those in Clerical, Manual, and Skilled Manual roles.

# Project Conclusion

To improve bike sales, marketing and sales efforts should primarily focus on middle-aged adults and adults (ages 30–59) working in Professional and Management roles, as this group shows the highest purchase rates and higher average income levels. Special attention should be given to customers with longer commute distances (10+ miles), as they are more likely to purchase bikes.

From a regional perspective, while North America has the largest customer base, it also has a higher proportion of non-buyers, indicating an opportunity to improve conversion through targeted promotions. In contrast, the Pacific region demonstrates stronger buyer conversion, making it a high-performing market that could benefit from expanded product offerings and loyalty programs.

Overall, a targeted strategy combining income-based segmentation, occupation-focused messaging, and region-specific marketing campaigns would be most effective in increasing bike sales and maximizing customer conversion.

# Tools and Skills Used
- Microsoft Excel
- Data Cleaning and Transformation
- Pivot Tables and Pivot Charts
- Interactive Dashboards
- Business and Customer Analytics
- Data Storytelling

