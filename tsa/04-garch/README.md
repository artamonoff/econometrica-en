# Time-Varying Volatility Models

## Data Sources

* [`FRED`](https://fred.stlouisfed.org)
* [`Yahoo Finance`](https://finance.yahoo.com)

## Required Python Libraries

|Library|Description|
|-|-|
|[`pandas`](https://pandas.pydata.org)|Tabular data|
|[`numpy`](https://numpy.org)|Working with data arrays, data transformation|
|[`yfinance`](https://github.com/ranaroussi/yfinance)|Downloading data from `finance.yahoo.com`|
|[`pandas-datareader`](https://pandas-datareader.readthedocs.io/en/latest/)|Loading data from external databases (`FRED`, `finance.yahoo.com`, etc.)|
|[`arch`](https://arch.readthedocs.io/en/latest/index.html)|Time series tests and models|
|[`sktime`](https://www.sktime.net/en/stable/index.html)|Framework for time series analysis|
|[`scipy.stats`](https://docs.scipy.org/doc/scipy/reference/stats.html)|Statistical methods (distributions, etc.)|

## Installing Python Libraries

In the command line (Anaconda PowerShell Prompt on Windows, Terminal on MacOS), run the following commands (in addition to the core libraries)

```
pip install arch sktime
```

In Google Colab, the missing libraries can be installed with a command in the first cell (this must be done every time the notebook is opened)

```
%%capture --no-display
!pip install sktime arch
```
