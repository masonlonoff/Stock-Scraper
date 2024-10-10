# Stock-Scraper

This repository is the first step in a project that will create a bot that will notify its users based stock movements. The motivation for this project lies simply in convenience. I have found it difficult to keep up with stock market movements consistently. Too often for my liking, I'm not aware certain companies have taken large market cap hits. At the very least, I wish to be aware of these nosedives so I can conduct further analysis. This project will track intraday moves as well as movements over a larger period of time. For example, I want the bot to notify me when a stock has dropped 25% off of it's all time and 52 week high. 

I want the bot to track the information of the large-cap and mega-cap stocks. 

The first step in the project is to create my list of stocks I wish to track. I am doing that by scraping them from:
1. https://stockanalysis.com/list/mega-cap-stocks/
2. https://stockanalysis.com/list/large-cap-stocks/

The lone code in this repository is a scraping program which pulls in the tickers that I want to track. 


#### Next Steps

I will use these tickers as my filter for the live financial information I pull. I will most likely use yahoo finance to pull real time price data. I will calculate percent changes over intra-day highs, and also calculate percent changes from the 52 week high, 3 month high, 1 month high, and 1 week high. Most likely I will want to send a single email out at the end of the day with any of the prices changes that meet the bot's requirements.


#### Stretch Goal

Since the list I'm scraping from is dynamic. I want to be notified if a stock drops off the large cap list, or if a new stock gets added to the list
