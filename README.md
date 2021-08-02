MonteCarlo Simulation 

This is a review of portfolio data using historical pricing data from Alapaca to simulate what the future value of the portfolio may be. The returns were simulated over a 30 year period and a 10 year period.
The results were also graphed for visualization. The MonteCarlo simulation was provided via a Python file which provided the instructions for how the simulation was to be run. This was imported to the jupyter notebook file to run the simulation 





---

## Technologies
This application is written in Python 3.7

this application uses the following packages:
Json - 
pandas
load_dotenv
alpaca_trade_api
MCForecast tools


---

## Installation Guide

Before running the application first install the following dependencies.

python
  pip install json
  pip install pandas
  
Alpaca needs to be signed up for and a two keys created the regular key and the secret key
a .env file also needs to be created to store you ALPACA_API_KEY, and ALPACA_SECRET_KEY which is then imported into the notebook via load_dotenv
MCForecast tools which houses the instructions for the Montecarlo Simulation also needs to be imported 

---

## Examples

![alt text](C:\Users\seanp\OneDrive\Documents\Lightshot\cumulative returns 10yr.png)

![alt text](C:\Users\seanp\OneDrive\Documents\Lightshot\cumulative returns 30yr.png)

---

## Usage

To use the loan qualifier application simply clone the repository.

Values can be changed to tweak the results. The main variables to be changed that will change the outcome are spy_shares and agg_shares

The time period can also be changed on the Montecarlo simulation as was done in the challenge.
Also the amount of time for the historical data can be changed by adjusting the time frame in the start_date and end_date variables 
```
---

## Contributors

Sean Patel (myself) seanpatel076@gmail.com
---

## License

License is public anyone can use or make changes to this application 
