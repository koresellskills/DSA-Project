# DSA-Project

# Amazon Product Data Analysis

[Project Overview](#Project-Overview)

[Objectives](#Objectives)

[Analysis Tools](#Analysis-Tools)

[Data Cleaning Process](#Data-Cleaning-Process)

[Outcome of Analysis](#Outcome-of-Analysis)

[Dashboard Preview](#Dashboard-Preview)

[Recommendations](#Recommendations)

### Project Overview

This project explores a dataset containing product listings from Amazon — including prices, ratings, review counts, categories, and discount percentages. The primary goal is to uncover insights that can inform sales strategy, pricing decisions, and customer behavior patterns using Microsoft Excel and Pivot Tables.

This analysis was completed as part of my Data Analysis coursework, focusing on non-code tools like Excel, but structured in a way that mimics industry-level data analytics workflows.

### Objectives

i. Clean and prepare raw product data for analysis

ii. Use Excel functions and Pivot Tables to answer 14 business-driven questions

iii. Create a basic dashboard for visual insight delivery

iv. Document insights and translate them into actionable recommendations


### Analysis Tools

Microsoft Excel [Download Here](https://www.microsoft.com)

### Data Cleaning Process

- Removed leading/trailing whitespace with

```
TRIM()
```

- Fixed inconsistent capitalization with

```
UPPER() and PROPER()
```

- Converted string percentages to decimal values

- Created helper columns:

```
Discount % = (Actual Price - Discounted Price) / Actual Price

Price Range Bucket using IF() and VLOOKUP() logic

```
- Verified data types (numeric, text, currency)

### Outcome Of Analysis

- Highest Avg Discount: Found in subcategories like

```
USB Cables and HDMI Adapters

```
- Most Reviewed Product: Appeared in the Electronics category with 17,000+ reviews

- Top Rating Correlation: Higher-rated products tended to have lower discounts, suggesting stronger value perception

- 50%+ Discount Products: Made up nearly 30% of total products

- Potential Revenue Leaders: Electronics category had the highest total review-weighted revenue

#### See the Analyzed Data Here 

[FIle of the Outcome for the Analysis](https://github.com/koresellskills/DSA-Project/blob/main/Amazon%20case%20study.xlsx)

### Dashboard Preview

![Preview](https://github.com/koresellskills/DSA-Project/blob/5da5433bf20da2aed51d6fdd4103c87b311ef70b/Screenshot%202025-07-05%20002542.png)

![02](https://github.com/koresellskills/DSA-Project/blob/c79b0e2b84d35bfe8a2bb41b29aa35c017a4c40e/Screenshot%202025-07-05%20002611.png)

![03](https://github.com/koresellskills/DSA-Project/blob/9c8eefa21b37ab76fc2f29b532d59487c90ab4ee/Screenshot%202025-07-05%20002713.png)

![04](https://github.com/koresellskills/DSA-Project/blob/c39002e6f405f3d3d2a8f0b99b419120737fbf43/Screenshot%202025-07-05%20002732.png)

![05](https://github.com/koresellskills/DSA-Project/blob/fb0bfe2414a430e6b4da1b71afdbbce2a258029a/Screenshot%202025-07-05%20002807.png)

![06](https://github.com/koresellskills/DSA-Project/blob/fcb1661210605a48484e00600d022563aa881877/Screenshot%202025-07-05%20002848.png)

### Recommendations

- Adjust discounting strategy: High-discount products often have lower ratings — quality control or price anchoring may be needed

- Leverage best-rated products: Feature them in advertising or bundles

- Explore review-driven pricing: Consider giving discounts to boost new product visibility

##### Author: Ri-EL

##### Role: Data Analyst in training (Unilorin BME)

##### Reach Me: ajeawesome01@gmail.com
