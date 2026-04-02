# Spotify Data Analysis with Python

## Project Overview
This project focuses on analyzing Spotify music data using Python to uncover insights about **song features, artist trends, and listener preferences**.  

The goal is to perform **Exploratory Data Analysis (EDA)** and generate actionable insights about what makes songs popular and how music trends evolve over time.

---

## Objective
> Analyze Spotify data to identify patterns in music features, user preferences, and industry trends to support better decision-making in music production and marketing.

---

## Dataset Description

The dataset contains Spotify track-level data with the following features:

- **Song Name** – Title of the song  
- **Artist** – Performer of the track  
- **Genre** – Music category  
- **Popularity** – Popularity score based on streams  
- **Danceability** – Suitability for dancing (0–1)  
- **Energy** – Intensity of the song (0–1)  
- **Tempo** – Speed in BPM  
- **Acousticness** – Acoustic quality (0–1)  
- **Loudness** – Volume in decibels (dB)  
- **Valence** – Positiveness of the song (0–1)  

---

## Project Workflow

### 1️. Data Preparation

- Loaded dataset using **Pandas**
- Handled missing values and removed inconsistencies  
- Standardized numerical features  
- Performed feature engineering:
  - Popularity categories  
  - Artist ranking  
  - Genre trends  

---

### 2️. Exploratory Data Analysis (EDA)

- Descriptive statistics (mean, median, standard deviation)  
- Distribution analysis of features like:
  - Popularity  
  - Energy  
  - Danceability  
- Correlation analysis between features  
- Outlier detection in tempo and loudness  

---

### 3️. Data Visualization

Used **Matplotlib, Seaborn, and Plotly** to create:

- 📊 **Histograms** – Distribution of features  
- 📈 **Bar Charts** – Top genres and artists  
- 📦 **Boxplots** – Spread and variability  
- 🔥 **Heatmaps** – Correlation between features  
- ⚡ **Scatter Plots** – Feature relationships  

---

### 4️. Musical Trend Analysis

- 📅 **Time Series Analysis** – Trends over years  
- 🎼 **Genre Trends** – Popular genres over time  
- 🎤 **Artist Analysis** – Most active and popular artists  

---

### 5️. Insights & Findings

- Identified **top-performing genres and artists**  
- Found relationships between:
  - Energy & popularity  
  - Danceability & user preference  
- Observed trends in music evolution  
- Suggested ideal features for playlist creation  

---

## Key Insights

- High **energy and danceability** often correlate with popularity  
- Certain genres consistently dominate streaming platforms  
- Music trends evolve over time with shifts in tempo and acousticness  
- Popular songs tend to have balanced loudness and valence  

---

## Visualizations Included

- Popularity distribution  
- Feature correlation heatmap  
- Genre-wise analysis  
- Artist performance charts  
- Feature vs popularity scatter plots  

---

## Tech Stack

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn, Plotly  

---

