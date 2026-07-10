# 🎵 Spotify Spain Top 50 Playlist Lifecycle Analysis

A complete data analytics project that analyzes the lifecycle of songs in Spotify's Spain Top 50 playlist using Python, Power BI, and exploratory data analysis. The project uncovers how songs enter, grow, peak, mature, and decline while identifying the factors that influence playlist longevity.

---

## 📌 Project Overview

This project analyzes **27,750 daily Spotify playlist records** from Spain's Top 50 playlist (May 2024 – November 2025) to understand content performance and lifecycle behavior.

The analysis focuses on answering questions such as:

- How long do songs stay on the playlist?
- How quickly do songs reach their peak position?
- How frequently does the playlist rotate?
- Which song characteristics increase playlist longevity?
- What business insights can help optimize release strategies?

The project includes both a **Python data analysis pipeline** and an **interactive Power BI dashboard**.

---

## 📊 Dataset

- **Market:** Spotify Spain Top 50
- **Time Period:** May 2024 – November 2025
- **Rows:** 27,750
- **Unique Songs:** 545
- **Unique Artists:** 306

### Features

- Date
- Playlist Position
- Song Name
- Artist
- Popularity
- Duration (ms)
- Album Type
- Total Tracks
- Explicit Content
- Additional engineered features

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Power BI
- Microsoft Excel

---

## 📈 Project Workflow

1. Data Cleaning
2. Duplicate Removal
3. Feature Engineering
4. Exploratory Data Analysis
5. Lifecycle Construction
6. KPI Calculation
7. Lifecycle Classification
8. Visualization
9. Business Recommendation

---

## 📊 Lifecycle Framework

Each song is classified into one of five lifecycle stages:

- 🟢 New Entry
- 🔵 Growth
- 🟡 Peak
- 🟠 Mature
- 🔴 Decline

The lifecycle is determined using:

- Entry Date
- Exit Date
- Days on Playlist
- Peak Position
- Average Position
- Popularity Score

---

## 📌 Key Performance Indicators

The project computes several important KPIs including:

- Average Playlist Lifetime
- Median Lifetime
- Time to Peak
- Playlist Churn Rate
- Average Popularity
- Peak Position
- Lifecycle Distribution
- Average Days by Album Type
- Average Days by Explicit Content
- Average Days by Song Duration

---

## 📈 Key Insights

- Songs remain on the playlist for an average of **50.9 days**.
- Nearly **40% of songs exit within one week**.
- Songs reach their highest rank in approximately **10 days**.
- Singles outperform album tracks in playlist longevity.
- Clean versions survive longer than explicit tracks.
- Songs between **3–4 minutes** perform best.
- Spain's playlist replaces approximately **1.7 songs per day**.

---

## 📊 Power BI Dashboard

The interactive dashboard includes:

- KPI Cards
- Lifecycle Stage Distribution
- Playlist Churn Analysis
- Popularity Trends
- Duration Analysis
- Album Type Comparison
- Explicit vs Clean Comparison
- Song Lifecycle Explorer
- Interactive Filters and Slicers

---

## 📂 Project Structure

```
Spotify-Spain-Lifecycle-Analysis/
│
├── Data/
│   ├── dataset.csv
│
├── Notebook/
│   ├── Spotify_Lifecycle_Analysis.ipynb
│
├── Dashboard/
│   ├── Spotify_Lifecycle.pbix
│
├── Report/
│   ├── Research_Report.pdf
│
├── Images/
│   ├── dashboard.png
│
└── README.md
```

---

## 🚀 Business Recommendations

- Release singles before albums.
- Focus marketing efforts within the first 10 days after release.
- Produce clean versions for the Spain market.
- Target song durations between 3–4 minutes.
- Monitor playlist churn to identify optimal release windows.
- Invest in Latin and reggaeton collaborations for better retention.

---

## 📚 Skills Demonstrated

- Data Cleaning
- Data Wrangling
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Data Visualization
- Business Intelligence
- Dashboard Design
- KPI Development
- Storytelling with Data
- Power BI Reporting

---

## 📸 Dashboard Preview

<img width="1388" height="796" alt="Screenshot 2026-07-06 210622" src="https://github.com/user-attachments/assets/5f77855c-8a6c-4149-91a9-499834c3e26d" />

---

## 🎯 Future Improvements

- Predict playlist lifespan using Machine Learning.
- Build a recommendation system for release strategy.
- Compare playlist behavior across multiple countries.
- Deploy the dashboard using Power BI Service.
- Automate daily data updates.

---

## 👨‍💻 Author

**Teja Venakata Nukesh**

B.Tech Computer Science Engineering

Passionate about Data Analytics, Business Intelligence, Machine Learning, and Data Visualization.

📧 Feel free to connect and provide feedback!

---

## ⭐ If you found this project useful, consider giving it a Star!
