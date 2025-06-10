# 🌍 Air Quality Analysis – Exploratory Data Analysis (EDA) Project

## 📌 Description

This project explores air quality data from various global cities using **Exploratory Data Analysis (EDA)** techniques. It is designed as a hands-on practice exercise to develop data intuition, clean real-world datasets, explore relationships, and communicate findings effectively.

The dataset contains pollutant concentrations (e.g., CO, NO₂, SO₂, PM2.5) and corresponding AQI (Air Quality Index) values measured across time and locations. The focus is not on modeling but on understanding and extracting **valuable insights** from the data.

---

## 🎯 Objectives

- Practice real-world **EDA skills** with Python and pandas
- Understand trends in air pollution across **time**, **cities**, and **pollutants**
- Perform data cleaning, transformation, and feature engineering (e.g., extracting seasons, hours)
- Visualize patterns and relationships in the data
- Identify key factors influencing AQI and pollution peaks

---

## 🔍 Key Insights

This EDA addressed six core analytical questions, leading to the following insights:

1. **What are the pollution levels for each pollutant?**  
   - Calculated **max**, **min**, and **mean** values for pollutants like CO, NO₂, SO₂, and PM2.5.
   - PM2.5 and CO showed wide variability, suggesting more extreme pollution events.

2. **Which cities are the most polluted?**  
   - Cities like **Dubai** exhibited the highest average AQI values.
   - Grouped data by city and pollutant to rank cities based on pollution severity.

3. **Is there a seasonal pattern in pollution levels?**  
   - Grouped data by **season (Spring, Summer, Fall, Winter)**.
   - Found higher AQI during **summer months** in several cities — possibly due to heat, dust, and higher energy usage.

4. **Are pollution levels higher at certain hours of the day?**  
   - Analyzed AQI by **hour of day**.
   - Pollution levels tended to rise during **early mornings and evenings**, likely due to rush-hour traffic.

5. **Are some pollutants correlated?**  
   - Generated a **correlation matrix** to analyze relationships.
   - Moderate correlation found between certain pollutants like CO and NO₂, suggesting shared sources (e.g., vehicle emissions).

6. **What can we learn from outliers?**  
   - Used the **IQR method** to detect extreme AQI values.
   - Outliers often corresponded to short-term pollution events, such as industrial activities or weather conditions.

---

## 📊 Visualizations

To support the analysis, multiple visual tools were used:

- **Line plots**: AQI over hours, pollutants per city, or seasonal trends
- **Bar plots**: Average AQI across cities or seasons
- **Box plots**: Distribution and outlier detection by pollutant
- **Heatmaps**: Correlation between pollutants
- **Categorical grouping**: Hourly and seasonal grouping to highlight temporal patterns

---

## 🧠 Tech Stack

- **Python**
- **Pandas** and **NumPy** for data processing
- **Matplotlib** and **Seaborn** for visualization
- **Jupyter Notebook** / VSCode for development

---

## 📂 File Structure
