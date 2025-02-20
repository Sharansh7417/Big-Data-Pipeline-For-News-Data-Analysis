# 🌐 News Scraper & Spark Word Count 📊

## 🚀 Project Overview

Welcome to the News Scraper & Spark Word Count project! 🎉

This project scrapes news articles from multiple websites, process the text with Apache Spark, and find out the most trending topics based on the most frequent words. It’s perfect for identifying hot topics in the world right now!

Here’s what this project does:

- Scrapes news articles from multiple sources .
- Saves the scraped data in HDFS (Hadoop Distributed File System).
- Processes the data using Apache Spark to perform a word count (a.k.a. trending topics).
- Outputs the results back into HDFS for easy access.
- Let’s get started with scraping some news and counting those words!

## 💡 Technologies Used

This project is powered by:

- *Python*: For scraping the web and processing the data.
- Apache Spark: For running the data processing in a distributed environment.
- Hadoop HDFS: For storing the scraped data and results.
- BeautifulSoup: For scraping the web pages.
- Requests: For sending HTTP requests to fetch news articles.
- PySpark: For running Spark jobs in Python.

🛠️ Prerequisites

Before running the project, you will need the following software installed:

- Python 3.x
- Apache Hadoop (HDFS)
- Apache Spark (for data processing)
- Java 8+ (required for Spark)
- pip (Python package installer)
