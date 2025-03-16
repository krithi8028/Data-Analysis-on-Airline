
# Data Analysis on Airline Dataset ✈️📊

This repository contains an **exploratory data analysis (EDA)** of an **Airline Dataset**, focusing on key insights related to flight performance, pricing, stopages, and other aviation trends.

## Summary of Findings

### 🛫 1. Number of Flights with Respect to Stopages
- **481 flights** have **0 stopages** (direct flights).
- **5,742 flights** have **1 stopage**.
- **1,520 flights** have **2 stopages**.
- **45 flights** have **3 stopages**.
- **1 flight** has **4 stopages**.

### 💰 2. Most Expensive & Cheapest Flights
- **Jet Airways Business** is the **most expensive** flight.
- **Trujet** is the **cheapest** flight.

### 📈 3. Variation in Flight Price Based on Source
- The **maximum outliers** in flight prices are found in **Bangalore**.
- **Kolkata** has the **least** outliers in flight prices.

### 📅 4. Day & Month with Maximum Flight Stopages
- *(vizualization based on specific days and months.)*

### 📆 5. Month with Maximum Flights Taking Off
Total flights per month:
- **January**: 11,279,591 flights
- **March**: 18,647,220 flights
- **April**: 2,217,885 flights
- **May**: 19,414,875 flights
- **June**: **23,369,151 flights** (highest)
- **September**: 13,429,373 flights
- **December**: 8,719,011 flights

### 🌍 6. Availability of Flights by Source & Destination
- *(Visualization-based insights on flight connectivity.)*

## Notebook Contents

The notebook includes:

- **Data Cleaning & Preprocessing**: Handling missing values, feature engineering, and preparing the dataset.
- **Exploratory Data Analysis (EDA)**: Visualizing and interpreting trends in airline performance and pricing.
- **Key Insights & Recommendations**: Actionable findings based on the dataset.

## How to Use

1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "Data Analysis On Airline Dataset.ipynb"
   ```

## Dependencies

Ensure you have the following Python libraries installed:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

You can install them using:
```bash
pip install pandas numpy matplotlib seaborn
```

