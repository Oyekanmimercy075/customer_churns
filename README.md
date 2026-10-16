# Customer Segmentation & Retention Analysis

## 1. Project Overview

This project focuses on analyzing customer behavior, purchasing patterns, customer lifetime value, and churn risk using Microsoft Power BI.

The dashboard transforms customer data into actionable insights to help businesses understand their customers, identify high-value customer segments, and develop effective customer retention strategies.

The analysis explores customer segmentation, spending patterns, average order value, lifetime value, and churn risk to support data-driven business decisions.

## 2. Business Problem

Businesses need to understand their customers to improve retention, increase revenue, and allocate marketing resources effectively.

However, without proper analysis, it can be difficult to identify valuable customer segments, understand purchasing behavior, and recognize customers who may be at risk of leaving.

This project addresses the following business questions:

- Which customer segments have the largest customer populations?
- Which customer segments contribute the most to customer spending?
- How does customer lifetime value vary across segments?
- What is the relationship between customer segments and churn risk?
- Which customers may require targeted retention strategies?
- How does average order value differ across customer segments?

## 3. Project Objectives

- Analyze customer distribution across different segments.
- Evaluate customer lifetime value and spending patterns.
- Compare average order value across customer segments.
- Examine churn risk across customer groups.
- Identify customer segments that may require retention efforts.
- Build an interactive Power BI dashboard.
- Support business decisions through data visualization and analysis.

## 4. Tools and Technologies

| Tool | Purpose |
|------|---------|
| Python | Data extraction and manipulation, where applicable |
| Beautiful Soup | Web scraping, where applicable |
| pandas | Data cleaning and manipulation |
| Microsoft Excel | Data cleaning, analysis, and summarization |
| MySQL | Querying and analyzing large datasets |
| Microsoft Power BI | Dashboard development and visualization |
| DAX | Calculations, measures, and key performance indicators |

## 5. Dashboard Features

### 5.1 Key Performance Indicators (KPIs)

The dashboard presents key customer metrics, including:

- Total customer spending
- Average total orders
- Total customer lifetime value
- Average order value
- Total number of customers

These metrics provide an overview of customer activity and value.

### 5.2 Customer Distribution by Segment

Visualizes the number of customers across different customer segments, including frequent buyers, high-value customers, low-frequency buyers, and moderate-value customers.

**Business Value:** Helps businesses understand the composition of their customer base and identify segments that may require different marketing approaches.

### 5.3 Average Customer Lifetime Value

Compares customer lifetime value across customer segments.

**Business Value:** Helps identify segments with higher customer value and informs customer relationship management and loyalty strategies.

### 5.4 Customer Distribution by Churn Risk

Examines customer distribution across low, medium, and high churn-risk categories.

**Business Value:** Helps businesses identify customer groups that may require additional engagement and retention efforts.

### 5.5 Customer Spend by Segment

Compares customer spending across different customer segments.

**Business Value:** Helps management understand how customer groups contribute to spending and where opportunities for revenue growth may exist.

### 5.6 Average Order Value by Segment

Analyzes average order value across customer segments.

**Business Value:** Helps businesses compare purchasing value across customer groups and develop targeted sales strategies.

### 5.7 Churn Risk Across Customer Segments

Combines customer segments and churn-risk categories to show how risk varies between groups.

**Business Value:** Helps businesses prioritize retention initiatives based on customer value and potential churn risk.

### 5.8 Interactive Filters

The dashboard includes filters for customer segments, churn risk, and other available customer attributes.

These filters allow users to explore specific customer groups and compare their performance.

## 6. Analytical Approach

The project follows a data analytics and business intelligence workflow:

1. **Data Extraction:** Extracted data from websites using Python and relevant libraries, where applicable.

2. **Data Cleaning:** Cleaned and prepared the dataset using Python and Excel.

3. **Data Exploration:** Performed Exploratory Data Analysis (EDA) to investigate patterns, relationships, and trends in the dataset.

4. **Data Summarization:** Used Excel PivotTables to summarize customer data and explore important metrics.

5. **SQL Analysis:** Imported the dataset into MySQL to perform queries and investigate customer behavior, spending patterns, and churn risk.

6. **Data Visualization:** Loaded the analysis results into Power BI to create interactive charts, KPIs, and dashboard filters.

7. **Business Insights:** Interpreted the results to identify potential customer retention opportunities and support data-driven decisions.

## 7. Business Applications

The insights from this dashboard can help businesses:

- Develop targeted customer retention strategies.
- Identify high-value customer segments.
- Improve customer engagement.
- Understand differences in customer purchasing behavior.
- Design targeted marketing campaigns.
- Support customer relationship management decisions.
- Allocate marketing resources based on customer value and risk.

## 8. Potential Business Recommendations

Based on the patterns identified in the dashboard, businesses could consider the following strategies:

- **High-Value Customers:** Develop loyalty programmes and personalized offers to maintain engagement.

- **High Churn-Risk Customers:** Investigate the reasons for potential disengagement and introduce appropriate retention campaigns.

- **Frequent Buyers:** Encourage repeat purchases through loyalty rewards and relevant product recommendations.

- **Low-Frequency Buyers:** Test targeted promotions and engagement campaigns to encourage repeat purchases.

- **Moderate-Value Customers:** Explore opportunities to increase purchase frequency and average order value.

These are potential actions to investigate. Specific recommendations should be validated against the underlying data and business context.

## 9. Skills Demonstrated

- Data extraction and manipulation
- Data cleaning and transformation
- Exploratory Data Analysis (EDA)
- SQL querying
- Customer segmentation analysis
- Customer lifetime value analysis
- Customer retention and churn-risk analysis
- KPI development
- Power BI dashboard development
- Data visualization
- Business intelligence
- Analytical thinking
- Data-driven decision-making

## 10. Project Structure

The repository can be organized as follows:

```text
Customer-Segmentation-Retention-Analysis/
│
├── README.md
├── Customer_Segmentation.pbix
├── data/
│   └── customer_dataset.xlsx
└── screenshots/
    └── customer_segmentation_dashboard.png
