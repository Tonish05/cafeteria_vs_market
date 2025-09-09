Cafeteria vs Market Price Analysis
 Problem Statement

Students often feel that cafeteria food items are overpriced compared to local market prices.
This project analyzes and compares cafeteria prices with local market prices across 4 areas to identify items and categories with the highest markup.

 Objectives

Compare Cafeteria Price vs Market Price for common food items.

Calculate price difference & % difference to measure markup.

Identify overpriced items & categories across areas.

Visualize results using bar charts, boxplots, and comparison graphs.

Build an interactive dashboard (Streamlit) for easy exploration.

 Dataset

Data collected from 4 different areas, each saved in a separate CSV file.

Each file contains the following columns:

Column Name	Description
Item ID	Unique identifier for each food item
Food Item	Name of the food item
Category	Snacks, Breakfast, Beverages, Main Course
Cafeteria Price (₹)	Price in the college cafeteria
Market Price (₹)	Average local market price

 Additional columns were added during processing:

Price Difference (₹) = Cafeteria Price – Market Price

% Difference = (Price Difference ÷ Market Price) × 100

 Project Workflow

Data Collection → Prices of 20 common food items across 4 areas.

Data Cleaning & Preparation → Handled missing values, added calculated columns.

Exploration & Summarization → Avg prices, mean/median/std of % difference, min & max overpriced items.

Data Visualization → Created multiple charts for clear insights.

Dashboard Development → Built an interactive web app with Streamlit.

Insights & Interpretation → Identified common overpriced items, fair pricing trends, and area-wise differences.

 Data Visualizations

Bar Chart → Cafeteria vs Market price for each item.

% Difference Chart → Highlighting items with >30% markup.

Boxplot → Distribution of % differences by category (Snacks, Beverages, etc.).

Area Comparison Chart → Average % difference across all 4 areas.

🖥 Dashboard (Streamlit)

The interactive dashboard allows users to:

Select an area and view data.

Compare cafeteria vs market prices visually.

View summary statistics (mean, median, std of % difference).

Identify most & least overpriced items instantly.

Run the dashboard locally:

pip install -r requirements.txt
streamlit run dashboard/app.py

 Results & Insights

Snacks & Beverages are the most overpriced categories across all areas.

Sandwiches, fries, and burgers consistently show high markups.

Mineral water and some beverages are priced fairly across all areas.

Area comparisons show that:

One area had the highest markup (~35% avg difference).

Another area was closest to market rates (~15% avg difference).

Overpricing is likely due to convenience factor and overhead costs in cafeterias.
