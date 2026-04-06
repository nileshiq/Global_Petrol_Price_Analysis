# ⛽ Pump Fiction: Global Petrol Price Analysis

A comprehensive data analysis and visualization project exploring petrol price disparities, regional trends, and market volatility across 101 countries.

## 📌 Project Overview
This project analyzes a global dataset of petrol prices (USD per Liter/Gallon) to identify economic patterns and regional outliers. By leveraging Python's data science ecosystem, the study provides insights into where fuel is most expensive, where it is subsidized, and how prices have shifted recently.

## 🚀 Features
- **Exploratory Data Analysis (EDA):** Statistical summary of global fuel costs.
- **Regional Benchmarking:** Comparative analysis of price levels across continents.
- **Volatility Tracking:** Identification of countries with the highest percentage price changes.
- **Categorical Mapping:** Segmentation of markets into "Very High" to "Very Low" price tiers.

## 🛠️ Technologies Used
- **Python 3.x**
- **Pandas**: Data manipulation and cleaning.
- **Matplotlib & Seaborn**: Advanced data visualization and statistical plotting.
- **Jupyter Notebook**: Interactive development environment.

## 📊 Key Visualizations
The analysis includes the following graphical insights:
1. **Global Price Distribution**: Histogram showing the density of fuel costs worldwide.
2. **Average Price by Region**: Ranked bar charts comparing regional affordability.
3. **Price Level Composition**: Pie chart showing the global market breakdown.
4. **Correlation Matrix**: Heatmap exploring the relationship between current and previous pricing.
5. **Volatility Analysis**: Box plots and strip plots identifying price swings and regional stability.

## 📈 Key Insights
- **The High End**: Hong Kong remains the most expensive market ($4.11/L), followed closely by Singapore and several European nations.
- **The Low End**: Major oil producers like Venezuela and Libya maintain the lowest prices due to heavy subsidies.
- **Regional Leaders**: Europe is the most expensive region on average ($1.95/L), while the Middle East is the most affordable ($0.69/L).
- **Market Trends**: Over 45% of the analyzed countries are currently experiencing rising fuel trends.

## 📂 Dataset
The dataset contains 101 entries with the following features:
- `Country` / `Region`
- `Price_Per_Liter_USD`
- `Price_Per_Gallon_USD`
- `Previous_Price_USD`
- `Price_Change_Percent`
- `Price_Trend` (Stable, Rising, Falling, etc.)
- `Price_Level` (Very High to Very Low)
