
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

📈 Visualizations & Analysis
1. 📉 Line Chart - Anime Ratings Over Index

    Goal: Identify overall trends in anime ratings.

    Insight: View how ratings change across the dataset.

    Enhancement Ideas:

        Add a line for the average rating.

        Label top or bottom rated titles.

2. 📊 Bar Chart - Average Rating by Genre

    Goal: Compare average ratings across genres.

    Insight: Discover which genres tend to receive higher ratings.

    Enhancement Ideas:

        Sort genres by anime count or alphabetically for different perspectives.

3. ⚫ Scatter Plot - Rating vs. Number of Members

    Goal: Analyze the correlation between user ratings and popularity.

    Insight: Visualize how rating influences viewership (or vice versa).

    Enhancement Ideas:

        Add color coding based on type (TV, Movie, OVA).

4. 🌡️ Heatmap - Ratings by Type and Genre

    Goal: Examine how anime type and genre affect ratings.

    Insight: Pinpoint genre-type combinations with highest or lowest ratings.

    Enhancement Ideas:

        Add annotations for exact values.

        Use better genre parsing to handle multi-genre entries.

🛠️ Improvements & Next Steps

    Clean and split multi-genre values into separate rows or categories.

    Handle missing ratings (1.9% of dataset).

    Normalize episodes data to numerical values for deeper analysis.

    Add interactive visualizations with Plotly or Dash.
