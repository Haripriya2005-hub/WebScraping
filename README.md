# Java Web Scraper - Product Information Extractor

## Overview
This Java program scrapes product information (name, price, rating) from the demo e-commerce site [Books to Scrape](http://books.toscrape.com/) using Jsoup and saves the data into a CSV file (`products.csv`).

## Requirements
- Java 8 or higher
- Jsoup library (version 1.15.4 used here)

## How to Run

### If using Maven:

1. Add Jsoup dependency to your `pom.xml`.
2. Compile and run the `WebScraper.java`.

### If not using Maven:

1. Download Jsoup jar from [https://jsoup.org/download](https://jsoup.org/download)
2. Compile with:

```bash
javac -cp jsoup-1.15.4.jar WebScraper.java
