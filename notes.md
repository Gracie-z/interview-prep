## Data Cleaning
- [] describe, info
- [] Change date str into pd.to_datetime
- [] might want to sort the values based on dates, names etc.
- [] check missing values
- [] range of date, values etc.  (any abnormal values, outliers)
- [] duplicates (drop)
- [] inconsistent values (negtive numbers, high < low etc.)
- [] train-test split; EDA only on trainining set



## EDA

### stocks
- [] plot prices
- [] plot trading volumes
- [] bar chart of mean traded share volumes
- [] plot daily returns
- [] calculate basic stats like skewness, excess kurtosis, 80, 90 percentiles etc.
- [] plot histograms to get a feel of the distribution.
- [] plot moving average (smoother version)
- [] plot daily volatility, check GARCH/ARCH effect, probably via some tests (e.g. LM)
- [] plot autocorrelation of daily returns and daily returns squared
- [] cross-stock correlations
- [] same-day volume-return relationships
- [] Ljung–Box tests whether autocorrelations at lags 1–20 are jointly zero;  ACF plot compares returns, absolute returns and squared returns.
