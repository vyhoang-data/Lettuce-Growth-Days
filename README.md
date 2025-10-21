**Lettuce Growth Analysis**

This project investigates how environmental factors **(temperature, humidity, TDS value, pH level)** and **growth days** influence lettuce growth. As a result, the insights extracted from the dataset aim to identify patterns and correlations to guide more effective cultivation solutions.

**-** **Created by:** Vy Hoang

**-** **Tools:** Excel

**- Dataset (Kaggle):** [Lettuce Dataset](https://www.kaggle.com/datasets/jurijsruko/lettuce/data?select=lettuce_dataset.csv)

**-** Worked with **22,190** data points

**- Tag:** Correlational analysis, data cleaning, visualization 

**Research Questions**

1. Can lettuce growth be predicted based on environmental conditions (temperature, humidity, TDS value and pH level)?
2. How does the insight help inform next season’s planning?

**Dataset Overview**

| Variable          | Description                          |
|-----------------|--------------------------------------|
| Plant_ID        | Unique identifier for each plant     |
| Date            | Observation timestamp                |
| Temperature (°C)| Recorded air temperature             |
| Humidity (%)    | Environmental humidity level         |
| TDS (ppm)       | Total dissolved solids (nutrient availability) |
| pH Level        | Environmental pH                     |
| Growth Days     | Time from planting to maturity       |

**Key Insights**

- Growth duration: 46 days (avg. ~23 days) from 03/08/2023 to 18/09/2023.

- In addition to the chart, I used the R² value (coefficient of determination) to measure how well the independent variable(s) explain the variation in the dependent variable.

             R² = 0 → the independent variable explains none of the variation.

             R² = 1 → the independent variable perfectly explains all the variation.

- Weak correlations between environmental factors and lettuce growth days (R² values):

               * Temperature: -0.0745

               * Humidity: -0.0145

               * TDS: -0.0206

               * pH: 0.003
  
**Question 1:** Can lettuce growth be predicted from environmental factors (temperature, humidity, TDS, pH)?

*=>Answer:* No. Correlational analysis shows very weak relationships between these factors and lettuce growth.

**Question 2:** How does the insight help inform next season’s planning?

*=>Answer:* The insights highlight which environmental factors have minimal impact on lettuce growth and prioritize other growth-influencing factors beyond just temperature, humidity, TDS, and pH.
  
**Recommendation**
- Monitor and optimize nutrient levels in the soil
- Consider other factors that might influence lettuce growth such as fertilizer or light conditions

**Data Visualization**

<img width="533" height="573" alt="Screenshot 2025-10-20 164300" src="https://github.com/user-attachments/assets/b3da7862-5220-4740-9d18-cce185923d57" />


**Contact**

**LinkedIn:** [Vy Hoang](https://www.linkedin.com/in/vyhoang-ussh/) | **Email:** vy.hoangphamuyen@gmail.com
