# trAIder

ETF trading strategy analyzer based on Yahoo Finance data.

Built with Node.js/Express for the back-end and React for the front-end.

Designed using MVC architecture.

## Prerequisites
1. Python installed
2. Node installed (v 18)

## How to run
1. Open a terminal
2. Move into trAIder/src/server and run 'npm i' then 'npm start' to start the Nodejs/Express server.
3. Open a second terminal
4. Move into trAIDer/ and run 'npm i'. Then, 'npm run build'. This will create a client build. Then 'npm start' to start the client. A browser tab will be automatically created.

## Features
1. Ability to download the historical data of FNGU and FNGD for the past three years between
01/01/2020 and Yesterday from Yahoo Finance and save them in JSON format on a server. The downloaded data includes Date, Open, High, Low, Close, and Volume.
2. User interface (GUI) for that displays the data from the saved data and draws a graph for the selected symbol (either FNGU or FNGD) and date period.
3. Implements two trading strategies (a) Moving Average Cross-over and (b) Bollinger
Band Bounce.
4. The initial balance of the trading account will be $ $100,000$. Implements a simple backtesting method to calculate the total gain or loss from every trade for the selected period and displays
the final performance of each trading strategy in terms of total $ return and % return,
assuming the trading fee is zero (free).

## Credits

Mike Ball | Salvador Felipe | Christian Mendez | Gilberto Espino Solis | Nick Viste

Everyone contributed equally
