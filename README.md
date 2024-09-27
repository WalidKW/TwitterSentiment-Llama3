# <span style='color:dodgerBlue; font-weight:bold;'> Twitter Sentiment Analysis using LLM </span>

![Twitter](https://www.aimtechnologies.co/wp-content/uploads/2024/01/Twitter-Sentiment-Analysis.png)

### <span style='color:aqua; font-weight:bold;'> Project Context: </span>

In this project, we aim to explore the sentiments and opinions of people in Gaza, as expressed on social media, specifically Twitter. The focus is to gather real-time tweets, process and clean the data, and perform sentiment analysis. The insights gained can help better understand the prevailing mood, attitudes, and general discourse around specific topics related to Gaza, including social, political, and humanitarian issues.

<b>The project involves the use of the following technologies:</b>

* **Twitter Scraping**: Selenium is used to scrape real-time tweets, targeting specific hashtags and topics, due to limitations with paid APIs.
* **Data Cleaning**: Python is employed to clean the scraped data by removing unwanted symbols, URLs, and filtering the text.
* **Sentiment Analysis and LLM Integration**: Groq’s LLM, particularly the llama3-70b-8192 model, is integrated to conduct sentiment analysis and provide real-time question-answering capabilities on the collected tweets, enabling a deeper understanding of the data.

The goal is to provide meaningful insights into the feelings and reactions of individuals in Gaza based on public social media posts, which could support researchers, humanitarian organizations, and policymakers in understanding the sentiment landscape.

<b>Key Components:</b>

1. **Data Collection**: Tweets are scraped using Selenium, focusing on specific hashtags and topics.
2. **Data Cleaning**: Removing unwanted symbols, URLs, and filtering English texts to ensure clean and usable data.
3. **Sentiment Analysis & LLM Integration**: Using Groq’s LLM to perform sentiment analysis and answer questions about the data simultaneously.
4. **Insights**: The resulting sentiment analysis provides critical insights into public opinions, which could support researchers and humanitarian organizations.
