# CryptoPrices_Crawler

### WHAT  
The code can
1. retrieve coin prices by day/hour/minute from https://www.cryptocompare.com/api/ , and
2. extract finance features like movingAverage/RSI/change/exchanges from retrieved data.  


### HOW   
1. data retrieving: python ./lib/get_prices.py  
   Find features at ./data/features/
2. feature extracting: python ./lib/get_features.py  
   Find pricecs at ./data/prices/