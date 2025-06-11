# 🌍 Air Quality Analysis – Exploratory Data Analysis (EDA) Project

## 📌 Description

This project explores air quality data from 6 important cities using **Exploratory Data Analysis (EDA)** techniques. It is designed as a hands-on practice exercise to develop data intuition, clean real-world datasets, explore relationships, and communicate findings effectively in Github.

The dataset contains pollutant concentrations (e.g., CO, NO₂, SO₂, PM2.5,CO2) and corresponding AQI (Air Quality Index) values measured across time and locations(Dubai, Cairo, Brazilia, London, New York, Sydney). The focus is not on modeling but on understanding and extracting **valuable insights** from the data.

---

## 🎯 Objectives

- Practice real-world **EDA skills** with Python, pandas, numpy, matplotlib and seaborn.
- Understand trends in air pollution across **time**, **cities**, and **pollutants**
- Perform data cleaning, transformation, and manipulation (e.g., extracting seasons, hours)
- Visualize patterns and relationships in the data

---

## 🔍 Key Insights

This EDA addressed six core analytical questions, leading to the following insights:

1. **What are the pollution levels for each pollutant?**  
- Calculated **max**, **min**, and **mean** values for pollutants like CO, NO₂, SO₂, and PM2.5.
- **Dubai** stands out as the most polluted city overall. It consistently records the highest average levels of key pollutants such as **carbon monoxide (CO)**, **particulate matter (PM2.5 and PM10)**, and has the highest average **AQI**, indicating generally poor air quality.

- **Cairo** shows exceptionally high levels of **sulfur dioxide (SO₂)**, both in average and maximum values. This suggests potential industrial or fossil fuel-related sources significantly affecting the air quality in the region.

- In contrast, **Sydney** and **Brasilia** exhibit the cleanest air among the cities analyzed. Both maintain **low levels of most pollutants** and have the **lowest average AQI values**, suggesting relatively healthy air conditions.
  

  <img width="1107" alt="Levels of pollutant" src="https://github.com/user-attachments/assets/9cdd51c9-62ed-4e5b-966e-5b510d79418d" />



These observations provide a clear understanding of how pollution levels vary significantly across cities and can guide further investigation into sources and solution strategies.

2. **Which cities are the most polluted?**  
   - Cities like **Dubai** exhibited the highest average AQI values.
   - Grouped data by city to rank cities based on pollution severity.

   <img width="503" alt="Most polluted City" src="https://github.com/user-attachments/assets/d71e010f-e856-4ab4-9b01-c2d0ea54df50" />


3. **Is there a seasonal pattern in pollution levels?**
   - Grouped data by **season (Spring, Summer, Fall, Winter)**.
   - Found higher AQI during **summer months** in several cities — possibly due to heat, dust, and higher energy usage.
   - **Summer** emerges as the season with the **highest overall AQI**, suggesting poorer air quality, particularly due to elevated levels of **ozone (O₃)** and **particulate matter (PM10)**. These pollutants tend to increase with heat and sunlight.

   - **Fall and Winter** exhibit **slightly better air quality** overall, with **lower AQI values**, although **CO and SO₂ levels** peak in **winter**, potentially due to heating-related emissions and stagnant air conditions.

   - **Spring** shows moderate AQI levels, but an increase in **PM2.5** and **O₃**, likely due to transitional weather patterns and blooming-related particulates.

This seasonal trend highlights the importance of considering **temporal variation** when analyzing air pollution and designing mitigation strategies.


4. **Are pollution levels higher at certain hours of the day?**  
   - Analyzed Pollutant by **hour of day**.
   - Pollution levels is generally simillar accross the day but it tends to slightly rise during **early mornings and evenings**, likely due to rush-hour traffic.

5. **Are some pollutants correlated?**  
   - Generated a **correlation matrix** to analyze relationships.
   - CO, O3, PM2.5, and PM10 are highly correlated, suggesting common sources or related atmospheric behavior.
   - PM2.5 and PM10 are almost perfectly correlated, which is expected.
   - SO2 generally shows weaker correlations with other pollutants, indicating potentially different sources or atmospheric processes.

6. **What can we learn from outliers?**  
   - Used the **IQR method** to detect extreme values and learn from it.
Outlier analysis uncovered **significant pollution spikes** that stand apart from regular trends:

   - Nearly **all extreme outliers** come from **Dubai**, indicating **severe pollution episodes**.

   - Among these, the **majority occurred during the summer season**, suggesting a seasonal intensification of pollution in Dubai, possibly due to high temperatures amplifying pollutant concentrations or increased emissions.

   - A **small cluster of 8 outliers** was also found in **Cairo**, all on **February 12, 2024, between 1 PM and 8 PM**. This isolated event may signal a **temporary environmental incident**.
---

## 📊 Visualizations

To support the analysis, multiple visual tools were used:

- **Bar plots**: Average AQI across cities or seasons

   <img width="564" alt="Screenshot 2025-06-10 at 8 29 28 PM" src="https://github.com/user-attachments/assets/72b75068-5d60-46b2-9538-ae99ff49b5ad" />

- **Line plots**: AQI and Pollutants over hours.
<img width="1124" alt="Screenshot 2025-06-10 at 5 53 27 PM" src="https://github.com/user-attachments/assets/d5d568f1-706b-4fe7-943f-21208b248016" />

- **Heatmaps**: Correlation between pollutants

  <img width="652" alt="Screenshot 2025-06-10 at 6 02 55 PM" src="https://github.com/user-attachments/assets/bd839662-8ef2-4a89-9e90-69ab18937425" />

- **Categorical grouping**: Hourly and seasonal grouping to highlight temporal patterns

  <img width="544" alt="Screenshot 2025-06-10 at 8 40 12 PM" src="https://github.com/user-attachments/assets/fa030d30-bfb2-4764-8cf6-1b39b0efcdd0" />

---

## 🧠 Tech Stack

- **Python**
- **Pandas** and **NumPy** for data processing
- **Matplotlib** and **Seaborn** for visualization
- **Jupyter Notebook** / VSCode for development

---
