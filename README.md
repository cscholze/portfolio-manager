#stock-market-manager
Project to use MarketOnDemand API to manage a stock portfolio.

* pg1. Input form to get stock quotes by symbol.
* pg2. Get quotes should have link to page with more details about company
 - Company
 - Last price
 - 'Buy' button with input for quantity of shares
* pg3. Portfolio Page
 - show all stocks you've bought in table with headers (symbol, company,
   current price, quantity)
 - Portfolio value (total value of all shares of all stocks)
 - 'get new quote' link
* pg.4 Sell function...stock and quantity

# Planning
* What kind of data do I need to store?
* What will my data look like?
* What type of routes will I expect? (GETs and POSTs)
  - pg1: GET /quote
  - pg2. GET /quote/<symbol>, maybe a query parameter
  - pg3. GET / or GET /protfolio
  - POST /buy


# Development and Deployment
* To deploy the heroku app on localhost:5000, and you have already
  installed the heroku cli usei

## To preview heroku app on localhost
`$ heroku local dev`
and navigate browser to localhost:5000

## To preview heroku app on web
`$ heroku open`

## To deploy app locally with node
`$ npm start`
and navigage browser to localhost:3000
