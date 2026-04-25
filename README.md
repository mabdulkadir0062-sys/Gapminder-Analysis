# Gapminder-Analysis

# Project Overview

. This project analyzes global development data using the Gapminder dataset to understand how economic indicators (GDP) relate to human
development outcomes (life expectancy) across continents

### 💼 Business / Analytical Problem

### Organizations such as governments, NGOs, and international institutions often need to answer:

. Does higher GDP lead to better living conditions?

. Which regions are improving over time?

. Where are development gaps still significant?

. How does population size impact these relationships?

## 🧹 Data Cleaning & Preparation
### The dataset was prepared for analysis using the following steps:

. Loaded dataset from Plotly’s built-in Gapminder dataset

. Converted data from Pandas → Polars for faster processing

. Verified structure and consistency of data
📈 Visualizations
🌍 Average Life Expectancy by Continent
Bar chart comparing continents
Includes:
Population size
Average GDP (hover data)
➡ Helps identify which regions have higher living standards
💰 GDP vs Life Expectancy
Scatter plot with:
GDP per capita (log scale)
Life expectancy
Bubble size = population
Trendline (OLS regression)
➡ Shows the relationship between wealth and health
📊 Life Expectancy Trends Over Time
Line chart showing changes across years
Segmented by continent
➡ Reveals development progress and convergence/divergence patterns
