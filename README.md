# 📚 Books Web Scraping using Python

## 📌 Project Overview

This project demonstrates how to scrape book information from the
[Books to Scrape](https://books.toscrape.com/) website using Python.

The project collects book data from multiple pages and stores the
extracted information in a CSV file for further analysis.

## 🎯 Objective

The main objective of this project is to practice web scraping
and learn how to:

- Send HTTP requests to a website
- Parse HTML content
- Extract specific information from web pages
- Store scraped data in a structured format
- Export the data into a CSV file

## 📊 Data Collected

The following information is extracted for each book:

| Column | Description |
|---|---|
| Name | Name of the book |
| Link | Link of the book |
| Price | Price of the book |

## 🛠️ Technologies & Libraries

- Python
- Requests
- BeautifulSoup
- Pandas

## 🔄 Project Workflow

```text
Website
   ↓
Requests
   ↓
HTML Response
   ↓
BeautifulSoup
   ↓
Extract Book Information
   ↓
Python List
   ↓
Pandas DataFrame
   ↓
CSV File

