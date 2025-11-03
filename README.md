# Spotify-structure-clustering
Clustering Spotify audio features to analyze music structure and map moods to book genres. Produces tailored playlists to enhance readers' experience for various book genres. Demonstrates KMeans clustering, feature interpretation, and visualization of patterns in music data.

## Objective
Identify patterns in Spotify audio features to group songs by musical characteristics, then match these clusters to moods suitable for various book genres. 
Key goals include:
- analyzing songs based on audio features like energy, danceability, acousticness, and instrumentalness
- applying KMeans clustering to group similar tracks
- interpreting cluster profiles to assign moods to corresponding book genres
- generating tailored playlists to enhance the reader’s experience
- demonstrating feature scaling, clustering methodology, interpretaions, and visualization

## Tools Used
Python (pandas, scikit-learn, matplotlib, seaborn)
Jupyter Notebook

## Dataset
Contains a collection of Spotify tracks with audio features
Features include track-level data such as danceability, energy, acousticness, valence, and more
Data used is from Kaggle:
https://www.kaggle.com/datasets/priyamchoksi/spotify-dataset-114k-songs

## Features
The dataset includes features such as:
-explicit – whether the track contains explicit content
-danceability – describes how suitable a track is for dancing
-energy – intensity and activity of the track
-loudness – overall volume in decibels
-speechiness – presence of spoken words
-acousticness – confidence measure of whether the track is acoustic
-instrumentalness – likelihood the track is instrumental or vocal
-valence – musical positiveness conveyed

## Clusters
Cluster 0 – Confident, bold, high-impact tracks with strong vocals and electronic backing: Fantasy / Action / Adventure
Cluster 1 – Intimate, acoustic, vocal-driven tracks with emotional tone: Romance / Drama
Cluster 2 – Upbeat, energetic, electronic-forward tracks: Science Fiction / Adventure
Cluster 3 – Quiet, instrumental, dark or suspenseful tracks: Thriller / Mystery / Horror
Cluster 4 – Dynamic, lively, instrumental electronic tracks: Historical Fiction

## Key Findings
Different clusters clearly represent distinct moods and audio structures, enabling targeted playlist creation.
KMeans clustering effectively grouped songs with similar profiles based on feature values.
Cluster analysis allows mapping music to book genres, demonstrating an applied use-case for audio feature interpretation.
Playlists generated from these clusters can enhance readers’ immersive experience by matching to the emotional tone of their book.

## Notebook
All code, clustering analysis, and visualizations are included in the Jupyter Notebook in this repository.
