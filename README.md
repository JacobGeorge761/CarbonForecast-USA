# 🌎 CarbonForecast-USA

A data-driven model to simulate and forecast future U.S. CO₂ emissions under hypothetical economic and energy scenarios.

---

## 📌 Project Overview

**CarbonForecast-USA** uses historical emissions data and machine learning to predict total carbon dioxide emissions in the United States. The project explores relationships between population, GDP, and fossil fuel usage (coal, oil, gas), and builds a forecasting tool to estimate future emissions under a variety of scenarios.

Rather than simply summing known emissions data, this model enables **"what-if" analysis** — allowing us to explore the impact of changes in energy policy, economic growth, and population trends on future emissions.

---

## 🚀 Key Features

- 🔢 **Machine Learning Model**: Built using Random Forest Regression
- 🧮 **Data Normalization + Log Transformations** for skewed features
- 🔮 **Forecasting**: Predict future emissions from 2024–2028 based on hypothetical growth rates
- 🎛️ **Sensitivity Analysis**: Measure how CO₂ output changes when individual features like `gdp` or `coal_co2` are adjusted
- 📈 **Interactive Visuals**: Plotly + Matplotlib visualizations to explore historical and predicted trends

---

## 🧠 Why Not Just Sum the Fuel-Based Emissions?

While emissions from coal, oil, and gas can be summed to approximate total CO₂, this model is designed for **flexibility and forecasting**.

> 🔍 The goal is not to recreate past values — but to predict **future emissions** based on inputs we can estimate or simulate.

This enables:
- Policy simulation (e.g., reducing coal by 30% by 2030)
- Economic scenario planning (e.g., how GDP growth affects CO₂)
- Emissions projections even when granular fuel data is unavailable
