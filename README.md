# Electric Vehicles Market Size Analysis

## Overview
I conducted an analysis of the electric vehicles (EV) market size using Python. This analysis is based on the EV population in the United States. The goal of this project is to understand EV adoption trends, geographical distribution, vehicle types, manufacturer popularity, electric range trends, and the estimated growth in market size.

## Dataset
The dataset contains records of registered electric vehicles in the United States, including details such as model year, manufacturer, model name, electric range, and geographical registration information.

## Analysis Areas
I explored the following key areas:

1. **EV Adoption Over Time**: Analyzed the growth of the EV population by model year.
2. **Geographical Distribution**: Examined where EVs are most commonly registered (e.g., by county or city).
3. **EV Types**: Studied the breakdown of Battery Electric Vehicles (BEV) and Plug-in Hybrid Electric Vehicles (PHEV).
4. **Make and Model Popularity**: Identified the most popular manufacturers and models among the registered EVs.
5. **Electric Range Analysis**: Investigated the progression of EV range over time.
6. **Estimated Market Growth**: Predicted future EV adoption using historical data and growth models.

---

## EV Adoption Over Time
To understand the growth of EVs, I visualized the number of EVs registered by model year.

![EV Adoption Over Time](https://github.com/Sourabh1710/Electric-Vehicle-Market-Size-Analysis/blob/main/images/EV%20Adoption%20Over%20Time.png)

The bar chart shows that EV adoption has been increasing over time, with a significant upward trend starting around 2016. The number of registered vehicles grew modestly until 2017, after which it rose rapidly. The highest peak is observed in 2023, indicating a strong growth in EV adoption.

---

## Geographical Distribution
I selected the top three counties based on EV registrations and analyzed the distribution of EVs within the cities of those counties.

![EV Distribution by City](https://github.com/Sourabh1710/Electric-Vehicle-Market-Size-Analysis/blob/main/images/Top%20Cities%20in%20Top%20Countries%20by%20EV%20Registrations.png)

Key findings:
- **Seattle (King County)** has the highest number of EV registrations.
- **Bellevue and Redmond (King County)** follow, though at a significantly lower number than Seattle.
- **Kirkland and Sammamish (Snohomish County)** show moderate EV registrations.
- **Tacoma and Tukwila (Pierce County)** have the lowest number of registrations among the selected cities.
- **King County** dominates EV registrations compared to the other counties.

This indicates that EV adoption is concentrated in certain areas, with King County leading.

---

## EV Types Breakdown
I analyzed the distribution of different EV types to understand consumer preferences.

![EV Type Distribution](https://github.com/Sourabh1710/Electric-Vehicle-Market-Size-Analysis/blob/main/images/Distribution%20of%20Electric%20Vehicle%20Types.png)

Findings:
- Battery Electric Vehicles (**BEVs**) are significantly more popular than Plug-in Hybrid Electric Vehicles (**PHEVs**).

---

## Popularity of Manufacturers and Models
### Most Popular Manufacturers

![Manufacturer Popularity](https://github.com/Sourabh1710/Electric-Vehicle-Market-Size-Analysis/blob/main/images/Top%2010%20Popular%20EV%20Makers.png)

Findings:
- **TESLA** has the highest number of registered vehicles by a substantial margin.
- **NISSAN** and **CHEVROLET** are the next most popular manufacturers, though far behind TESLA.
- **Other notable manufacturers** include FORD, BMW, KIA, TOYOTA, VOLKSWAGEN, JEEP, and HYUNDAI.

### Most Popular EV Models

![Model Popularity](https://github.com/Sourabh1710/Electric-Vehicle-Market-Size-Analysis/blob/main/images/Top%20Models%20in%20Top%203%20Makers%20by%20EV%20Registrations.png)

Key insights:
- **TESLA’s Model Y and Model 3** are the most registered EVs, with Model Y leading.
- **NISSAN’s LEAF** is the most registered non-TESLA vehicle.
- **TESLA’s Model S and Model X** have significant registrations.
- **CHEVROLET’s Bolt EV and Volt** are the most popular models from Chevrolet.
- **NISSAN’s Ariya and CHEVROLET’s Spark** have the least registrations among the listed models.

---

## Electric Range Analysis
### Distribution of Electric Ranges

![Electric Range Distribution](https://github.com/Sourabh1710/Electric-Vehicle-Market-Size-Analysis/blob/main/images/Distribution%20of%20Electric%20Vehicle%20Ranges.png)

Observations:
- Most EVs have a **low electric range**, with a peak just before 50 miles.
- The distribution is **skewed to the right**, meaning only a few vehicles have a high range.
- The **mean electric range** is approximately **58.84 miles**, which is relatively low compared to the highest available ranges.
- While high-range EVs exist, the **majority of vehicles have shorter ranges**.

### Electric Range Over Time

![Electric Range Over Time](https://github.com/Sourabh1710/Electric-Vehicle-Market-Size-Analysis/blob/main/images/Average%20Electric%20Range%20by%20Model%20Year.png)

Findings:
- **Upward trend** in electric range over time, indicating improvements in battery technology.
- **Peak in 2020**, with the highest average range.
- **Drop after 2020**, possibly due to the introduction of lower-range models or incomplete data.
- **Recovery in recent years**, but fluctuations remain.

### Electric Range by Manufacturer

![Electric Range by Manufacturer](https://github.com/Sourabh1710/Electric-Vehicle-Market-Size-Analysis/blob/main/images/Top%2010%20Models%20by%20Average%20Electric%20Range%20in%20Top%20Makers.png)

Findings:
- **TESLA Roadster has the highest average range** among all models.
- **TESLA’s vehicles dominate the top range category** (Model S, Model X, Model 3).
- **CHEVROLET Bolt EV** is a notable high-range model among Chevrolet’s lineup.
- **NISSAN’s LEAF and CHEVROLET’s Spark** have the shortest average ranges.

---

## Estimated Market Size Analysis
To estimate the market size of EVs in the United States, I calculated the number of EVs registered per year and projected future growth.

### EV Registrations by Year

Recent data shows:
- **2021**: 19,063 EVs registered
- **2022**: 27,708 EVs registered
- **2023**: 57,519 EVs registered
- **2024 (partial data)**: 7,072 EVs registered (until March)

Using the **Compound Annual Growth Rate (CAGR)**, I projected the future market size:

```
2024: 79,079 EVs
2025: 119,653 EVs
2026: 181,047 EVs
2027: 273,940 EVs
2028: 414,496 EVs
2029: 627,171 EVs
```

### Forecasted Market Growth

![Estimated Market Size](https://github.com/Sourabh1710/Electric-Vehicle-Market-Size-Analysis/blob/main/images/Current%20and%20Estimated%20EV%20Market.png)

Key takeaways:
- EV adoption remained **low and stable until 2010**, followed by a **sharp increase**.
- The forecast predicts **continued rapid growth** in the coming years.
- The **steep increase in future EV registrations** suggests a **strong consumer shift toward EVs**.
- This trend indicates **significant investment and business opportunities** in the EV industry.

---

## Summary
Market size analysis is essential to understanding industry growth, demand trends, and investment potential. Through this analysis, I found:
- **EV adoption is growing exponentially**, with major increases from 2016 onward.
- **King County leads in EV registrations**, indicating concentrated adoption in certain regions.
- **BEVs dominate over PHEVs**, showing a preference for fully electric solutions.
- **TESLA is the market leader**, followed by NISSAN and CHEVROLET.
- **Electric range is improving over time**, though most vehicles still have shorter ranges.
- **The EV market size is expected to expand significantly**, with a forecast showing rapid growth in registrations.

---

##Author

Sourabh Sonker <br>
Data Science Enth

