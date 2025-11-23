1. Problem Statement

Many organizations collect customer feedback, but manually analyzing each comment to understand customer
satisfaction is time-consuming and inefficient. There is a need for an automated tool that can quickly classify
feedback into positive, neutral, or negative sentiment. This helps businesses understand customer experience and
make improvements efficiently.

2. Scope of the Project

This project focuses on building a Customer Feedback Sentiment Analyzer with the following characteristics:
Uses Python for backend processing.
Uses Tkinter to provide a simple graphical user interface (UI) for entering customer feedback.
Utilizes TextBlob for basic sentiment analysis.
Stores feedback and results in a lightweight SQLite database (no MySQL).
Displays sentiment results instantly to the user.
Suitable for academic mini-projects and beginner portfolios.

The project does NOT include:
Machine learning model training.
Advanced UI design.
Cloud database or deployment.

3. Target Users

This project is intended for:
Small businesses who want a simple local system for analyzing customer feedback.
Anyone who needs a quick tool to analyze short customer comments.

4. High-Level Features

 1. Simple User Interface (Tkinter)

Text box to enter feedback
Button to analyze feedback
Area to display positive/neutral/negative result


 2. Automatic Sentiment Analysis

Uses TextBlob to compute polarity

Classifies text into:
Positive
Neutral
Negative


 3. SQLite Database Integration

Stores:
User feedback
Sentiment result
Timestamp
Allows retrieving or analyzing past feedback if needed.
