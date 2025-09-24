📄 Web Scraping Project – Product Data Extraction
📌 Project Overview

This project involves using web scraping techniques to extract product-related data. The goal is to collect specific information from multiple product pages, organize it into a structured format, save it as a CSV file, and perform basic Exploratory Data Analysis (EDA).

🎯 Objectives

Scrape product information from a given website.

Extract relevant details such as product name, price, link, description, and availability.

Store the data in a Pandas DataFrame.

Save the dataset as a CSV file for further analysis.

Conduct basic EDA on the collected data.

🛠 Tools & Libraries

The following Python libraries were used in this project:

requests – for sending HTTP requests to the website.

BeautifulSoup – for parsing and navigating the HTML content.

pandas – for creating and manipulating the dataset.

matplotlib / seaborn – (if used) for basic data visualization during EDA.

🕸️ Data Collection Process

A list of product page URLs was provided. For each URL, the following data points were scraped:

Product Name

Product Price

Product Page Link

Product Description

Availability Status (e.g., In stock / Out of stock)

The scraping logic includes error handling in case any element is missing or not available on the page.

💾 Data Storage

After collecting the data, it was organized into a structured Pandas DataFrame. The DataFrame was then exported to a CSV file (products_data.csv) for future use and analysis.

📊 Exploratory Data Analysis (EDA)

Basic EDA was performed on the CSV data to gain insights, including:

Identifying missing or null values.

Analyzing product availability (in stock vs out of stock).

Overview of product pricing.

Detecting any anomalies or patterns in the dataset.
