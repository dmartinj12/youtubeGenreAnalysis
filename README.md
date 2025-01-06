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

From our analysis, we observed the following key insights:

- **Video Performance Across Categories:** We found significant variation in video performance across genres, with categories like "Music" and "Entertainment" consistently showing higher engagement metrics (views, likes, comments) compared to others like "News" and "Education." This suggests that content in certain genres inherently generates more interest and engagement from viewers.
  
- **Top Liked Videos:** The heatmap analysis provided a clear picture of the top 5 most-liked videos per category. This allowed us to identify the most successful videos in each genre, highlighting trends such as the dominance of music videos in terms of likes and interactions. The Music category, for instance, showcased videos with millions of likes, far outpacing other categories.

- **Standard Deviation Insight:** The standard deviation of metrics like view count, like count, and comment count gave us valuable context for understanding the spread and variability of the data. A high standard deviation in these metrics indicates that while some videos perform exceptionally well, others may struggle to gain traction. This variability is crucial in determining which genres are more consistent in their performance and which are more prone to outliers.

- **Engagement Factors:** By comparing the performance of videos in different categories, we were able to infer that genres like "Music" tend to receive more engagement overall, likely due to a combination of fanbase loyalty and viral content. In contrast, categories like "News" and "Education" showed more moderate engagement levels, likely due to the nature of their content, which may not be as shareable or attention-grabbing.

## Steps Taken

1. **Data Cleaning and Preprocessing:**
   - Filtered the dataset to focus on relevant columns (category, view count, like count, comment count).
   - Handled missing values and outliers to ensure clean data for analysis.

2. **Exploratory Data Analysis (EDA):**
   - Performed basic statistical analysis and visualizations.
   - Created box plots to compare the distribution of view counts across different categories.

3. **Advanced Analysis:**
   - Aggregated like counts to highlight the top videos in each genre.
   - Generated a heatmap visualizing the top 5 most liked videos per category, helping to identify trends in video performance across genres.

4. **Challenges and Limitations:**
   - The YouTube API was initially considered for data collection, but we were limited by API constraints that only allowed us to fetch data for the top 5 videos of the day, which wasn't sufficient for our needs.
   - We resorted to using a Kaggle dataset, which provided a broader range of data, but also introduced the challenge of handling large file sizes.

## Running the Code

Due to the large size of the dataset, we were unable to include the CSV file in the repository. However, you can download the dataset directly from Kaggle:

[Download US YouTube Trending Data](https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset?resource=download&select=US_youtube_trending_data.csv)

Once downloaded, place the CSV file in the project directory and run the Jupyter notebook to replicate the analysis.

## Conclusion

This analysis sheds light on YouTube video performance across different genres, revealing which genres tend to have higher levels of engagement. By examining view counts, like counts, and comment counts, we identified patterns in content performance that can help predict the success of videos based on genre. Although the project faced some data retrieval challenges, the Kaggle dataset proved to be a valuable resource for in-depth analysis. The insights derived from this analysis are crucial for understanding what makes certain video categories more successful on YouTube.
