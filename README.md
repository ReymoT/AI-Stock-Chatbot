
The script requires an older version of the OpenAI API, which can be installed by using `pip install openai==0.28`. The API key should be stored in .venv/API_KEY text file.
All financial data is fetched from Yahoo Finance using the yfinance module.

Program is executed by navigating to the directory and running `streamlit run main.py`

The chatbot provides the following stock technical analysis indicators:
* Simple Moving Average
* Exponential Moving Average
* Relative Strength Index
* Moving Average Convergence/Divergence
* Plot Stocks
* Get Latest News Relating to the Stock
