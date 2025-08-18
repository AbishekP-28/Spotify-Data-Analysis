# 🎵 Spotify Data Analysis – Power BI Dashboard

## 📊 Overview
This project analyzes Spotify streaming data using **Power BI**.  
It provides insights into listening behavior, most played tracks, artist popularity, and user engagement patterns.

---

## 📁 Project Structure
- `Spotify Data Analysis.pbix` → Power BI dashboard  
- `docs/Spotify Data Explanation.docx` → Dataset field descriptions  
- `images/` → Dashboard screenshots  

---

## 🗂️ Data Dictionary (Key Fields)
- **spotify_track_uri** → Unique ID for each track  
- **ts** → Timestamp when track stopped playing  
- **platform** → Device type (desktop, mobile, web, smart speaker)  
- **ms_played** → Playback duration (ms)  
- **track_name, artist_name, album_name** → Song metadata  
- **reason_start, reason_end** → Playback reasons  
- **shuffle, skipped** → Engagement behavior  

*(Full details available in `/docs/Spotify Data Explanation.docx`)*  

---

## 📸 Dashboard Preview

### Overview  
![Overview](images/dashboard_overview.png)

### Top Artists  
![Top Artists](images/top_artists.png)

### Device Usage  
![Device Usage](images/device_usage.png)

### Listening Patterns  
![Listening Patterns](images/listening_patterns.png)

---

## 🚀 How to Use
1. Download or clone this repository.  
2. Open `Spotify Data Analysis.pbix` in **Power BI Desktop**.  
3. If using `.pbit` (template), load your own dataset when prompted.  

---

## 📌 Insights
- 🎶 Most listened tracks & top artists  
- 📱 Platform usage trends (desktop, mobile, web, smart speaker)  
- ⏭️ Skipping behavior and engagement drop-offs  
- 🔀 Shuffle vs non-shuffle listening habits  

---

## ⚖️ License
This project is licensed under the **MIT License**.
