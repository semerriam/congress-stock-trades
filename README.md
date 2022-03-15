# Congress Stock Trades

This project is intended to   

combines data from Stock Watcher


Senate Stock Watcher API: https://senatestockwatcher.com/api House Stock Watcher API: https://housestockwatcher.com/api


on the demographic and educational attainment differences between public school districts in Essex County and the distances between these districts. The two-week exploration of primarily Mass. DOE, NCES, and ACS data required merging over 20 datasets and using a variety of tools to analyze and explore the data graphically. Highlights included looking into historical documents about busing in the 70's and learning how to calculate and code the Haversine formula. Additionally, historical data aggregated by the Boston Regional Metropolitan Planning Organization was used to compare incomes between towns.


## Project goal

Identify which members of Congress have similarities between their committee assignments and their stock trades 

## Project notes
### Notebooks

* [congress-stock-trades-committees-merge.ipynb](analysis/congress-stock-trades-committees-merge.ipynb) merges Members of Congress' stock trade info with Members' subcommittee assignments using a string algorithm
* [Stock Watchers-Categories.ipynb](analysis/Stock Watchers-Categories.ipynb) combines Senate and House Stockwatcher data with stock descriptions from the YFinance Module
* [YFinance.ipynb](analysis/YFinance.ipynb) explores the YFinance module to understand the type of information one can access for stock tickers
* [Congress-Committee-Assignments.ipynb](analysis/Congress-Committee-Assignments.ipynb) extracts each member of Congress' committeee assignments from a nested JSON file 
* [string-algorithms-scratchpad.ipynb](analysis/string-algorithms-scratchpad.ipynb) explores using different string algorithms

### Data sources

* Senate Stock Watcher API: https://senatestockwatcher.com/api 
* House Stock Watcher API: https://housestockwatcher.com/api
* Yahoo Finance data via YFinance Ticker Module: https://pypi.org/project/yfinance/
* Committee Assignments: https://theunitedstates.io/congress-legislators/committee-membership-current.json
* Committee Descriptions: Handmade dataset from committees' .gov sites with some exceptions
* Global Industry Classification Standard (GICS) https://www.msci.com/our-solutions/indexes/gics


## Technical

*TBD*


## Data notes

*TBD*
