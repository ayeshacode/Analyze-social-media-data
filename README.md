Instagram Data Sentiment Analysis
Overview
This project performs sentiment analysis on Instagram data to understand public sentiment towards specific posts. By analyzing the captions of Instagram posts, the project extracts sentiment scores and visualizes trends over time using Natural Language Processing (NLP) techniques.




Objectives
Analyze the sentiment of Instagram captions.
Understand how sentiment correlates with engagement metrics like likes, comments, and shares.
Visualize the distribution of sentiment and trends based on user engagement.
Dataset
The dataset includes Instagram post metrics:




Impressions: Number of views the post received.
Likes, Comments, Shares: User engagement metrics.
Profile Visits, Follows: How many people visited the profile or followed after viewing the post.
Caption: The text accompanying the post, which is used for sentiment analysis.
Hashtags: Hashtags used in each post.
Steps in the Analysis
1. Data Preprocessing
Cleaned the text in captions by removing URLs, non-alphabetical characters, and converting everything to lowercase.
Tokenized the text and removed common stopwords (like "the", "and", "a").
2. Sentiment Analysis
Used the TextBlob library to assign a sentiment polarity score to each caption:
Positive Sentiment: Polarity score > 0.
Negative Sentiment: Polarity score < 0.
Neutral Sentiment: Polarity score = 0.
3. Visualizations
Created visualizations to explore the distribution of sentiment in the dataset.
Analyzed how sentiment correlates with engagement metrics like likes and comments.
Visualizations
a. Sentiment Distribution
A bar chart showing the distribution of positive, neutral, and negative captions.

b. Engagement vs. Sentiment
A bar chart showing the average number of likes for each sentiment category (positive, neutral, negative).

Tools Used
Pandas: For data manipulation and cleaning.
TextBlob: For sentiment analysis.
Matplotlib: For creating visualizations.
Google Colab: For running the analysis.
How to Run This Project
Clone this repository to your local machine:
bash
Copy code
git clone https://github.com/ayeshacode/Analyze-social-media-data.git
Install the required Python libraries:
bash
Copy code
pip install pandas textblob matplotlib
Run the analysis script (analysis.ipynb or analysis.py) in your Python environment or upload the notebook to Google Colab.
Results
Positive posts tend to receive more engagement (likes, comments) compared to neutral or negative posts.
Captions with specific hashtags tend to have a more positive sentiment.
Conclusion
This analysis highlights the importance of sentiment in social media engagement. Understanding how users respond emotionally to posts can help improve marketing strategies and content creation on platforms like Instagram.


