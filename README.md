# 🏆 ICC T20 World Cup Super Team Dashboard

This Power BI dashboard focuses on creating the **best possible cricket team of 11 players** from all teams participating in the ICC T20 World Cup. The data was sourced from ESPN Sports and processed using Python, pandas, and Power BI. This `.readme` provides a detailed step-by-step breakdown of the project.

## 📑 Table of Contents
- [Data Source](#data-source)
- [Project Workflow](#project-workflow)
   1. [Web Scraping](#1-web-scraping)
   2. [Data Storage](#2-data-storage)
   3. [Data Cleaning & Manipulation](#3-data-cleaning--manipulation)
   4. [Data Conversion](#4-data-conversion)
   5. [Power BI Dashboard](#5-power-bi-dashboard)
- [Visualizations](#visualizations)

---

## 🌐 Data Source

All the data used in this project was web-scraped from [ESPN Sports](https://www.espncricinfo.com/) 🏏, specifically targeting the ICC T20 World Cup player and match statistics.

---

## 📊 Project Workflow

### 1️⃣ Web Scraping

- For web scraping, I used **BrightData** to extract comprehensive ICC T20 World Cup data from ESPN’s website. This process included gathering player statistics, match details, and team performance data.

### 2️⃣ Data Storage

- The scraped data was stored in a `.json` file format to ensure easy access and flexibility.

### 3️⃣ Data Cleaning & Manipulation

- The raw data was imported into Python 🐍 using the `pandas` library for cleaning and transformation:
  - Removed irrelevant or redundant columns.
  - Handled missing data by either imputing or removing records.
  - Standardized column names for consistency.
  - Reformatted dates and numerical values to ensure accurate data analysis.
  
- The data was transformed into a suitable format for analysis, focusing on player performance metrics to aid in selecting the best players for the ultimate T20 team.

### 4️⃣ Data Conversion

- After cleaning, the data was exported into `.csv` format, ensuring compatibility with Power BI for further analysis and visualization.

### 5️⃣ Power BI Dashboard

- I imported the cleaned `.csv` data into Power BI to create a dashboard that helps in identifying and selecting the **best team of 11 players** based on their T20 World Cup performance:
  - **Data Integration:** Imported and transformed the `.csv` file within Power BI.
  - **Data Relationships:** Managed relationships between player statistics, team data, and match results.
  - **Player Selection:** Utilized key performance indicators such as batting averages, bowling strike rates, and overall contribution to select the top 11 players from across all teams.
  - **KPIs & Metrics:** Created specific measures such as best all-rounders, top scorers, highest wicket-takers, etc.
  - **Filters & Slicers:** Added filters for teams, players, and matches to allow detailed exploration.

---

## 📈 Visualizations

The dashboard includes the following visualizations:
- 🏅 **Best XI Team:** A visual display of the top 11 players based on performance metrics across all teams in the ICC T20 World Cup.
- 📊 **Player Statistics:** Interactive tables showcasing batting, bowling, and all-rounder stats for every player.
- 🏏 **Team Comparisons:** Bar charts and visuals comparing team performances in various match categories.
- 🌍 **World Map:** A map illustrating the geographic spread of participating teams.
- 🕹️ **Interactive Filters:** Filters to allow users to explore player and team performance based on match data.

---

## 📂 Files in the Repository
- `icc_t20_data.json`: Raw data scraped from ESPN in JSON format.
- `icc_t20_cleaned.csv`: Cleaned and processed data ready for analysis.
- `ICC_T20_WorldCup_Super_Team.pbix`: Power BI dashboard file containing all visualizations and analysis.

---

## 🚀 Getting Started

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/icc-t20-worldcup-super-team-dashboard.git


