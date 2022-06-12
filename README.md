# NFT Price Prediction with Multivariate LSTM networks

NFT sales price predition protoypes, build in the context of the final applied computational intelligence project at FHNW.

## Description

This repository contains two software protoypes to forecast Non Fungible Token (NFT) sale prices by using multiple multivariate time series datasets containing features defined by the current state of research in the Non Fungible Token (NFT) market space. The software protoypes where implemented with help of two python machine learning libraries [Pycaret](https://pycaret.org/) and [Dart](https://unit8.com/resources/darts-time-series-made-easy-in-python/).

## Getting Started

### Prerequisites

* [Anaconda Navigator](https://anaconda.org/anaconda/anaconda-navigator#:~:text=Anaconda%20Navigator%20is%20a%20desktop,to%20use%20command%20line%20commands.)
* [Python 3.8](https://www.python.org/) 
* [Dune Analytics Account (free acc.)](https://dune.com/browse/dashboards) 
* [m3o API Access (free acc.)](https://m3o.com/) 
* [Twitter API Access (free acc.)](https://developer.twitter.com/en/docs/twitter-api) 

### Installing

* Clone the project repository from [Github](https://github.com/f4h578/ACI_prototype_NFT_price_predicton) or place the code 
directly in a directory of your choice
* Create a new [python environment](https://docs.anaconda.com/anaconda/navigator/tutorials/manage-environments/)
* Install all dependencies by running the follwing command (the requirements.txt files can be found in the root dir of the project):
```
conda create --name <env> --file requirements_first_env.txt
```
* Create a second [python environment](https://docs.anaconda.com/)
* Install all dependencies by running the follwing command:
```
conda create --name <env> --file requirements_second_env.txt
```

### Executing the program

* Open [juypter notebook](https://jupyter.org/) in Anaconda Aavigator
* [Select the first environment ](https://docs.anaconda.com/anaconda/navigator/tutorials/manage-environments/#using-an-environment) 
* Prepare the data by running the following juypter notebook files in the following order:
    * GetGoogleTrendsData.ipynb
    * GetSingleNFTData.ipynb
    * GetNFTCollectionData.ipynb
    * CombineDatasets.ipynb
* After creating the final dataset you can run both **SingleTimeSeriesModel.ipynb** and **MultipleTimeSeriesModel.ipynb**
* **IMPORTANT!** Make sure to select the *second environment* for the execution of the **MultipleTimeSeriesModel.ipynb** 

## Authors

* Jerome Branny
* jerome.branny@students.fhnw.ch

## Acknowledgments

Inspiration, code snippets, etc.
* [Multiple Time Series Forecasting with PyCaret](https://towardsdatascience.com/multiple-time-series-forecasting-with-pycaret-bc0a779a22fe)
* [Multiple Time Series Pre-trained Models and Covariates](https://github.com/unit8co/darts/blob/master/examples/01-multi-time-series-and-covariates.ipynb
)
* [Dune analytics](https://github.com/itzmestar/duneanalytics)
* [Top nft data analysis](https://github.com/dansal0807/top-nfts-data-analysis)
* [Opensea data mining](https://github.com/AlxDfy/OpenSea_API_DataScience/blob/main/data-mining-OpenSea.ipynb)