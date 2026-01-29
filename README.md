# Sentiment Analysis Web Application

This practice project is a Flask-based web application that performs sentiment analysis on user-provided text using an external NLP API. It sends the input text to the Watson NLP sentiment analysis service, processes the response, and displays the sentiment label along with its confidence score.


# Project Overview

The application consists of:

	•	A sentiment analysis function that communicates with an external API.
	•	A Flask server that exposes an endpoint for analyzing text.
	•	A simple web interface to interact with the system.

The system identifies whether the given text has a positive, negative, or neutral sentiment and returns the corresponding score.

# Project Structure
- final_project/
  - SentimentAnalysis/
    - __init__.py
    - sentiment_analysis.py
  - templates/
    - index.html
  - server.py
  - requirements.txt
  - README.md

# Technologies Used
	•	Python 3.x
	•	Flask
	•	Requests
	•	JSON
	•	Watson NLP Sentiment API

# How the Code Works

# Sentiment Analyzer Function
	•	Sends text to the Watson NLP API.
	•	Extracts sentiment label and score.
	•	Handles API errors by returning None.

# Flask Endpoint (/sentimentAnalyzer)
	•	Accepts text as a query parameter.
	•	Calls the sentiment analyzer function.
	•	Formats and returns the result.


  
