# Mood Map # 🎧 Spotify Mood Calendar 📅

This project visualizes my emotional landscape through Spotify listening history. By analyzing audio features like valence, energy, and danceability, it detects the **dominant mood** for each day and presents it beautifully using a **calendar heatmap**.

---

## 📷 Preview

![image](https://github.com/user-attachments/assets/dbf358f6-8678-4649-b5b1-ddaec675504d)

---

## 📌 Project Highlights

- 🔍 **Mood Detection**: Categorizes songs into moods (Happy, Calm, Energetic, Sad, etc.) using Spotify's audio features.
- 🗓️ **Daily Mood Calendar**: Detects the most frequent mood each day from listening history and displays it in a color-coded calendar.
- 🎨 **Custom Color Palette**: Each mood is represented with a unique color for clear emotional mapping.
- ⚡ **Optimized Data Pipeline**: Clean and efficient processing of Spotify CSV data with pandas and NumPy.
- 📊 **Data Visualization**: Uses `calplot` to plot a beautiful and intuitive year-long mood map.

---

## 🛠 Tech Stack

- **Python**
- **pandas**, **NumPy**
- **Spotify Web API**
- **matplotlib**, **calplot**
- **Jupyter Notebook**

---

## 📁 Dataset

- The dataset includes:
  - Track names, artists, albums
  - Timestamps of when songs were played
  - Audio features (valence, energy, tempo, etc.)
  - Genre enrichment using Spotify API

---
