# Dsa210-Project
Spotify Mood Analysis 🎧

## Login
This project aims to analyze my own Spotify listening data to reveal my music habits and their relationship to my mood. Using the Spotify Web API, I will collect data about the tracks I listen to, their sonic characteristics (e.g. energy, valence), and related metadata such as genres and artists. The ultimate goal is to understand how music affects my mood and provide personalized recommendations based on data.

---

## Technologies I will be using
- **Programming Language:** Python
- **APIs:** Spotify Web API
- **Libraries:**
  - Data Analysis: Pandas, NumPy
  - Visualization: Matplotlib, Seaborn
- **Tools:** Jupyter Notebook, GitHub

## Dataset Description
### Spotify Web API
**Purpose:** Provides access to personal Spotify data.  
**Received Data:**
- **Listening History:** Information about recently played tracks, including track titles, artists, and albums.
- **Audio Features:** Details such as energy, value, danceability and tempo for each track.
- **Genres and Artists:** Classification of tracks by genre and artist metadata.

- ---

## Project Idea and Plan
### Goals
- **Understand Listening Habits:**analyze listening history to identify daily and weekly trends.
- **Discover Mood Patterns:** Examine correlations between voice characteristics (valence, energy) and mood categories.
- **Personalized Recommendations:** Recommends playlists that improve your mood

### Data Collection
- **Fetch Listening History:** Get recently played tracks using Spotify API.
- **Collect Audio Features:** Collect energy, valence, tempo and other music features for each track.


### Data Analysis
#### **Listening Trends**
- Calculate daily and weekly listening habits.


#### **Mood Patterns**
- Cluster traces based on valence and energy scores to define mood categories:
  - **Happy:** High valence, high energy
  - **Calm:** High valence, low energy
  - **Sad:** Low valence, low energy
  - **Energetic:** Low valence, high energy
- Analyze mood distribution over time (e.g. morning and evening listening patterns).
-0.0-0.3:Sad mood
-0.3-0.7:Calm mood
-0.7-1:Happy mood
#### **Playlist Suggestions**
- Use mood analysis to create personalized playlists tailored to specific activities, e.g. study, exercise, relaxation.

### Creating Analysis
- Summarize key findings on listening habits and mood correlations.
- Visualize listening trends and mood distribution through graphs and charts.

---

## Expected Results
By analyzing my Spotify data I hope to:
1. Get insight into my music preferences and how they change depending on my mood and time of day.
2. Understand the role of certain genres or artists in influencing my mood.
