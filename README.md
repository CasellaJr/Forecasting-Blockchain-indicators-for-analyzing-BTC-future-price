# Forecasting-Blockchain-indicators-for-analyzing-BTC-future-price
This repository contains the code used to execute the experiments described in the paper <i>Predicting Cryptocurrencies Market Phases through
On-Chain Data Long-Term Forecasting</i>. Code is written in [Python](https://www.python.org/) and using the [Keras](https://keras.io/) framework.

Extensive experiments have been executed testing stochastic processes (SARIMAX) and DL models (CNN and RNN) over six on-chain time series collected from [Glassnode](https://glassnode.com/): New and Active Addresses, Block Height, Fees, Hash Rate, Spent Output Profit Ratio (SOPR).

Models have been trained on an Intel(R) Core(TM) i5-5257U CPU (2 cores per CPU).

## Usage

To run the experiments as is, clone [this](https://github.com/CasellaJr/Forecasting-Blockchain-indicators-for-analyzing-BTC-future-price) repository and follow instructions:
```
1. Download the metrics from Glassnode
2. Put the data in the same folder of the Jupyter notebooks
3. Run all the cells of the Jupyter notebook
```
If you want to use additional datasets, you need to change only the first few cells where there is the import of the data.

## Contributors

Bruno Casella <bruno.casella@unito.it>  

Lorenzo Paletto <lorenzo.paletto@unito.it>
