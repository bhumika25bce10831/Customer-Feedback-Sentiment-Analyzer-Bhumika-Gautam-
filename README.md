# Customer-Feedback-Sentiment-Analyzer-Bhumika-Gautam-Customer Feedback Sentiment Analyzer

(Beginner-Friendly Project with Simple UI + SQLite Database)

This project is a beginner-friendly Customer Feedback Sentiment Analyzer built with Python Tkinter for UI and SQLite for the database.
It analyzes user feedback as Positive, Negative, or Neutral using TextBlob and stores the results locally.


---

 Features

 Very simple and beginner-friendly Python code

 Clean Tkinter GUI with one input box

 Uses SQLite (no installation needed)

 Stores feedback + sentiment in feedback.db

 Uses TextBlob for easy sentiment analysis

 Runs perfectly on Jupyter Notebook, VS Code, PyCharm

 No ML training required



---

 Project Structure

 Sentiment-Analyzer-SQLite/
│── sentiment_app.py           # Main application
│── feedback.db                # Auto-created SQLite database
│── README.md                  # Documentation
│── flowchart.png              # (Optional) Flowchart image
│── report.pdf                 # (Optional) Final project report


---

 Technologies Used

Component	Technology

Programming	Python
UI	Tkinter
Sentiment Analysis	TextBlob
Database	SQLite
Platform	Works on all OS (Windows/Linux/Mac)



---

 SQLite Database Setup

No setup required!

The Python code automatically:

Creates feedback.db

Creates a table feedback

Inserts all results into it


SQL used:

CREATE TABLE IF NOT EXISTS feedback (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    user_feedback TEXT,
    sentiment TEXT
);


---

 Sentiment Analysis Logic

We use TextBlob polarity score:

Polarity > 0 → Positive

Polarity < 0 → Negative

Polarity = 0 → Neutral


Perfect for beginners because it's very easy and accurate enough.


---

 How to Run

1. Install dependencies

pip install textblob
python -m textblob.download_corpora


---

2. Run the project

python sentiment_app.py


---

 How the App Works

1. User enters feedback in the input box


2. Press “Analyze Sentiment”


3. Program calculates Positive / Negative / Neutral


4. Result appears on the screen


5. Feedback + sentiment is saved in SQLite database




---

 Flowchart

(Attach your generated flowchart here; text version below)

Start 
 ↓
Open Tkinter UI 
 ↓
User enters feedback 
 ↓
Analyze sentiment using TextBlob 
 ↓
Store (feedback + sentiment) in SQLite 
 ↓
Display result on UI 
 ↓
End


---

 Example Input & Output

Input Feedback	Sentiment

"I love this!"	Positive
"This is bad"	Negative
"It is okay"	Neutral



---

 Why SQLite Version Is More Beginner Friendly?

No database installation

No server setup

Works offline

Runs instantly

Perfect for college mini-projects



---

 Future Enhancements (Optional)

Add a history page to view all saved feedback

Add graphs and charts

Export analytics to PDF

Add login system

Add mobile UI (Kivy)
