# 🌍 Gapminder Data Analysis & Visualization

This project presents a comprehensive analysis and interactive visualization of the **Gapminder dataset**, exploring global trends in key socio-economic indicators over time and across regions.

---

## 📊 Features

- Cleaned and structured data using pandas
- Aggregated metrics by country, region, and year
- Interactive Altair charts:
  - Time-series visualizations per region
  - Scatter plots of GDP vs indicators with regression lines
  - Faceted charts by year and region
  - Full pairwise variable matrix using Altair repeat
- Segmentation into **High GDP** and **Low GDP** regions

---

## 🧰 Technologies Used

- Python 3
- Jupyter Notebook
- Pandas
- Altair
- VegaFusion

---

## 📁 Project Structure

<pre> ```text 📁 📁 gapminder-analysis/
├── gapminder.csv                # Raw Gapminder dataset
├── gapminder-analysis.ipynb     # Main notebook with all code and visuals
├── README.md                    # This file
└── requirements.txt             # Python dependencies (optional)
 </pre>


---

## 🗂️ Visualizations Overview

- 📈 **Trends Over Time**  
  Fertility, life expectancy, child mortality, and GDP across regions.

- 📉 **GDP vs Indicators**  
  Regression + scatter plots for GDP vs fertility, life expectancy, population, and child mortality.

- 🔁 **Variable Matrix**  
  All-vs-all scatter matrix showing relationships between variables.

- 🌍 **Region-based Comparisons**  
  Separate views for High GDP vs Low GDP regions using horizontal charts.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/gapminder-analysis.git
cd gapminder-analysis

### Install Dependencies:
pip install pandas altair vegafusion

### if using jupyter:
pip install notebook
jupyter notebook gapminder-analysis.ipynb

📚 Dataset Source
Data used from the Gapminder Foundation.
The CSV file contains cleaned, multi-year data on:

Fertility rate
Life expectancy
Population
GDP
Child mortality
Region & country information
