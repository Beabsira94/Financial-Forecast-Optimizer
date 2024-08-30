# Overview of the dataset
The **Financial News and Stock Price Integration Dataset** (FNSPID) is a big collection of information used to help people predict how the stock market might change. It combines two types of information: **numbers** (like stock prices) and **words** (like news stories). Here’s what’s in the dataset:

1. **headline**: This is the title of a news story, like a newspaper headline. It tells you the important things happening, like a company's stock going up or down.

2. **url**: This is like a shortcut that takes you straight to the full news story if you want to read more.

3. **publisher**: This tells you who wrote or published the news story, like the name of a newspaper or website.

4. **date**: This shows when the news story was published, including the exact time and timezone.

5. **stock**: This is a special code made up of letters that represent a company in the stock market. For example, "AAPL" stands for Apple. 

So, this dataset helps people see how news stories about companies might affect their stock prices!

# Financial News Exploratory Data Analysis (EDA)

This project performs an extensive exploratory data analysis (EDA) on a dataset containing financial news articles. The analysis aims to uncover patterns, trends, and insights within the data that can be valuable for understanding how financial news is distributed and its potential impact on the markets.


## Project Overview

This project is focused on analyzing a dataset of financial news articles. The goal is to explore various aspects of the data, such as headline lengths, publication trends, sentiment analysis, and the contribution of different publishers. By leveraging natural language processing (NLP) and time series analysis, the project seeks to identify important events and trends that could be significant for traders, automated trading systems, and financial analysts.



## Steps carried out during the Exploratory Data Analysis

### 1. Descriptive Statistics

This section provides an initial overview of the dataset by calculating basic statistics and identifying key characteristics:
- **Textual Length Statistics**: The length of headlines is analyzed to understand the distribution of headline lengths. This gives insights into the typical structure of financial news headlines.
- **Article Count per Publisher**: We count the number of articles contributed by each publisher to identify the most active publishers in the dataset.
- **Publication Date Analysis**: Trends over time are analyzed by looking at the frequency of news publications. This helps in identifying any spikes in news frequency on particular days or during specific events.

### 2. Text Analysis (Sentiment & Topic Modeling)

This section leverages natural language processing (NLP) techniques to analyze the content of the headlines:
- **Sentiment Analysis**: Sentiment analysis is performed on the headlines to gauge whether the news articles have a positive, negative, or neutral sentiment. This can provide insights into the overall tone of financial news.
- **Topic Modeling**: Common keywords and phrases are identified using NLP techniques to extract topics or significant events. Keywords like "FDA approval", "price target", "dividend", etc., are tracked to see how often they appear and how they relate to market movements.

### 3. Time Series Analysis

In this section, we explore the time series characteristics of the publication data:
- **Publication Frequency Over Time**: We analyze how the publication frequency varies over time, detecting any spikes in the number of articles that could be related to specific market events.
- **Publishing Time Analysis**: This analysis explores whether there are specific times of the day when most news is released. Identifying such patterns could be valuable for traders and automated trading systems.

### 4. Publisher Analysis

The final section focuses on the publishers themselves and the type of content they produce:
- **Publisher Contribution Analysis**: We identify which publishers contribute the most to the news feed, helping to understand the distribution of financial news across different sources.
- **News Type Differences**: We analyze whether different publishers focus on different types of news or events.
- **Domain Analysis**: If email addresses are used as publisher names, we extract the unique domains to see if certain organizations contribute more frequently.

## Conclusion

The EDA reveals valuable insights into the distribution and content of financial news articles. From identifying active publishers to understanding sentiment and key topics, the analysis provides a comprehensive overview of the dataset, which could be instrumental for financial decision-making and automated trading strategies.

