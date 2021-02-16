# Music Playlist Generation using Twitter account post history and Sentiment Analysis

In this project, we aimed to develop a playlist generation capability inspired by a user’s or entity’s social media posting history. One way to accomplish this is to use sentiment analysis to compare the distribution of tweet and song lyric sentiment polarities to generate a list of recommended songs. To optimize the efficacy of this prediction, we implemented a variety of both machine and deep learning methods to predict sentiment polarity and evaluated the trained models for both data types. Ultimately, the Bidirectional LSTM for tweets and VADER model for lyrics were implemented when integrating the two polarity scores.

## Problem Statement

Given tweets from a person’s Twitter account, how can we estimate the general mood of a person to generate a music playlist for them? 
1. Predict tweets’ sentiment as positive, negative, or neutral.
2. Prepare a music lyrics database with sentiment analysis to generate sentiment label for each song.
3. Generate a playlist mapping the overall sentiment of a person’s tweet history with sentiment of different song.
