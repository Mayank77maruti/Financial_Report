# Financial Report Power BI Project

## Overview

This repository contains a comprehensive Power BI project for financial analysis, leveraging the widely-used [Financial Sample dataset](https://learn.microsoft.com/en-us/power-bi/create-reports/sample-financial-download) provided by Microsoft. The project demonstrates best practices in data modeling, visualization, and interactive dashboard design to deliver actionable insights for business decision-makers.

[View the live report](https://app.powerbi.com/view?r=eyJrIjoiZTRjZDFlNjctNzdmMS00MWQ2LWI0NmEtZjk5YzQ1YmY2ZjQ4IiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9&embedImagePlaceholder=true)

![Financial-Report](https://github.com/imenbkr/Power-Bi-dashboards/assets/104791884/f8bd1228-46fc-4fc1-b8cd-86a1f9ca8955)

[Screencast from 2025-07-19 20-35-45.webm](https://github.com/user-attachments/assets/065a0d72-7224-4506-942e-38e145a2a1d7)



---

## Project Features

- **Interactive Dashboards:** Explore financial performance across multiple dimensions such as product, country, and segment.
- **Key Metrics:** Track Gross Revenue, Discounts, Net Revenue, Cost of Goods Sold (COGS), and Profit.
- **Time-based Analysis:** Analyze Month-to-Date (MTD) and Year-to-Date (YTD) trends with dynamic slicers.
- **Geographic Insights:** Visualize revenue and profit distribution by country/region.
- **Profitability Analysis:** Drill down into profit by product, segment, and discount band.
- **Advanced Visuals:** Includes maps, treemaps, radar charts, hierarchical trees, and funnel charts for deep analysis.
- **Optimized Performance:** Efficient data modeling and DAX calculations for fast, responsive reports.

---

## Dataset Description

The project uses the [Financial Sample.xlsx](./Financial%20Sample.xlsx) dataset, which contains anonymized sales and profit data across different market segments and countries. The dataset includes the following fields:

- **Country**: Sales region
- **Product**: Product name
- **Segment**: Market segment
- **Discount Band**: Discount category
- **Units Sold**: Quantity sold
- **Manufacturing Price**: Cost to produce
- **Sale Price**: Selling price
- **Gross Sales**: Total sales before discounts
- **Discounts**: Total discounts applied
- **Sales**: Net sales after discounts
- **COGS**: Cost of goods sold
- **Profit**: Net profit
- **Date**: Transaction date

---

## Key Dashboards & Analyses

### 1. **Overview Page**
- Operating profit over time (monthly trend)
- Gross revenue by product and country
- Revenue distribution map

### 2. **Profit Analysis**
- Profit breakdown by category (hierarchical tree)
- Total profit by product (radar chart)
- Profit by country (treemap)
- Profit by discount band (funnel chart)
- Profit by segment (stacked bar chart)

### 3. **Geographic Analysis**
- Revenue and profit mapped by country/region
- Identification of high-performing and underexplored markets

### 4. **Efficiency & Usability**
- Fast report loading
- MTD and YTD slicers for flexible time analysis
- Consistent visual design and navigation

---

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone <repo-url>
   ```
2. **Open the Power BI template:**
   - Launch Power BI Desktop
   - Open `Financial Report.pbit` to create a new report instance
   - Or open `Financial Sample.xlsx` directly in Power BI to explore the dataset
3. **Explore the dashboards:**
   - Use slicers and navigation buttons to interact with the report
   - Analyze trends, compare segments, and drill down into details

---

## Credits & Resources

- **Dataset:** [Microsoft Financial Sample](https://learn.microsoft.com/en-us/power-bi/create-reports/sample-financial-download)
- **Power BI Desktop:** [Download here](https://powerbi.microsoft.com/desktop/)
- **Inspiration:** Community Power BI financial dashboard projects

---

## License

This project is for educational and demonstration purposes. Please credit Microsoft for the sample dataset if you use it in your own work.
