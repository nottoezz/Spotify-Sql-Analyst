# 🎧 Spotify SQL Capstone Project

Welcome to the **Spotify SQL Capstone**, a portfolio project created as part of the [HyperionDev Full Stack Web Developer course](https://www.hyperiondev.com/). This interactive website presents SQL analysis conducted on real-world Spotify streaming data to uncover user listening behavior, playback patterns, and playlist optimization insights.

---

## 🔍 Project Overview

This project demonstrates proficiency in:

- Relational database setup and configuration (MariaDB via XAMPP)
- SQL query writing for data analysis
- Data cleaning and transformation using SQL
- Front-end development using HTML, CSS, and JavaScript

---

## 📁 Project Structure

```
📂 spotify-sql-capstone/
│
├── index.html           # Main website containing all queries, results, and overview
├── style.css            # Custom styling (if extracted from index.html)
├── script.js            # JavaScript to handle interactions (inline or separate)
├── README.md            # This file
├── /assets              # Optional folder for logos or media
```

---

## 🧰 Tools Used

- **Database:** [MariaDB](https://mariadb.org/) (via [XAMPP](https://www.apachefriends.org/))
- **GUI:** [phpMyAdmin](https://www.phpmyadmin.net/)
- **Dataset:** [Spotify Streaming History (Kaggle)](https://www.kaggle.com/datasets/sgoutami/spotify-streaming-history)
- **Frontend:** HTML5, CSS3, JavaScript ES6
- **Syntax Highlighting:** [Highlight.js](https://highlightjs.org/)

---

## 📊 Key Analyses & SQL Queries

The website contains SQL queries and results that answer real-world analytical questions:

### 1. Skipped Songs Analysis
- Find songs skipped within 10 seconds.
- Explore implications of high skip counts vs high total plays.

### 2. User Selection Insights
- Identify most manually selected tracks.
- Analyze skip rates for autoplayed songs (only one autoplay track found: `"Say It, Just Say It"` with 0% skips).

### 3. Playlist Balancing
- Detect overplayed artists (appeared > 2 times).
- Surface longest-played tracks where shuffle was disabled.

### 4. Rage Skip Detection
- Find sessions with 5+ skips in under 60 seconds.
- Analyze by artist, album, and platform (Android session found).

### 5. One-Hit Wonders
- Identify artists where 90%+ of plays came from a single track.

> ⚠️ **Note:** Output tables are limited to 10 rows for readability on the website.

---

## 🚀 How to Use

1. Open `index.html` in any modern web browser.
2. Click on each query title to expand its SQL code and mock results.
3. Click **Run** to simulate query execution and reveal the data.

---

## 📌 Educational Context

This project was created as a requirement for the **HyperionDev Full Stack Web Developer Bootcamp** and serves as both an SQL capstone and a demonstration of frontend presentation skills.

---

## 📜 License

All content provided in this project is for educational purposes only. Original dataset is sourced from public Kaggle repositories and used under fair use.

---

## 👤 Author

**Liam Birch**  
2025  
[HyperionDev Full Stack Developer](https://www.hyperiondev.com/)
