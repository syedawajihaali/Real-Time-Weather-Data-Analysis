# 🌦️ Real Time Weather Data Analysis

Welcome to my Weather Data Analysis project! In this project, I explored weather data for various cities across Pakistan using Python, focusing on extracting meaningful insights through data scraping, cleaning, exploratory data analysis (EDA), and visualization.

---

## 🔍 Project Overview

This project involved analyzing real-time weather data from multiple cities in Pakistan. The entire process — from data extraction to visualization — was done using Python and key libraries such as `pandas`, `matplotlib`, and `seaborn`.

---

## 📊 Key Steps

### 🧲 Data Scraping
- Utilized the **OpenWeather API** to collect current weather data.
- Transformed the extracted JSON into a structured `DataFrame`.
- Saved the data for in-depth analysis.

### 🧹 Data Cleaning
- Standardized column names for consistency.
- Handled missing or null values.
- Ensured clean and reliable data for accurate results.

### 📈 Exploratory Data Analysis (EDA)
- Analyzed statistical properties and identified trends in the dataset.
- Visualized temperature, humidity, pressure, and other attributes across cities.

---

## 📌 Major Findings

- **Temperature Distribution:**  
  Most cities showed temperatures around **300°C** (Kelvin), with a right-skewed pattern indicating some outliers on the higher side.

- **Top 20 Cities Comparison:**  
  Cities with higher temperatures also tended to show **higher humidity** and **lower wind speeds**.

- **Correlation Matrix:**  
  - Strong positive correlation between **actual temperature** and **feels-like temperature**.  
  - Negative correlation between **temperature** and **pressure**.  
  - Weak relationship between **cloudiness** and **wind speed**.

- **Weather Conditions:**  
  - **Clear skies** dominated (71.1%).  
  - Conditions like **cloudiness**, **haze**, **light rain**, and **smoke** appeared less frequently.

- **Sunrise and Sunset Analysis:**  
  - **Southern cities** had earlier sunrises and sunsets.  
  - **Northern cities** experienced later sunrise and sunset timings.

---

## 📌 Conclusion

This project offered a detailed and insightful analysis of weather patterns across Pakistan. From API integration to custom visualizations, each step enhanced my understanding of how real-world data can be transformed into impactful stories. It also sharpened my skills in **data analysis**, **visualization**, and **problem-solving** using Python.

---

## 🛠️ Tools & Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- OpenWeather API
- Jupyter Notebook
