Travel Chat-based Flight Recommendation System

This project is a chat-based flight recommendation system for a travel agency, designed to provide personalized flight suggestions based on user preferences. The system leverages natural language processing (NLP) techniques and scoring algorithms to analyze customer preferences and reviews, delivering tailored recommendations for an enhanced customer experience.


Table of Contents

	1.	Project Overview
	2.	Features
	3.	Setup Instructions
	4.	How It Works
	5.	Technologies Used
	6.	Example Usage
	7.	Future Improvements
	8.	License

 Project Overview

The Travel Chat-based Flight Recommendation System engages users in an interactive conversation to understand their travel preferences, including departure and destination cities, preferred airlines, travel class, and the importance of specific flight attributes. It uses this information to filter flights, calculate preference scores, analyze user sentiment from reviews, and recommend the best options.

Features

	•	Interactive Chat Interface: Guides users through questions about their travel preferences.
	•	Data Cleaning: Ensures high-quality data by filtering verified reviews and removing incomplete records.
	•	Flight Filtering: Matches flights based on user preferences such as departure city, destination, airline, and travel class.
	•	Preference Scoring: Weighs key attributes (e.g., seat comfort, inflight entertainment) according to user rankings.
	•	Sentiment Analysis: Evaluates reviews using sentiment scores to enhance recommendation accuracy.
	•	Visualizations:
	•	Airline popularity histogram.
	•	Word cloud of popular departure cities.
	•	Final Recommendations: Provides the top 5 flight recommendations with scores and details.


 How It Works

	1.	Data Preprocessing:
	•	Cleans and filters data to include only verified reviews and valid routes.
	•	Maps airport codes to city names.
	2.	User Interaction:
	•	Collects user preferences through an interactive chat interface, including:
	•	Departure and destination cities.
	•	Preferred airline and travel class.
	•	Importance ranking of flight attributes.
	3.	Flight Filtering and Scoring:
	•	Filters flights based on user inputs.
	•	Scores flights by combining user preference weights and sentiment scores from reviews.
	4.	Sentiment Analysis:
	•	Uses NLTK’s SentimentIntensityAnalyzer to process customer reviews and calculate sentiment scores.
	5.	Recommendation:
	•	Ranks flights based on total scores (preference and sentiment).
	•	Returns the top 5 flight options along with their details.
	6.	Visualization:
	•	Generates visual insights like popular airlines and departure cities using histograms and word clouds.


 Technologies Used

	•	Python: Core programming language.
	•	pandas: Data manipulation and analysis.
	•	NLTK: Sentiment analysis and text processing.
	•	Matplotlib & Plotly: Visualization of trends and insights.
	•	WordCloud: Visualization of popular departure cities.


 Future Improvements

	•	Enhanced NLP:
	•	Incorporate advanced sentiment analysis models like BERT or GPT for better sentiment scoring.
	•	Flight Data Updates:
	•	Integrate real-time flight data via APIs from sources like Amadeus or Skyscanner.
	•	Multi-Language Support:
	•	Add language options to cater to a broader audience.
	•	User Preferences:
	•	Save user profiles for personalized recommendations in future sessions.
