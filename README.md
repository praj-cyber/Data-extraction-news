# Data-extraction-news
Project Overview:
This application collects news articles from various RSS feeds, stores them in a database, and categorizes them into predefined categories.
Libraries Used:
feedparser: Parses RSS feeds.
SQLAlchemy: Manages database interaction.
Celery: Handles asynchronous task queues.
NLTK: For natural language processing.

Feed Parser and Data Extraction:
Reads RSS feeds.

Extracts and stores article data in a database.

Ensures no duplicates.

Database Storage:
Designed schema with SQLAlchemy.

Stored new articles in a PostgreSQL database.

Task Queue and News Processing:
Set up Celery for managing task queues.

Classified articles into categories using NLTK.

Logging and Error Handling:
Implemented logging to track events.

Managed errors gracefully.

Steps to Run the Application:
Set up your PostgreSQL database.

Install necessary libraries: feedparser, SQLAlchemy, Celery, NLTK.

Run the feed parser script.

Start Celery worker.

Monitor logs for any errors.

Data Output:
Articles stored in PostgreSQL.

Categorized data can be exported as SQL dump, CSV, or JSON.
