# 🏏 Cricket Team Selection - Data Analytics Project 🏏

## 📝 Objective

The objective of this project is to identify the **best cricket team of 11 players** in the world using a data-driven approach. Data on player performance was collected via web scraping from **ESPN Cricinfo** using **Bright Data**. The project involves data cleaning, transformation, modeling, and visualization to analyze player statistics and select the final team.

## 🚀 Project Overview

- **Data Collection**: Web scraping from **ESPN Cricinfo** using **Bright Data** to collect player performance data.
- **Data Cleaning & Transformation**: Performed using **Pandas (Python)** to clean and transform the data.
- **Data Modeling & Power Query**: Applied additional transformation using **Power Query** and modeled the data with **DAX** in **Power BI**.
- **Dashboard Creation**: Created interactive dashboards using **Power BI** to visualize player performance.
- **Team Selection**: Based on insights from the dashboard, selected the best **11 players** for the team.

## 📁 Project Structure

```
├── t20_csv_files/                    # Raw CSV files
├── t20_json_files/                   # Raw JSON files
├── web_scraping_codes/               # Web scraping code
├── t20_data_preprocessing.ipynb      # Data cleaning and transformation in Python
├── t20_cric_1_power_query.pq         # Data transformation in Power Query
├── DAX Measures and Calculated columns.xlsx   # DAX calculations
├── Codebasics Cricket Best 11.pbit   # Power BI dashboard file
├── Parameter scoping                 # Insights to find
├── t20_json_files.zip                # data files in json format
├── t20_csv_files.zip                 # Data as flat files
```

## 📊 Data Overview

The dataset contains information on player performance in T20 cricket matches, including:

- **Player Name**
- **Matches Played**
- **Runs Scored**
- **Wickets Taken**
- **Batting Average**
- **Bowling Average**
- **Strike Rate**
- **Economy Rate**


## 🔨 Workflow & Key Steps

### 1. **Data Collection**

- Used **Bright Data** to scrape detailed player statistics from **ESPN Cricinfo**.

### 2. **Data Cleaning & Transformation**

- Cleaned the data using **Pandas (Python)** to ensure consistency and remove missing/incorrect values.
- Transformed the dataset using **Power Query** for further optimization.

### 3. **Data Modeling & DAX**

- Built **DAX** measures and calculated columns in **Power BI** to facilitate performance analysis.

### 4. **Dashboard Creation**

- Developed a fully interactive **Power BI dashboard** to visualize player statistics.
- The dashboard includes filters for different player types (e.g., power hitters, finishers, bowlers) and graphs to analyze performance metrics.

### 5. **Team Selection**

- Based on insights from the dashboard, selected the **best 11 players** considering factors like batting average, strike rate, bowling economy, and overall performance.

## 🛠 Technologies & Tools

- **Web Scraping**: Bright Data
- **Data Cleaning**: Python (Pandas)
- **Data Transformation**: Power Query
- **Data Modeling**: DAX (Power BI)
- **Visualization**: Power BI

## 📊 Dashboard Insights

- The **Power BI dashboard** provides an intuitive way to analyze player performance across key metrics such as runs scored, wickets taken, strike rate, and bowling average.
- Using DAX measures, the dashboard allows dynamic filtering and comparison between players to make data-driven decisions on team selection.

## 🎯 Key Results

- Selected the final **best 11 players** for the team based on data-driven insights.
- Developed an easy-to-use, interactive dashboard that provides real-time insights on player performance, helping to identify the most valuable players.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## 📄 License

This project is licensed under the MIT License.
