# Song_Reccomendation_Systems
A recommendation system that recommends songs to user based on the lyrics of their liked songs

## Description

In this project, I attempted to implement a Content-Based Filtering Music Recommendation System using K-Means Clustering to process song lyrics with their Term-Frequency values. 

### Big Picture
1. Use Term/word Frequency to handle song’s lyrics
2. Cluster songs with similarities in lyrics and meaning together using K-means clustering where the number of clusters is a certain percentage of the dataset size we have trained on.
3. Recommend multiple songs with highest lyric similarity.
4. Check perofrmance using RMSE, Silhouette Score



Steps Involved:
![stages](https://github.com/AineshAdvani/Song_Reccomendation_Systems/assets/42750392/a8e7c9a7-3147-4baa-9da1-6754918391e4)


## DataSet used
Used musiXmatch (MXM) from Million Song Dataset for training the model
- Contains lyrics information from tracks in MSD
- Already processed (not in the form of songs’ full lyrics)
- Format: bag-of-words- each track is described as the word-count for a dictionary of the top - 5000 words across the set.

Attributes we require:
- Track ID (MSDID)
- Track name (Title) 
- Set of Word - Shortened Lyrics of track

## Setup
- clone the repository and used the built uploaded training dataset to train the model using Song_Recommendation.ipynb
- Use your own dataset of that contains lyrics information and run Song_Recommendation.ipynb to train your model on it.






