# Media Production Company Analysis 🎥
_______________________________________________________________________________________________________________________________________________
**1. Introduction**   

The Media Production Company Analysis project aims to analyze audience preferences and opinions using datasets from IMDb, Rotten Tomatoes, and user reviews. The goal is to help Media Production Company, a leading production company in the Northern Hemisphere, understand how different movies are received by the public and how this information can be used to create future projects. The analysis focuses on three key areas:
•	Sentiment Analysis: To determine the overall sentiment (positive, negative, or neutral) of user reviews.
•	Comparative Analysis: To compare user ratings and reviews from IMDb and Rotten Tomatoes.
•	Trend Analysis: To track changes in audience sentiment over time.
The project provides actionable insights that can guide Media Production in making informed decisions about content creation, marketing strategies, and promotional campaigns.
_______________________________________________________________________________________________________________________________________________
**2. Methodology**

Data Collection
The data used in this project was collected from three primary sources:
1.	IMDb:
•	IMDb is one of the world’s most popular and authoritative sources for movie, TV, and celebrity content.
•	Data was collected for more than 500 movies. These movies were selected based on their popularity, critical acclaim, and varied release dates to ensure a diverse dataset.
2.	Rotten Tomatoes:
•	Rotten Tomatoes is a popular review-aggregation website for film and television. It offers both critic and audience ratings for movies.
•	Data for the same 500 movies was extracted from Rotten Tomatoes.
3.	User Reviews:
•	800 user reviews for each of the selected movies were collected from IMDb to analyze user sentiments. These reviews provide a range of opinions, allowing for a comprehensive sentiment analysis.

Data Analysis
The analysis was conducted using the following methods:
1.	Sentiment Analysis:
•	Sentiment analysis was performed on the user reviews collected from IMDb using Microsoft Excel.
•	The goal was to determine the overall sentiment (positive, negative, or neutral) expressed in each review by calculating sentiment scores. This helps in understanding how audiences perceive the selected movies.
2.	Comparative Analysis:
•	User ratings and reviews from IMDb and Rotten Tomatoes were compared using Tableau.
•	This comparison helps in identifying patterns and discrepancies between how movies are perceived by audiences on different platforms. It also provides insights into the differences between audience and critic reviews.
3.	Trend Analysis:
•	Trends in user sentiments were analysed over time using Tableau.
•	This analysis tracks changes in audience sentiment over time, helping to identify shifts in audience perception and preferences. It also highlights how external factors (e.g., streaming release, awards, or critical events) influence audience engagement.

Data Cleaning
Before analysis, the datasets underwent a thorough cleaning process to ensure accuracy and consistency:
1.	IMDb Dataset:
•	Null values were removed, particularly in the gross revenue column.
•	Movie durations were standardized to display numerical values representing minutes.
•	Genres were segregated into main genres and sub-genres for better analysis. However, due to inconsistent null values, sub-genre 2 was removed.
•	The dataset was refined to include only relevant attributes such as movie name, year of release, audience certificate, duration, main genre, IMDb rating, critic score, director, stars, and number of user votes.
2.	Rotten Tomatoes Dataset:
•	The dataset was cleaned to include only relevant attributes, removing unnecessary columns.
•	This ensured that the dataset was streamlined for comparative analysis with IMDb data.
______________________________________________________________________________
**3. Findings**
  	
The findings from the analysis are presented through Tableau visualizations and include the following key insights:
 Positive and Negative Audience Engagement
•	The analysis of audience sentiment trends over time revealed fluctuations in positive and negative reviews.
•	Significant shifts in sentiment were observed around key events such as streaming releases, awards, and critical.
 Negative and Positive Reviews Over Time
•	The number of positive and negative reviews was tracked over time for the selected movies.
•	Positive reviews peaked during the streaming release and the pandemic, while negative reviews stabilized post-pandemic.

Sentiment Distribution for Three Genres
•	Sentiment distribution across various genres was analysed.
•	Drama and comedy genres elicited the highest proportion of positive sentiment, while action had a more balanced distribution of positive and negative reviews.

IMDb and Rotten Tomatoes Ratings
•	A comparison of ratings from IMDb and Rotten Tomatoes revealed that IMDb users tend to Favor Warner Bros. productions, while Rotten Tomatoes critics prefer Lionsgate and 20th Century Fox productions.
•	This insight can help Media Production Company tailor its marketing strategies to different audience segments.

Positive Keywords Distribution
•	Commonly used positive keywords in user reviews were identified.
•	These keywords reveal key themes and elements that resonate well with audiences, helping Salt Productions prioritize content that aligns with audience preferences.
______________________________________________________________________________
**4. Conclusion**

The Media Production Company Analysis project provides valuable insights into audience preferences, engagement trends, and sentiment distribution across different genres and platforms. The key findings and recommendations are as follows:

Key Insights:
•	Audience Engagement Trends: Sentiment trends fluctuate over time, influenced by factors such as release timing, critical events, and streaming availability.
•	Genre Preferences: Drama and comedy genres elicit the highest proportion of positive sentiment, while action has a more balanced distribution.
•	Platform Preferences: IMDb users prefer Warner Bros. productions, while Rotten Tomatoes critics favor Lionsgate and 20th Century Fox productions.

Recommendations:
•	Content Strategy: Media Production Company should focus on genres with higher positive sentiment (e.g., drama and comedy) and diversify content partnerships to cater to different audience segments.
•	Marketing Campaigns: Tailor promotional campaigns to specific audience segments based on their preferred rating platforms (e.g., IMDb or Rotten Tomatoes).
•	Continuous Monitoring: Regularly monitor audience sentiment and adapt strategies to shifting preferences and market dynamics.
•	Content Acquisition: Prioritize acquiring rights to movies that align with positive audience sentiments and avoid elements that are less favoured by viewers.

