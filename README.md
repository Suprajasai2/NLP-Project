# NLP-Project
    Sentiment Analysis on TripAdvisor Reviews 
Introduction: 
In the realm of travel, hotels play a pivotal role, and with the abundance of information available, new avenues for selecting the best accommodations have emerged. Reviews, often considered the bedrock for evaluating product quality, serve as a crucial determinant in the decision-making process. While platforms like Amazon and YouTube employ scaled rating systems, Tripadvisor takes a nuanced approach. In this project, we aim to perform sentiment analysis on Tripadvisor hotel reviews for the city of New Delhi. This analysis seeks to provide valuable insights to both consumers and business owners, offering a nuanced understanding of the sentiments expressed in the reviews.
Project Context: 
The hospitality and tourism industry heavily relies on customer feedback to gauge satisfaction levels and identify areas for improvement. TripAdvisor is one of the largest platforms for travel-related reviews, hosting millions of reviews covering a vast array of destinations and establishments worldwide. Analyzing sentiments expressed in these reviews can provide valuable information to businesses, enabling them to enhance customer experience, address issues promptly, and make informed decisions based on customer feedback.
Problem Statement: 
The primary objective of this project is to develop a robust sentiment analysis model capable of categorizing TripAdvisor reviews into predefined sentiment categories (Poor, Good, Excellent). The model will be trained using a labeled dataset of TripAdvisor reviews sourced from Kaggle, where each review is associated with a sentiment label. The key challenges and goals of this project include:
Text Preprocessing: Cleaning and preparing textual data to ensure optimal model performance.
Exploratory Data Analysis: Conducting an exploratory data analysis (EDA) to  uncover interesting insights within the dataset.
Feature Extraction: Extracting meaningful features from text for sentiment analysis.
Model Development: Implementing and fine-tuning machine learning models to accurately classify reviews based on sentiment.
Performance Evaluation: Evaluating model performance using appropriate metrics like accuracy, precision, recall, and F1-score.
Interpretation and Insights: Gaining actionable insights from sentiment analysis results to assist businesses in making data-driven decisions.


Data Source and Data Description:
The dataset from kaggle contains 9 attributes and 148448 entries. The attributes are as below:	
●  parse_count: Auto incremental index of the web scraper.
●  restaurant_name: The name of the restaurant associated with the review.
●  rating_review: Integer review score within the range [1-5].		
●  sample: String representing "positive" samples [4-5] and "negative" ones [1-3].
●  review_id: A unique identifier for each review. 		
●  title_review: The title of the review.		
●  review_preview: A truncated preview of the review, often displayed on the website when the full text is very long.
●  review_full: The complete review text.
●  date: Timestamp indicating the publication date of the review in the format (day, month, year). 
 												 Key Features:
Review Text (review_text): Contains the main content of the review provided by the user.
Rating (rating): Represents the numerical rating given by the user, reflecting their experience.
