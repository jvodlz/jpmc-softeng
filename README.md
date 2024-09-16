# Background
Project is built on JPMorgan Chase's Perspective data visualisation software, which is open source. 

My objectives were to add a chart to a trader’s dashboard allowing them to better identify under/over-valued stocks. This was broken down to three tasks. A patch was created per task.

## Use Case
The trader would like to be able to monitor two historically correlated stocks and be able to visualise when the correlation between the two weakens (i.e. one stock moves proportionally more than the historical correlation would imply). This could indicate a potential trade strategy to simultaneously buy the relatively underperforming stock and sell the relatively outperforming stock. Assuming the two prices subsequently converge, the trade should be profitable.

# Set-up
- Run `npm install` to install dependencies

# Getting Started
- To start the data server, use `python datafeed/server3.py` (from root directory)
- After the server is running, use `npm start` to run the app