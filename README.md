# 🎵 Spotify Data Analysis & Dashboard using Power BI

This project showcases a **Power BI dashboard** created after cleaning and transforming a Spotify dataset using **Power Query Editor**. The aim is to derive insights into streaming trends, artist popularity, and audio features across various platforms.

---

##  Steps Followed

1. **Data Import**: Uploaded the `Spotify.csv` dataset into Power BI Desktop.
2. **Data Profiling**: Enabled `Column distribution`, `Column quality`, and `Column profile` under the *View* tab for better understanding.
3. **Data Cleaning**:
   - Changed column data types.
   - Identified and retained error rows for investigation before removing them.
   - Removed duplicate records.
   - Replaced null values with appropriate defaults.
4. **Data Transformation**:
   - Created a custom `Date` column using release year, month, and day.
5. **Visualization**:
   - Designed interactive visuals using bar charts, line charts, donut charts, and cards.

---

##  Dataset Features

  The dataset includes the following key columns:

- `Track`: Name of the song  
- `Artist`: Name of the artist(s)  
- `Artists Count`: Number of contributing artists  
- `Released Year/Month/Day`: Date the song was released  
- `Streams`: Total number of Spotify streams  
- `in_spotify_playlists`: Number of Spotify playlists the track appears in  
- `in_spotify_charts`, `in_apple_charts`, `in_deezer_charts`, `in_shazam_charts`: Chart performance across platforms  
- `bpm`, `key`, `mode`: Musical characteristics  
- `danceability`, `valence`, `energy`, `acousticness`, `instrumentalness`, `liveness`, `speechiness`: Audio features

---

## Key Insights

- **Total Tracks**: 952  
- **Total Streams**: 489 Billion  
- **Average Streams per Track**: 514 Million  
- Significant rise in song streams from **2000 to 2020**
- Peak streaming observed in **September** and **January**
- Top 5 artists analyzed by:
  - **Danceability** and **Valence** (Donut Charts)
  - **Stream Count** (Bar Charts)

---

## Notes

This beginner-friendly data visualization project highlights data cleaning, transformation, and storytelling using Power BI, aimed at demonstrating skills relevant for data analyst roles.
