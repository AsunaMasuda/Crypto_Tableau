# Self-Updating Cryptocurrency Daily Chart with Tableau
Visualization project of live (daily updated) Cryptocurrency data with Tableau. The data gets updated everyday automatically.
You can find the visualization at Tableau Public: [Here](https://public.tableau.com/profile/asuna.masuda#!/vizhome/Auto-updatedCryptocurrencyDailyChart/Crypto_Dash)

<p align="center"><img src = "https://github.com/AsunaMasuda/Crypto_Tableau/blob/master/tableaulogo_highres.png" width=500></p>

## Overview
- Visualised cryptocurrency historical tradings data (Bitcoin, XRP, Ethereum) with Tableau using API provided by [CryptoCompare](https://www.cryptocompare.com/). CryptoCompare provides a free API where users can request 100,000 times per month for various types of cryptocurrency. 
- The API data is dumped as JSON format. By using Google Sheet App Scripts it was imported to Google Sheets as tabular data, also was setted up to automatically upload the newest trading data everyday.

## Reference 
- Google App Script (JavaScript) for converting JSON file to Google sheet using API ([Github repo](https://github.com/bradjasper/ImportJSON))
- Google App Sript to renew data per certain interval [DATA MASHUP](https://datamashupblog.wordpress.com/)
- Top 5 Free APIs to access historical cryptocurrencies data [Blog](https://blog.rmotr.com/top-5-free-apis-to-access-historical-cryptocurrencies-data-2438adc8b62)
