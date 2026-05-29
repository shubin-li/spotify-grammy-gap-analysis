# spotify-grammy-gap-analysis-CSC1143

Spotify listener trends vs. Grammy Award recognition analysis using data visualisation techniques on Spotify & Grammy datasets. CSC1143 – Data Management & Visualisation, DCU, Autumn 2025.

## Project Overview

This project investigates whether Spotify listeners' music preferences have converged with Grammy Award standards between 2000 and 2023. By merging the Spotify 1 Million Tracks dataset with Grammy nominees/winners data, we analyse how the popularity distribution of Grammy-recognised songs has shifted over time.

**Research Question:** *From Popularity to Prestige: Are Spotify Listeners Moving Closer to Grammy Standards?*

## Datasets

| Dataset | Source |
|---|---|
| Spotify 1 Million Tracks | [Kaggle](https://www.kaggle.com/datasets/amitanshjoshi/spotify-1million-tracks) |
| Grammy Award Nominees and Winners (1958–2024) | [Kaggle](https://www.kaggle.com/datasets/kfoster150/grammy-award-nominees-and-winners-1958-2024) |

## Methodology

- **Data Cleaning:** Standardised artist names and track titles (lowercasing, punctuation removal, handling variants like `feat.` vs `featuring`)
- **Dataset Integration:** Matched songs across both datasets using track title + artist name string matching
- **Visualisation:** Interactive histogram built in Tableau showing Spotify popularity distribution of Grammy-nominated songs filtered by year (2000–2023)

## Key Finding

Grammy-winning songs have trended towards higher Spotify popularity scores over the 2000–2023 period, suggesting that public listening preferences and Grammy recognition have become increasingly aligned.

## Tools

Python · Pandas · Matplotlib · Seaborn · Tableau · Power BI · Jupyter Notebook · Google Drive

## Team

| Member | Contributions |
|---|---|
| Ananya | Final data pipeline, dataset merging, Tableau histogram, Power BI radar chart |
| Shubin Li | Exploratory analysis, valence/genre/category visualisations, dataset grouping strategy |
