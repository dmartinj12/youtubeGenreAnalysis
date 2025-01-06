# YouTube Genre Analysis

## Purpose

This project was developed to analyze YouTube statistics across different genres to study which genres perform the best across various metrics. Initially, we aimed to use the YouTube API to retrieve data, but due to limitations with the API, we were restricted to only retrieving the top 5 videos of the day. Moreover, there was no way to filter or select specific data based on our needs. 

To overcome these challenges, we found a Kaggle dataset that provided the necessary information for our analysis. The dataset was a comprehensive collection of YouTube videos across various genres, which allowed us to perform deeper analyses without API restrictions.

## Data Overview

The dataset contains video statistics including:
- Video ID
- Title
- Published date
- Channel information
- Category (genre)
- View count
- Like count
- Dislike count
- Comment count
- More

We used this data to examine metrics such as view count, like count, and comment count, broken down by genre, and explored how these metrics varied across different categories.

## Key Findings

During our analysis, we made some interesting observations, such as:

- The standard deviation of all video view counts is **9,794,087.11**.
- The standard deviation of all video like counts is **453,946.93**.
- The standard deviation of all video comment counts is **72,608.53**.

These figures reflect the variability and spread of the data across different video categories, and give insight into the performance fluctuations of YouTube videos.

## Steps Taken

1. **Data Cleaning and Preprocessing:**
   - We filtered the dataset to focus on relevant columns (category, view count, like count, comment count).
   - Addressed missing values and outliers.
   
2. **Exploratory Data Analysis (EDA):**
   - Performed basic statistical analysis and visualization.
   - Generated box plots to compare the view count across different categories.

3. **Advanced Analysis:**
   - Aggregated like counts to analyze top videos in each genre.
   - Created a heatmap visualizing the top liked videos by genre.

4. **Challenges and Limitations:**
   - We initially intended to use the YouTube API to collect data, but API restrictions limited us to only 5 videos per day.
   - We used a Kaggle dataset as an alternative, which allowed us to retrieve more comprehensive data.

## Running the Code

Due to the large size of the dataset, we were unable to include the CSV file in the repository. However, you can download the dataset directly from Kaggle:

[Download US YouTube Trending Data](https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset?resource=download&select=US_youtube_trending_data.csv)

Once downloaded, place the CSV file in the project directory and run the Jupyter notebook to replicate the analysis.

## Conclusion

This analysis provides a detailed examination of YouTube video performance across genres. The findings offer valuable insights into how different categories of videos perform in terms of engagement (likes, comments, views). Although we faced some challenges with data retrieval from the YouTube API, the Kaggle dataset provided a robust solution to carry out our analysis. We hope this analysis contributes to understanding the dynamics of video content across various YouTube genres.
