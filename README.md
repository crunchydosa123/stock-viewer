## Project Layout
This project handle requirements in the following way:
1. Homepage has a search bar. You need to enter a stock name in the search bar and press ENTER or click the search icon. The search bar reveals a list of best matches.
2. You can click one of these. The url for each match is set to '/stock/stockname'. Clicking one of these will take you to the detailed view of each stock.
3. The detailed view of each stock reveals:
  a. Most recent price fetched by the API
  b. Historical chart of the share price
  c. Stock name and ticker
  d. Country of Origin for the company of which the stock is shown
  e. Currency of the stock price
  f. Stock exchange where it is listed
  g. Date of IPO
4. You can further search for stocks in the detailed view as well.

## Dependencies/Libraries
Please go through package.json file and check for dependencies should you wish to fork this repository and run the application. Following are the packages installed using npm as extra other than the ones React comes pre-loaded with:
1. headlessui
2. heroicons
3. testing-library
4. autoprefixer
5. postcss
6. react-router-dom
7. recharts
8. tailwind-css
9. web-vitals

## API
This project uses the finnhub API for fetching stock data. ( https://finnhub.io/docs/api ). While it does return data from all stock exchanges around the world, US data seems to be the most updated. I recommend searching stocks listed on NASDAQ first.

## For cloning/forking
1. Navigate to root/stock-viewer
2. Use npm start
3. Clicking stock names from search bar might take time to respond and route you to the detailed stock view

![image](https://github.com/crunchydosa123/stock-viewer/assets/123110966/69044e59-db8b-4e6a-99c1-e16c5a773cb5)
![image](https://github.com/crunchydosa123/stock-viewer/assets/123110966/1c285335-fd91-4141-8be1-f4ff00dca699)
![image](https://github.com/crunchydosa123/stock-viewer/assets/123110966/d92050c4-76e6-460a-bada-9a1297273113)


