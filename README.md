# BitcoinAvalanches
The analysis methodology was adapted from Bray et al. (2020) and relies on approaches described by Di Santo et al. (2017) and Santucci et al. (2018). To run these notebooks the following dependencies are required: SciPy, NumPy, Pandas, Statsmodels, and Matplotlib.pyplot.

Bitcoin price data is available in the file 'BTC-USD.csv', spanning the date range from 17/09/2014 - 17/03/2022. To access more recent price data, please download the relevant files from CoinMarketCap.com. Under 'btcanalysis', you will find the full methodology, split into three sections:
(1) timeseries processing
(2) quantifying fluctuations
(3) avalanche analysis

This analysis pipeline can be modified to investigate any time series dataset. In order to do so, first download your desired data and then change the relevant parts of the Jupiter notebook.
