# Supplement Sales Data Analysis

## Project Overview
This project analyzes weekly sales data of various supplement products across multiple countries and platforms from January 2020 to August 2021. The analysis aims to identify sales trends, product performance, and platform effectiveness to inform business decisions.

## Dataset Information
**File:** `Supplement_Sales_Weekly_Expanded.csv`

**Columns:**
- `Date`: Date of sale (YYYY-MM-DD)
- `Product Name`: Name of the supplement product
- `Category`: Product category (Protein, Vitamin, Omega, etc.)
- `Units Sold`: Quantity of units sold
- `Price`: Price per unit
- `Revenue`: Total revenue (Units Sold × Price)
- `Discount`: Discount percentage applied
- `Units Returned`: Number of units returned
- `Location`: Country of sale (Canada, UK, USA)
- `Platform`: Sales platform (Amazon, Walmart, iHerb)

## Key Findings

### Revenue Insights
- Protein and Performance categories generate the highest median revenue
- Strong positive correlation between Units Sold and Revenue (0.72)
- Moderate positive correlation between Price and Revenue (0.45)

### Seasonal Trends
- Significant sales spikes in January (New Year resolutions)
- Summer months (June-August) show relatively lower sales
- Gradual sales increase from mid-2020 through 2021

### Platform Performance
- Amazon generates the highest total revenue
- Walmart and iHerb have similar sales volumes
- Amazon appears to be the dominant sales channel

### Pricing Patterns
- Most products priced between $10-$60
- Higher priced items (>$50) sell fewer units
- Negative correlation between Discount and Price (-0.31)

## Analysis Approach

### Data Exploration
- Used `.describe()`, `.info()`, and `.value_counts()` for initial exploration
- Identified data ranges, distributions, and unique values

### Visualizations
1. **Pairplot**: Relationships between numerical variables
2. **Heatmap**: Correlation matrix of numerical features
3. **Boxplots**: Revenue distribution by category
4. **Time Series**: Monthly revenue trends
5. **Bar Charts**: Platform performance comparison
6. **Scatterplots**: Price vs. Units Sold relationships

## How to Run the Analysis

### Requirements
- Python 3.6+
- Required packages:
  - pandas
  - seaborn
  - matplotlib
  - jupyter (optional for notebook)

### Installation
```bash
pip install pandas seaborn matplotlib jupyter
