![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-yellow?logo=plotly)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-008080)
![License](https://img.shields.io/badge/License-MIT-green)

# Spotify Streaming Data Visualization

This project analyzes Spotify listening history using Python to uncover trends in music consumption. It covers artist popularity, time-based activity, and daily listening habits through clean and interpretable visualizations.

---

## 📌 Objective

To practice data wrangling and visualization techniques by analyzing real-world Spotify streaming data using Pandas, Matplotlib, and Seaborn.

---

## 🧪 Tools & Libraries

- Python (Jupyter Notebook)
- Pandas for data manipulation
- Matplotlib & Seaborn for visualization

---

## 📁 Files Included

- `analysis.ipynb` – Notebook for data cleaning + visualizations
- `spotify_history.csv` – Raw dataset (excluded from GitHub)
- `README.md`, `LICENSE` – Supporting files
- `.gitignore` - Git ignore file

---

## ⚙️ Key Concepts Covered

- Datetime parsing and feature extraction
- Top-N analysis (artists, tracks)
- Streaming patterns by hour and weekday
- Distribution plots (histograms, KDE)
- Correlation heatmaps
- Plot styling and labeling

---

## 📥 Dataset Access

This project uses the Spotify Streaming History Dataset by Arshmankhalid on Kaggle. It features clean, structured user listening records including timestamps, track names, artist, album, platform, and playback reasons.

Important: The dataset is not included in this repository due to size and privacy best practices.

To run this project:

Visit the dataset page on Kaggle:
"Spotify Streaming History Dataset" by Arshmankhalid.

Download the spotify_history.csv file (about ~6 MB).

Create a folder named data/ in your project root and place the CSV inside:
data/spotify_history.csv

Launch the notebook (analysis.ipynb) — it will automatically load the file from that path.
