# ETA Prediction Dataset for Tier-2/3 Cities (India)

## 📌 Overview
This dataset is synthetically generated to simulate real-world public transport conditions in tier-2 and tier-3 cities in India. It is designed for research purposes in Estimated Time of Arrival (ETA) prediction using machine learning techniques.

Due to the limited availability of structured and publicly accessible transport datasets for smaller cities in India, this dataset was created to reflect realistic transport dynamics, including vehicle movement, traffic variability, and temporal patterns.

---

## 📊 Dataset Components

### 1. GPS Data (`bus_gps_data.csv`)
Contains real-time simulated vehicle movement data.

**Columns:**
- `bus_id` – Unique identifier for each bus  
- `route_id` – Route assigned to the bus  
- `latitude` – Geographic coordinate  
- `longitude` – Geographic coordinate  
- `timestamp` – Time of observation  
- `speed` – Instantaneous vehicle speed  

---

### 2. Route Data (`route_data.csv`)
Defines route structure and bus stop locations.

**Columns:**
- `route_id` – Unique route identifier  
- `stop_name` – Name of bus stop  
- `latitude` – Stop location latitude  
- `longitude` – Stop location longitude  

---

### 3. Historical Data (`historical_data.csv`)
Represents time-based traffic patterns.

**Columns:**
- `route_id` – Route identifier  
- `time_slot` – Hour of the day (0–23)  
- `avg_speed` – Average speed for that time  
- `avg_delay_minutes` – Average delay  

---

## ⚙️ Dataset Generation Methodology

The dataset was generated using controlled simulation techniques:

- GPS trajectories were created using incremental coordinate variations to simulate movement  
- Speed values were randomized within realistic urban ranges (20–60 km/h)  
- Temporal patterns were introduced using timestamp progression  
- Historical traffic patterns were modeled using time-based averages  
- Random noise was added to simulate real-world uncertainty  

---

## 🎯 Purpose and Use Cases

This dataset is intended for:

- ETA prediction using machine learning models  
- Transport analytics and simulation  
- Feature engineering for mobility data  
- Research in intelligent transportation systems  

---

## ⚠️ Limitations

- The dataset is synthetic and may not capture all real-world complexities  
- External factors such as weather, accidents, and road conditions are not included  
- Designed for research and educational purposes only  

---

## 🔗 Reference Dataset Inspiration

The dataset structure is inspired by publicly available transport datasets from platforms such as Kaggle, including GPS trajectory and ETA prediction datasets.

---

## 👨‍💻 Authors

- Snahasish Dey  
- Sneha Majumder  
- Srijit Bhattacharya  

---

## 📄 License

This dataset is released for academic and research purposes. Attribution is appreciated.

---
