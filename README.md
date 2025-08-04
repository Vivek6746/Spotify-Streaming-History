# 🎵 Spotify Listening History Dashboard

## 🛠️ Tools Used

- **Python**
- **Jupyter Notebook**
- **Pandas** – Data manipulation
- **Matplotlib & Seaborn** – Static visualizations
- **Plotly** – Interactive charts
- **Spotify History Dataset (CSV)**

---

## 📄 Summary

This project visualizes personal Spotify listening history to analyze music habits over time. The dashboard highlights top artists, songs, time-of-day preferences, and more. It uses Python libraries to transform raw data into engaging charts and insights.

---

## 🔗 Data Source

- **Dataset**: Personal export from Spotify account
- Files used:
  - `spotify_history.csv`
  - `spotify_data_dictionary.csv` (for reference)

---

## ✅ Steps Taken

1. **Data Importing**
   - Loaded CSVs using `pandas`, handled encoding issues and datetime conversion.

2. **Data Cleaning**
   - Checked for nulls, renamed columns for clarity, standardized artist and track names.

3. **Feature Engineering**
   - Extracted date, time, hour, and weekday from timestamps.
   - Added duration in minutes and grouped data for trend analysis.

4. **Data Analysis**
   - Identified most played artists, tracks, days, and hours.
   - Evaluated listening trends over time.
   - Explored seasonal behavior and daily patterns.

5. **Data Visualization**
   - Created line charts, bar charts, pie charts using `matplotlib`, `seaborn`, and `plotly`.

6. **Dashboard Creation**
   - Combined key insights into a single page notebook for presentation.

---

## 🎯 Final Outcome

- A personalized dashboard including:
  - Top 10 artists and songs
  - Most active listening days and hours
  - Daily and monthly listening trend
  - Duration distribution
  - Listening behavior heatmap (optional)

---

## 🚀 How to Run

1. Clone or download this repository
2. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn plotly
