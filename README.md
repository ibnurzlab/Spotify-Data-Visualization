# Spotify-Data-Visualization
This project is an Exploratory Data Analysis (EDA) on the songs_normalize.csv dataset, which includes various acoustic features of songs. The aim is to explore the dataset, analyze feature distributions, study correlations, and uncover insights into the patterns and characteristics of popular tracks.

## 📂 Dataset
- **File Name:** `songs_normalize.csv`  
- **Source:** Public dataset of Spotify songs (original source can be added if available).  
- **Available Features:**
  - `popularity` : song popularity score
  - `danceability` : how suitable a song is for dancing
  - `energy` : intensity and activity level of the song
  - `loudness` : average loudness
  - `speechiness` : presence of spoken words in the track
  - `acousticness` : acoustic characteristics of the song
  - `liveness` : likelihood that the track was recorded live
  - `valence` : musical positivity (mood of the track)
  - `tempo` : speed of the song in BPM
  - and several other attributes

## 🛠️ Tools & Libraries
The project was built using **Python** and the following libraries:
- `pandas` & `numpy` → data manipulation and preprocessing
- `matplotlib` & `seaborn` → basic visualization
- `plotly` → interactive visualization
- `datetime` → handling date and time data
- `warnings` → suppressing unnecessary warnings

## 🔍 Analysis Workflow
1. **Data Import**
   - Load the dataset `songs_normalize.csv`.
2. **Data Cleaning**
   - Check for missing values.
   - Remove duplicate records.
   - Review data types and descriptive statistics.
3. **Exploratory Data Analysis**
   - Visualize feature distributions (`popularity`, `danceability`, `energy`, etc.).
   - Analyze correlations between features.
   - Build interactive histograms with Plotly.
4. **Insights**
   - Identify general trends in popular songs.
   - Explore which features may influence song popularity.

## 📊 Key Findings
- Songs with higher **danceability** tend to have better popularity scores.  
- **Energy** and **valence** are closely related to the overall mood of songs.  
- The **popularity** distribution is skewed, with only a small proportion of songs being highly popular.  
- Acoustic features provide useful information about song characteristics and patterns.
