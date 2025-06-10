**✈️ Airlines Data Analysis using SQL and Python**

### 📊 Overview

This project analyzes airline operational data to uncover insights related to flight performance, delays, and trends. It combines SQL for data extraction and Python for cleaning, analysis, and visualization.

---

### 🧰 Tools & Technologies

* SQL :MySQL
* Python (pandas, matplotlib, seaborn)
* Jupyter Notebook




### 📝 Project Objectives

* Analyze flight delays by airline, airport, and time of day.
* Identify best-performing airlines based on punctuality.
* Understand trends in passenger traffic and flight volumes.
* Combine SQL querying with Python-based data analysis and visualization.


### 📁 Dataset

* Source: Kaggle dataset
* Format: CSV 
* Key fields: `flight_date`, `airline`, `origin`, `destination`, `departure_delay`, `arrival_delay`, `flight_number`, etc.



### ⚙️ How It Works

1. SQL Queries:
   Extract specific subsets of flight data directly from a database using SQL:

   * Top delayed flights
   * Most frequent flight routes
   * Delay distribution by airline

2. Python Analysis:

   * Load and clean SQL results with pandas
   * Generate visualizations (bar plots, box plots, time series)
   * Calculate key metrics (e.g., average delay per carrier)

3. Visualization Examples:

   * Delay trends over time
   * Airline-wise performance comparison
   * Origin vs. destination delay patterns



### 🚀 How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/json2801/airlines-data-analysis.git
   cd airlines-data-analysis
   ```
2. Create virtual environment and install requirements:

   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the notebook:

   ```bash
   jupyter notebook notebooks/Airlines_Analysis.ipynb
   ```


### 🔮 Future Improvements

* Use machine learning to predict flight delays
* Incorporate weather data for better delay modeling
* Build an interactive dashboard with Streamlit or Power BI


### 📬 Contact

* Author: Johnson
* LinkedIn: linkedin.com/in/johnson28012005
* Email: js28012005@gmail.com
