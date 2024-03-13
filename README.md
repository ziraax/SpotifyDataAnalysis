# Spotify Songs Analysis

## Overview

This project explores the characteristics of songs available on Spotify using two datasets obtained from Kaggle. The analysis includes Exploratory Data Analysis (EDA) to uncover insights about song features and their relationships and NLP. We also build a pipeline for HuggingFace model.

## Data Sources

The data for this project was obtained from the following sources:

1. [Spotify Songs Dataset - JoeBeachCapital](https://www.kaggle.com/datasets/joebeachcapital/57651-spotify-songs/data)
   - This dataset contains information about various features of songs available on Spotify, such as danceability, energy, key, loudness, mode, speechiness, acousticness, instrumentalness, liveness, valence, tempo, and time signature.

   **Dataset Description:**
   The Spotify Songs Dataset provides a comprehensive collection of song features that are typically used for music analysis and recommendation systems. These features are extracted from the Spotify Web API and cover a wide range of musical attributes.

2. [Spotify 12M Songs Dataset - RodolfoFigueroa](https://www.kaggle.com/datasets/rodolfofigueroa/spotify-12m-songs/data)
   - This dataset provides a collection of song lyrics from Spotify, which can be used for natural language processing (NLP) tasks such as sentiment analysis and topic modeling.

   **Dataset Description:**
   The Spotify 12M Songs Dataset offers a vast collection of song lyrics available on the Spotify platform. This dataset enables researchers to analyze the textual content of songs and extract meaningful insights related to language use and sentiment.

Please refer to the respective datasets for more details and to access the raw data.

## Tech Stack

- **Programming Languages:** Python
- **Libraries and Frameworks:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Hugging Face Transformers
- **Development Environment:** Jupyter Notebooks, Visual Studio Code

## Key Features

- Exploratory Data Analysis (EDA)
- NLP Analysis
- Emotion Analysis
- Hugging Face transformers pipeline with [SamLowe/roberta-base-go_emotions](https://huggingface.co/SamLowe/roberta-base-go_emotions)
- LDA (Latent Dirichlet Allocation)
- Clustering


# Datasets

https://www.kaggle.com/datasets/joebeachcapital/57651-spotify-songs/data
https://www.kaggle.com/datasets/rodolfofigueroa/spotify-12m-songs/data

