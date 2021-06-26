# CarbonExt

## Value proposition

As highlighted in this recent report [Net Zero: The Next Frontier for Corporate Sustainability](https://cbey.yale.edu/research/net-zero-the-next-frontier-for-corporate-sustainability), a publicly-available, free, updated, and consolidated database on GHG emissions of corporates is not available over the Internet. 
How can we expect consumers, private investors and employees to favor environmentally-friendly companies when a metric, as simple as GHG emissions, is not immediately available? I also believe this lack of public database is slowing down the development of applications and businesses that promote the decarbonization of the economy.

This project has the following goals:

* Explore ways to systematically gather GHG emissions data
* Build a free-of-use database of corporate GHG emissions
* Provide data visualization to inspire the general public to contribute to the acceleration of the decarbonization of he economy.


## Prototype

* A set of interactive visualization using S&P 100 GHG emission database provided in the report  [Net Zero: The Next Frontier for Corporate Sustainability](https://cbey.yale.edu/research/net-zero-the-next-frontier-for-corporate-sustainability)
* one animation that could be exported in a GIF file

## Tools
### Programming Language
The project will mainly be developed in Python as it contains great libraries for data scientists

### Database
Initially we'll use a simple .csv file. If the project scales, we will consider other options (e.g. SQL)

### Dashboard
Dash - plotly seems to be the most appropriate tool for the project. Streamlit was also considered but aesthetics and speed seem superior in Dash.

## Step-by-Step learning

1. Learn about dash + plotly
2. Implement one visualization (without database import)
3. Implement one visualization (with database import)