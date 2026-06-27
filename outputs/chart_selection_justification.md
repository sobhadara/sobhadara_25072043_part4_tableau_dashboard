# Part 4: Tableau Executive Dashboard & Data Storytelling


# Task 6: Chart Selection Justification

The dashboard was designed using visualization best practices to present business insights clearly and effectively. Each chart was selected based on the business question it answers.

## Chart Selection

- **Line Chart (Sales Trend View)**
  - Used to show how sales change over time.
  - A line chart makes monthly trends and seasonal patterns easy to identify.

- **Bar Chart (Regional Performance View)**
  - Used to compare sales across regions.
  - Bar charts allow quick comparison between categories.

- **Horizontal Bar Chart (Category Profitability View)**
  - Used to compare profit across categories and sub-categories.
  - Horizontal bars improve readability for longer category names.

- **Grouped Bar Chart (Customer Segment View)**
  - Used to compare Sales and Profit across customer segments.
  - This makes performance differences between segments easy to interpret.

- **Highlight Table (Return Analysis View)**
  - Used to identify customer segments and product categories with higher return rates.
  - Color intensity quickly highlights high-risk areas.

- **Scatter Plot (Discount vs Profit View)**
  - Used to study the relationship between discount percentage and profit.
  - This chart helps identify whether higher discounts are associated with lower profitability.

## Dashboard Design Principles

The dashboard follows several visualization best practices:

- Appropriate chart types were selected for each business question.
- KPI cards are placed at the top to provide a quick business summary.
- Visualizations are arranged below the KPIs to create a clear information hierarchy.
- Consistent colours are used throughout the dashboard for better readability.
- Charts include clear titles, labels, and data values where appropriate.
- Charts are sorted to improve comparison and highlight top performers.
- Axes and scales are kept consistent and are not manipulated, ensuring that comparisons are accurate and not misleading.
- Interactive filters for Region, Category, and Customer Segment allow users to explore the data dynamically.
- An action filter enables users to drill down into dashboard views by selecting a region.
- The dashboard layout minimizes clutter while presenting the most important business insights on a single page.

Overall, the selected visualizations help communicate business performance clearly while supporting interactive analysis and executive decision-making.


---



# Task 10: Explain Chart Selection

## Sales Trend View

### Question Answered
How are sales changing over time?

### Why This Chart?
A line chart was used because it clearly shows the monthly sales trend and makes it easy to identify increases and decreases.

### Fields Used
- Sales
- Month (Order Date)
- Sales labels
- Region and Customer Segment filters

### Design Principles Used
- Clear title
- Consistent color
- Data labels
- Simple and clean layout

### Mistake Avoided
A bar chart was not used because a line chart is better for showing trends over time.

---

## Regional Performance View

### Question Answered
Which region performs the best?

### Why This Chart?
A bar chart was used because it allows easy comparison of sales across different regions.

### Fields Used
- Region
- Sales
- Sales labels
- Region and Customer Segment filters

### Design Principles Used
- Sorted bars
- Clear labels
- Consistent colors
- Easy comparison

### Mistake Avoided
A pie chart was not used because bar charts make regional comparisons easier.

---

## Category Profitability View

### Question Answered
Which categories and sub-categories generate the highest profit?

### Why This Chart?
A horizontal bar chart was used because it displays many categories clearly and makes profit comparison easy.

### Fields Used
- Category
- Sub-Category
- Profit
- Profit labels
- Region and Customer Segment filters

### Design Principles Used
- Logical grouping
- Clear labels
- Simple layout
- Consistent colors

### Mistake Avoided
A treemap was not used because bar charts make it easier to compare profit values.

---

## Customer Segment View

### Question Answered
How do customer segments compare in terms of sales and profit?

### Why This Chart?
A grouped bar chart was used to compare Sales and Profit side by side for each customer segment.

### Fields Used
- Customer Segment
- Sales
- Profit
- Data labels
- Region, Category, and Customer Segment filters

### Design Principles Used
- Different colors for Sales and Profit
- Clear labels
- Easy comparison
- Clean formatting

### Mistake Avoided
Separate charts for Sales and Profit were not used because a grouped chart provides a better comparison.

---

## Return Analysis View

### Question Answered
Which customer segments and product categories have higher return rates?

### Why This Chart?
A highlight table was used because it quickly identifies high and low return rates using color intensity.

### Fields Used
- Customer Segment
- Category
- Return Rate
- Percentage labels
- Region, Category, and Customer Segment filters

### Design Principles Used
- Consistent color scale
- Percentage labels
- Clean layout
- Easy to identify patterns

### Mistake Avoided
A normal table was not used because the color highlights make the return patterns easier to understand.

---

## Dashboard Summary

Different chart types were selected based on the business questions they answer. Line charts were used for trends, bar charts for comparisons, grouped bars for comparing multiple measures, and a highlight table for identifying return patterns. KPI cards provide a quick summary of important business metrics. Interactive filters and action filters allow users to explore the dashboard from different perspectives while keeping the layout clean, consistent, and easy to use.


---