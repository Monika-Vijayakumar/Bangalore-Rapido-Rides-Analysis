
# Bangalore Rapido Rides Service Analysis

**Domain:** Transportation  
**Tools Used:** Python, Power BI  

---

## Project Overview
This project analyzes Bangalore Rapido Rides data to uncover ride patterns, demand trends, and actionable insights.  
The aim is to help Rapido optimize ride services by understanding ride behaviors, fares, routes, and customer preferences.

---

## Objective
- Identify ride patterns, demand trends, and insights using **exploratory data analysis (EDA)**  
- Clean, transform, and preprocess the data for accurate analysis  
- Create meaningful visualizations to explain relationships between time, distance, fare, and other variables  
- Provide **actionable insights and recommendations** for optimizing ride services  

---

## Dataset Information
- **Source:** [Kaggle – Bangalore Rapido Ride Services Dataset](https://www.kaggle.com/datasets/vishaldeoprasad/bangalore-rapido-ride-services-dataset)  
- **Size:** 50,000 rows × 13 columns  
- **Key Features:**  
  - `ride_id` – Unique ride identifier  
  - `ride_date`, `ride_start_time`, `ride_end_time` – Ride timing information  
  - `pickup_location`, `drop_location` – Start and end points  
  - `distance_km` – Ride distance  
  - `fare_amount` – Fare charged  
  - `ride_time_min` – Duration in minutes  
  - `payment_method` – Cash, UPI, Wallet, etc.  
  - `ride_type` – Solo, Shared  
  - `customer_rating`, `driver_rating` – Ratings provided  

---

## Analysis Types
- **Descriptive Analysis:** Mean, median, mode, and distributions of key features  
- **Diagnostic Analysis:** Ride fare variations, customer satisfaction patterns  
- **Prescriptive Analysis:** Recommendations for price optimization, service timing, and route allocation  

---

## Key Steps
### Stage 1 – Problem Definition & Dataset Selection
- **Business Problem:** Rapido wants to improve its Bangalore rides by understanding peak times, popular routes, fare patterns, and unusual ride behaviors.  
- **Expected Outcome:** Identify peak hours, popular routes, average ride distances and fares, and generate insights to optimize operations.  

### Stage 2 – Data Cleaning & Transformation
- Removed duplicates and missing values  
- Converted date and time columns to appropriate formats  
- Calculated ride durations and distance-fare ratios  

### Stage 3 – Exploratory Data Analysis & Visualization
- Analyzed demand trends across different times and locations  
- Studied ride distances, fares, and types  
- Developed **interactive Power BI dashboards** integrating Python analysis  

### Stage 4 – Insights & Recommendations
- Identified busiest routes and peak hours  
- Suggested fare optimizations and ride allocation strategies  
- Highlighted areas for improving customer satisfaction  

---

## Outcome
The analysis provides a clear understanding of ride behaviors, fare patterns, and customer preferences.  
Rapido can use these insights to make **evidence-based decisions** for improving operations and service allocation.

---

## Files Included
-  [analysis.py](https://drive.google.com/file/d/1_0KcnfwwS3Mbdog4lBv2T6bYdHTJIPNB/view?usp=drive_link) – Python scripts for cleaning, transforming, and analyzing the dataset  
-  [dashboard.pbix](https://drive.google.com/file/d/1IBOFTIyvS6VIP3FJCcXvI7L-qkSzYa7y/view?usp=drive_link) – Power BI dashboard with visualizations and insights  
-  [dataset.csv](https://drive.google.com/file/d/17WEO_dE2rolohF7sQn6dcbxnZEH6kzL5/view?usp=drive_link) – Cleaned Rapido rides dataset  
-  [screenshots](https://drive.google.com/file/d/1_kOYCFOQ-dmiRM4lQzIr92H087G_Fjtw/view?usp=drive_link) - Dashboard exported to pdf from PowerBI

---

## Documentation
- [Project Word Document](https://docs.google.com/document/d/1RIsvrZZd3xA17SiuLV7DY5GrEaxSPznP/edit?usp=drive_link&ouid=115514694561278560173&rtpof=true&sd=true)

---

## Key Skills Demonstrated
- Data cleaning, transformation, and preprocessing  
- Exploratory and diagnostic analysis  
- Python (Pandas, NumPy) and Power BI  
- Data visualization and dashboard creation  
- Business insights generation and recommendations  

---

