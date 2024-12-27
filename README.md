# Sales Data Analysis - Notebook 1

## Project Overview
This project focuses on exploring and analyzing the sales data of a global superstore to understand trends, seasonalities, and patterns in sales. The insights generated from this analysis will serve as the foundation for building a predictive sales model in future notebooks.

## Notebook 1: Data Exploration and Preprocessing

### Objectives
The goal of this notebook is to clean and preprocess the dataset, conducting exploratory data analysis (EDA) to uncover sales trends and insights that will help prepare the data for further analysis and modeling.

### Steps
1. **Data Preprocessing**: 
   - Handle missing values, duplicate entries, and data type corrections.
   - Standardize postal code and date columns.
   - Convert sales figures to numeric values.
   
2. **Exploratory Data Analysis (EDA)**:
   - Analyze sales trends by different time periods (daily, weekly, monthly).
   - Identify seasonality patterns and key drivers of sales.
   - Investigate relationships between sales and product categories, customer segments, and shipping modes.

3. **Data Preparation**: 
   - Create new columns for the year, month, and day of the week based on the 'Order Date'.
   - Aggregate sales data to uncover insights on sales by product, region, and time.
   - Visualize trends and patterns in the sales data using bar plots, line charts, and heatmaps.

4. **Handling Missing Values**:
   - Impute missing postal codes for specific cities.
   - Replace missing or inconsistent values in the dataset.

### Key Insights from the Analysis
- **Seasonal Trends**: 
   - Sales peaks were observed in the months of November and December, likely driven by holiday seasons.
   - Significant differences in sales patterns across weekdays, with weekends showing higher sales.
   
- **Missing Data**: 
   - Missing postal codes were successfully imputed based on city and state information.

- **Sales Distribution**: 
   - A clear trend of increased sales in the last months of each year, suggesting a seasonal boost in demand.

### Tools and Libraries Used
- **Pandas**: For data manipulation and preprocessing.
- **Matplotlib & Seaborn**: For data visualization.
- **Statsmodels**: For statistical testing, including the Dickey-Fuller test for stationarity.

### Conclusion
The data preprocessing and exploratory analysis in this notebook have provided valuable insights into the sales trends and seasonal patterns in the dataset. This will serve as the foundation for future modeling, with the goal of forecasting sales for the next 7 days.

## Next Steps
In the next notebook, we will focus on building a predictive model using machine learning techniques to forecast future sales.

---

Feel free to explore the notebook and follow along with the analysis!
