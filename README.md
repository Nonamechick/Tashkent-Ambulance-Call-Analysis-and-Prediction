# Tashkent Ambulance Call Analysis and Prediction

An emergency ambulance call dataset analysis across Tashkent districts, predicting call volume trends using **Polynomial Regression (Degree 2)**[cite: 1].

---

## 📌 Project Overview

This project analyzes monthly emergency ambulance call records across 12 administrative districts in Tashkent city. The goal is to perform exploratory demographic analysis using **Pandas** and fit a non-linear machine learning model (**Polynomial Regression**) to forecast ambulance service demand and assist healthcare authorities in resource planning[cite: 1].

---

## 🤝 Collaborators

Check the **Collaborators** list on GitHub to see team member profiles and contributions.

---

## 🎯 Objectives & Expected Outcomes

### Objectives
1. **Demographic Breakdown:** Identify which age groups generate the highest volume of emergency medical calls.
2. **Geographic Distribution:** Identify high-demand districts in Tashkent city to optimize emergency dispatch.
3. **Trend Forecasting:** Fit a 2nd-degree Polynomial Regression model ($f(x) = ax^2 + bx + c$) to predict overall monthly call volumes[cite: 1].

### Expected Outcomes
- **Predictive Model:** A working quadratic regression equation forecasting overall call demand in Tashkent[cite: 1].
- **Visual Analytics:** Interactive charts showcasing call distribution across districts and age categories.
- **Resource Insights:** Data-driven findings to help health authorities allocate emergency personnel and vehicle fleets effectively.

---

## 📊 Dataset Information

- **Dataset Title:** Monthly Ambulance Calls by Age Category and District in Tashkent City
- **Source:** Open Data Portal of Uzbekistan (`data.gov.uz`)[cite: 1]
- **File Name:** `monthly_calls_by_agecategory_by_district.xlsx`
- **Size:** 510 rows × 17 columns
- **Features:**
  - `year`, `month`: Time variables
  - `age_category`: Demographics (`under12`, `under18`, `under25`, `over50`, `undefined`)
  - **12 District Columns:** `Uchtepa`, `Bektemir`, `Yunusobod`, `Mirzo Ulug'bek`, `Mirobod`, `Shayxontoxur`, `Olmazor`, `Sergeli`, `Yakkasaroy`, `Yashnobod`, `Chilonzor`, `Yangi Hayot`
  - `Total (Tashkent city)`: Total call volume in Tashkent city

---

## 📅 Project Plan

For details regarding project implementation steps, activities, and milestones, please refer to our project plan document:
👉 **[View Project Plan](https://github.com/Nonamechick/Tashkent-Ambulance-Call-Analysis-and-Prediction/blob/main/Tashkent%20Ambulance%20Call%20Analysis%20and%20Prediction.txt)**

---

## 📚 References

1. Open Data Portal of the Republic of Uzbekistan (`data.gov.uz`)[cite: 1].
2. NumPy and Pandas Documentation (`numpy.org`, `pandas.pydata.org`).
