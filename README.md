Project:Exploratory Data Analysis (EDA)

1.Initial Exploration:
Reviewed the dataset using basic queries (e.g., SELECT *) to understand the structure and key columns.
Used aggregate functions like MAX() and MIN() to identify extremes in total_laid_off and percentage_laid_off.

2.Identifying Key Insights:
Analyzed companies with a 100% layoff rate to identify those that went out of business.
Ordered results by funds_raised_millions to understand the financial scale of affected companies.

3.Trend Analysis:
Grouped data by location, industry, and company to calculate total layoffs using SUM() and GROUP BY.
Analyzed layoffs by year and identified patterns using YEAR(date).

4.Advanced Analysis with CTEs:
Used common table expressions (CTEs) to rank companies by layoffs per year with DENSE_RANK().
Calculated rolling totals of layoffs by month to visualize cumulative trends.

5.Outlier Detection:
Highlighted companies and locations with unusually high layoff numbers.
Identified industries and funding stages most impacted.
