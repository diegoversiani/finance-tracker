# Finance Tracker

This is the finance tracker app from The Complete Ruby on Rails Developer Course

# Functionalities

- Authentication system
  - users can sign-up
  - edit their profile
  - log in / log out
- Stocks
  - Users can search for stock symbols, see its name and current price
  - Users can track stocks - up to 10 stocks per user
  - The user profile page displays all current stock prices
  - Users can choose to add a stock to their portfolio
- Follow
  - Users can look for other users and start following
  - Users can see other users portfolio

# Model Associations

```
User **many_to_many** Stock
User **many_to_many** User(following)
```

# Technologies

- Ruby 2.2.3
- Rails 4.2.6
- Devise 3.5.10
- Twitter Bootstrap (gem)
- Twitter Bootstrap for Devise (gem)
- StockQuote (gem) - for Stock search and prices

# Demo

Running demo at: http://finance-tracker-diegoversiani.herokuapp.com