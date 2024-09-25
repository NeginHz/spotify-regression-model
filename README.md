
# Spotify 2023 Top Songs Dataset - Random Forest Model Project

## Overview

This project applies a Random Forest Regression model to a dataset of the top Spotify songs of 2023. The goal is to predict certain musical attributes and trends using the available data.

## Dataset

This dataset contains a comprehensive list of the most famous songs of 2023, as listed on Spotify. It offers a wealth of features beyond what is typically available in similar datasets, providing insights into each song's attributes, popularity, and presence on various music platforms.

### Key features include:
- **Track Name**: The name of each song.
- **Artist(s) Name**: The artist or group performing the song.
- **Release Date**: The release date of each song.
- **Spotify Playlists & Charts**: Information about the song's presence on Spotify playlists and charts.
- **Streaming Statistics**: Data on the number of streams each song has on Spotify.
- **Apple Music Presence**: Whether the song is also available on Apple Music.
- **Deezer Presence**: Whether the song is available on Deezer.
- **Shazam Charts**: Information about the song’s presence on Shazam charts.
- **Audio Features**: Various audio attributes like tempo, energy, danceability, and more.

The dataset was sourced from Kaggle and can be downloaded using the following command:

```bash
kaggle datasets download -d nelgiriyewithana/top-spotify-songs-2023
```

## Project Goals

- **Data Cleaning**: Prepare the data for model training by handling missing values, converting columns to appropriate data types, and ensuring the dataset is ready for analysis.
- **Feature Engineering**: Extract and preprocess features from the dataset that can be used to train the Random Forest Regression model.
- **Model Training**: Train a Random Forest model using the cleaned dataset.
- **Evaluation**: Assess the model's performance using metrics like R² and explain the results in terms of the dataset's features.

## Model

The Random Forest Regression model was chosen due to its ability to handle large datasets with multiple features and its robustness in avoiding overfitting. The model's R² score was **0.88**, indicating strong predictive performance.

## Copyright Information

The dataset used in this project is publicly available on Kaggle and is provided by **Nelgiriye Withana**. The dataset is intended for educational and research purposes.

For more information, visit the [Kaggle Dataset Page](https://www.kaggle.com/nelgiriyewithana/top-spotify-songs-2023).

## Requirements

To run this project, you will need the following dependencies:

- `pandas`
- `scikit-learn`
- `numpy`
- `matplotlib`
- `seaborn`

You can install them using the `requirements.txt` file provided in this repository:

```bash
pip install -r requirements.txt
```

## How to Run

1. Download the dataset using the Kaggle command.
2. Prepare your environment by installing the required dependencies.
3. Run the Python scripts to clean the dataset, train the model, and evaluate its performance.
