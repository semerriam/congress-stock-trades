# Congress Stock Trades

Data publication and documentation for a project on Congress Members' stock trades and committee assignments


## Project goal

Identify which members of Congress have similarities between their committee assignments and their stock trades.

Some Questions to Answer:
* Which members of Congress have frequent stock trades in industries that committees they are on have jurisdiction over?
* Which members of Congress have stock trades of significant amounts in industries that committees they are on have jurisdiction over?


## Project notes
### Notebooks

* [congress-stock-trades-committees-merge.ipynb](analysis/congress-stock-trades-committees-merge.ipynb) merges Members of Congress' stock trade info with Members' subcommittee assignments using a string algorithm
* [Stock-Watchers-Categories.ipynb](analysis/Stock-Watchers-Categories.ipynb) combines Senate and House Stockwatcher data with stock descriptions from the YFinance Module
* [Congress-Committee-Assignments.ipynb](analysis/Congress-Committee-Assignments.ipynb) extracts each member of Congress' committeee assignments from a nested JSON file 
* [YFinance-scratchpad.ipynb](analysis/YFinance-scratchpad.ipynb) explores the YFinance module to understand the type of information one can access for stock tickers
* [Stock-Watchers-Scratchpad.ipynb](analysis/Stock-Watchers-Scratchpad.ipynb) explores the Stock Watcher data
* [string-algorithms-scratchpad.ipynb](analysis/string-algorithms-scratchpad.ipynb) explores different string algorithms to practice

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
