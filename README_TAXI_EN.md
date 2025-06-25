# 🚖 Chicago Taxi Trip Analysis + Hypothesis Testing
Urban trip exploration and statistical testing using Python

## 📌 Introduction
This project analyzes taxi trip data in Chicago during November 2017. It includes:

1. **Exploratory Data Analysis** (EDA) by company and destination neighborhood  
2. **Hypothesis Testing** regarding the effect of weather on trip duration from the Loop to O'Hare International Airport

## 🎯 Business Problem
Taxi companies and city transportation authorities aim to understand urban travel patterns, especially under changing weather conditions. If rain significantly affects trip durations, operational planning can be improved.

## 🔍 Project Goals
✔ Analyze trip frequency by company and drop-off location  
✔ Visualize distributions and top-performing areas  
✔ Identify neighborhoods with highest trip completions  
✔ Evaluate impact of rainy Saturdays on trip durations  
✔ Formulate and test relevant hypotheses  

## ❓ Key Questions
- Which companies had the most trips on November 15–16?  
- What are the top neighborhoods for trip completions?  
- Does rain on Saturdays affect average trip duration?

## 📊 Key Metrics
📌 EDA:
- Total trips per company  
- Average trips per neighborhood  
- Frequency visualizations  

📌 Hypothesis testing:
- Average trip duration with and without rain  
- T-statistic and p-value  
- Significance level (α) and conclusion  

## 🗂 Dataset Overview
📁 `/datasets/project_sql_result_01.csv`: trips per company (Nov 15–16)  
📁 `/datasets/project_sql_result_04.csv`: trips per neighborhood (November)  
📁 `/datasets/project_sql_result_07.csv`: duration from Loop to airport

Key columns:
- `company_name`, `trips_amount`, `dropoff_location_name`, `average_trips`  
- `start_ts`, `weather_conditions`, `duration_seconds`

## ⚙️ Analysis Process
📌 Tools used: Python, Pandas, Matplotlib, Seaborn, SciPy

### Step 1: Data Review & Cleaning
✔ Check and convert data types  
✔ Handle missing or unusual values  

### Step 2: EDA and Visualization
✔ Bar charts and comparative plots  
✔ Top 10 companies and neighborhoods  

### Step 3: Statistical Testing
✔ Hypothesis: Rain affects duration  
✔ Independent t-test application  

## 📁 Repository Structure
📂 data  
 └── project_sql_result_01.csv  
 └── project_sql_result_04.csv  
 └── project_sql_result_07.csv  

📂 notebooks  
 └── Proyecto_Sprint8_FINAL.ipynb  

📂 insights  
 └── summary.md  

## 📬 Contact
📧 Email: jessica.elizondo.t@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/jessica-elizondo-t
