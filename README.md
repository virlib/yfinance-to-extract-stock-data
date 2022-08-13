# yfinance-to-extract-stock-data

Extracting essential data from a dataset and displaying it is a necessary part of data science. 

In this project, I extract and plot price and revenue graphs of two famous stocks: `Tesla` and `GameStop`.

First, I use ticker objects to extract date and closing value of the stocks.

Then, to extract the stocks revenue data, I webscrape these two websites: [website1 for tesla](https://www.macrotrends.net/stocks/charts/TSLA/tesla/revenue?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkCoursesIBMDeveloperSkillsNetworkPY0220ENSkillsNetwork23455606-2022-01-01) and [website2 for GameStop](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/stock.html)

In the end, I plot the stock data graph using a fuction make_graph which plots two graphs:
<li> one with date and the stock closing value </li>
<li> second with date and stock revenue </li>
