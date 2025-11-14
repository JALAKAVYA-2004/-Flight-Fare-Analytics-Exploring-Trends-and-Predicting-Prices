# ✈️ Exploring Flight Pricing Patterns Using Python (EDA Project)

This project focuses on analyzing flight ticket prices to understand how fares vary across airlines, routes, number of stops, duration, and travel dates. All analysis is performed using **Python**, with a strong emphasis on **data cleaning, transformation, and exploratory data analysis (EDA)**.

---

## 📌 Project Objectives

- Analyze and understand flight fare variations  
- Compare prices across airlines  
- Identify the cheapest and costliest routes  
- Study how the number of stops affects pricing  
- Explore month-wise and seasonal price trends  
- Examine the relationship between flight duration and ticket price  
- Find weekend vs weekday price differences  

> **Note:** This is a *pure EDA project* — no machine learning is used.

---

## 📁 File Structure
Flight-Fare-Analytics/
│
├── data/
│ └── flight_data.csv
│
├── notebooks/
│ └── flight_fare_eda.ipynb
│
└── README.md

---

---

## 🗂️ Dataset Details

The dataset includes the following columns:

- Airline  
- Date_of_Journey  
- Source  
- Destination  
- Route  
- Dep_Time  
- Arrival_Time  
- Duration  
- Total_Stops  
- Additional_Info  
- Price  
https://colab.research.google.com/drive/1meP5po7yYPZBtjmLxDsS4WsAvlvw7h1l?usp=sharing

---

## 🧹 Data Cleaning & Preprocessing

Performed the following steps:

- Removed missing & duplicate rows  
- Extracted **Day, Month, Year** from journey date  
- Standardized **Duration** into hours and minutes  
- Cleaned `Total_Stops` values  
- Converted categorical features into structured formats  
- Created derived fields:  
  - `Journey_Day`  
  - `Journey_Month`  
  - `Duration_Hours`  
  - `Duration_Minutes`

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Airline-wise Price Analysis  
Compare fare distributions to differentiate cheap vs premium airlines.

### 🔹 Route Price Comparison  
Identify the most expensive and economical routes.

### 🔹 Effect of Stops on Price  
Analyze price differences between non-stop, one-stop, and multi-stop flights.

### 🔹 Duration vs Price Relationship  
Used scatter plots and correlation.

### 🔹 Monthly & Seasonal Trends  
Understand peak travel months and fare spikes.

### 🔹 Weekday vs Weekend Comparison  
Check whether fares change across the week.

---

## 📈 Visualizations Used

- Bar plots  
- Box plots  
- Line charts  
- Heatmaps  
- Scatter plots  
- Distribution plots  

Created using **Matplotlib & Seaborn**.

---

## 🧠 Key Insights



- Premium airlines show consistently higher average fares.  
- Non-stop flights are costliest; prices drop with more stops.  
- Some high-demand routes show frequent price fluctuations.  
- Festival/holiday months display visible fare spikes.  
- Duration has moderate correlation with pricing.  
- Weekend fares tend to be higher than weekday fares.

---

## 🛠 Technologies Used

- **Python**  
- **Pandas** – Data cleaning & manipulation  
- **NumPy** – Numerical operations  
- **Matplotlib** – Visualization  
- **Seaborn** – Statistical plotting  
- **Google Colab**

---
