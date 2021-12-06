Web scraping with Indeed and Craigslist


1. Project Background
There are huge amount of data online, but what data we need and how to accquire them are very challanging. In this project, we use web scraping skills to retrieve and processing data from Indeed and Craigslist. We choose Indeed because it is a very popular for job search. The craigslist web, on the other hand, has many locations around the world and contains data related to our life closely.¶
2. We use python3, requests and beautifulsoup to do web scraping. After that, we store data locally using MySql 8.0.
3. Challenges: 1) the biggest challenge for web scraping is the website's structure, especially when they dislike web scraping with their pages. For example, Indeed changed it's website stucture on October, 2021 and built much more complicated website structures to limit web scraping. 2) Raw data from Internet is not always well structured. And sometime, some parts of data is not available. We need to process raw data and analysis them after we retrieve data from Internet. 3) Indeed and Craigslist, especially Indeed, may change their website in the future to make web scraping more challenging. Or they may prevent us from web scraping totally, like Glassdoor and other websites.
