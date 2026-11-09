# Proposal

## What will (likely) be the title of your project?

StockSim
## In just a sentence or two, summarize your project. (E.g., "A website that lets you buy and sell stocks.")

A full-stack web application that simulates stock, trading without financial risk: useers get $10,000 in virtual cash and can look up real stocks prices, buy and sell shares, and track their porfolio.
## In a paragraph or more, detail your project. What will your software do? What features will it have? How will it be executed?
StockSim is a full-Stack web application that lets people practice trading stocks without risking real money. Each new user registers with a username and password and receive $10,000 in virtual cash. Users can search for any stock by ticker symbol(e.g. AAPL, TSLA, MSFT) and see its current price, which the app retrieve from an external financial data API such as Alpha Vantage or Yahoo Finance. If a user has enough cash, they can buy shares, and they can sell shares they already own. Every trade upduates the user's cash balance and holdings. 
## If planning to combine 1051's final project with another course's final project, with which other course? And which aspect(s) of your proposed project would relate to 1051, and which aspect(s) would relate to the other course?

N/A
## If planning to collaborate with 1 or 2 classmates for the final project, list their names, email addresses, and the names of their assigned TAs below.

N/A, I'm working alone.
## In the world of software, most everything takes longer to implement than you expect. And so it's not uncommon to accomplish less in a fixed amount of time than you hope.

### In a sentence (or list of features), define a GOOD outcome for your final project. I.e., what WILL you accomplish no matter what?

A working Flask web app where a user can register, log in, look up a stock's current prices, and buy and sell shares, with cash, holdings, and trades saved in SQlite database. 
### In a sentence (or list of features), define a BETTER outcome for your final project. I.e., what do you THINK you can accomplish before the final project's deadline?

Everything in GOOD, pkus a portfolio page(shares held, current price, value per holding cash, and total account value), a transaction history page, and clear validation and error messages for every failure case. 

### In a sentence (or list of features), define a BEST outcome for your final project. I.e., what do you HOPE to accomplish before the final project's deadline?

Everything in betterm plus extras like a price chart for each stock, profit and loss shown per holding, a leaderboard comparing user's account values, and a clean, mobile-friendly design 
## In a paragraph or more, outline your next steps. What new skills will you need to acquire? What topics will you need to research? If working with one of two classmates, who will do what?

I need to learn Flask,(routes, temples, forms and sessions) how to use SQLit and SQL from python to storer users, holding and transactions, and basic HTML and CSS to build the pages. I also need to research how tto get stock prices from an external API(including getting an API ley and handling errors or rate limites), how to hash passwords securely, and how to validate user input.My first step is to build the simplest version: register, log in. Then I'll add buying and selling, then portgolio and transaction history pages, and finish with extras like charts and the leaderboard. I'm working alone. So I'll do all of the work my self and plan to ask my professor or TA when I get stuck or need some guidance.
