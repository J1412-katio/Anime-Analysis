
# 📊 Anime Data Analysis with Python

This project analyzes a large anime dataset using Python, focusing on relationships between genres, types, ratings, and popularity metrics. Through various data visualizations, we aim to uncover trends and insights within the anime industry.

---

## 📁 Dataset Overview

- **Source**: `anime.csv`
- **Total Entries**: 12,294
- **Columns**:
  - `anime_id`: Unique identifier for each anime
  - `name`: Title of the anime
  - `genre`: Genres associated with each title
  - `type`: Media type (TV, Movie, OVA, etc.)
  - `episodes`: Total number of episodes
  - `rating`: User rating (float)
  - `members`: Number of users who have watched the anime

---

## 🧪 Packages Used

```python
pandas
numpy
matplotlib
seaborn 
plotly

---

## 📈 Visualizations & Analysis

### 1. 📉 Line Chart – Anime Ratings Over Index

- **Goal**: Identify overall trends in anime ratings.
- **Insight**: Observe how ratings fluctuate throughout the dataset.
- **Suggestions**:
  - Add a horizontal line representing the average rating.
  - Highlight exceptionally high or low-rated titles.

### 2. 📊 Bar Chart – Average Rating by Genre

- **Goal**: Compare average ratings across different genres.
- **Insight**: Identify genres that consistently receive high or low ratings.
- **Suggestions**:
  - Sort genres alphabetically or by number of entries for varied perspectives.

### 3. ⚫ Scatter Plot – Rating vs. Number of Members

- **Goal**: Analyze the relationship between anime ratings and popularity.
- **Insight**: Understand how highly rated titles align with user engagement.
- **Suggestions**:
  - Use color to differentiate between anime types (TV, Movie, OVA).

### 4. 🌡️ Heatmap – Ratings by Type and Genre

- **Goal**: Examine how anime types and genres affect average ratings.
- **Insight**: Detect combinations of type and genre that yield higher or lower ratings.
- **Suggestions**:
  - Include annotations to show exact values.
  - Parse multi-genre entries for improved accuracy.

---

## 🛠️ Improvements & Next Steps

- Split multi-genre entries into individual categories.
- Handle missing ratings (~1.9% of entries).
- Normalize episode counts for consistency.
- Integrate interactive visualizations using Plotly or Dash.
