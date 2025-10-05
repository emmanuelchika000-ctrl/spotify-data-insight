# spotify-data-insight
spotify-data-insights/ │ ├── data/ │   ├── raw/spotify_tracks.csv │   └── cleaned/spotify_cleaned.csv │ ├── notebooks/ │   ├── data_cleaning.ipynb │   ├── exploratory_analysis.ipynb │   └── visualization.ipynb │ ├── reports/ │   ├── spotify_dashboard.png │   └── final_report.pdf │ ├── requirements.txt └── README.md
# 🎧 Spotify Data Insights

## 📖 Project Overview
This project explores and visualizes Spotify track data to uncover patterns in popularity, artist trends, and musical features such as danceability, energy, and tempo.  

The goal is to understand what makes songs go viral and how audio features influence listener engagement.

---

## 📊 Dataset
- **Source:** [Kaggle - Spotify Tracks Dataset](https://www.kaggle.com/datasets)
- **Size:** ~50,000 songs
- **Columns:** Track Name, Artist, Genre, Popularity, Danceability, Energy, Tempo, Duration, Release Year

---

## ⚙️ Tools & Libraries
- **Python** 🐍  
- **Jupyter Notebook**  
- **Pandas & NumPy** – Data cleaning and manipulation  
- **Matplotlib & Seaborn** – Data visualization  
- **Plotly** – Interactive charts  
- **Power BI / Tableau (optional)** – Dashboard visualization  

---

## 🧹 Data Cleaning
- Removed duplicate and null entries  
- Standardized genre names  
- Converted duration from milliseconds to minutes  
- Extracted release year from date column  

---

## 🔍 Exploratory Data Analysis (EDA)
### Key Questions:
1. What features most influence a song’s popularity?  
2. Which artists consistently produce high-energy tracks?  
3. How do music features change across different genres and years?  
4. What are the trends in danceability and energy over time?

---

## 📈 Key Insights
- 🎶 **Danceability and energy** have a strong positive correlation with popularity.  
- 🎤 **Top artists** like Ed Sheeran and The Weeknd appear most frequently in the top 100 playlists.  
- 🕺 Genres like **Pop** and **Dance/Electronic** dominate the charts.  
- 📆 Songs are getting **shorter** and **more upbeat** over the years.  

---

## 📊 Visualizations
- Popularity vs. Danceability Scatterplot  
- Top 10 Artists by Average Popularity  
- Trend of Energy & Tempo Over Years  
- Genre Popularity Heatmap  

![Spotify Dashboard](reports/spotify_dashboard.png)

---

## 🧠 Conclusion
Spotify’s data shows how music evolution and listener preferences are closely tied to tempo, rhythm, and emotional tone.  
Businesses and creators can use these insights for:
- Better playlist curation  
- Data-driven marketing  
- Artist trend forecasting

---

## 🧩 Repository Structure
