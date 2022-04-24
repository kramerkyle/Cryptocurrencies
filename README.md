# Cryptocurrencies

## Overview
This repository documents a machine learning exploration of the crypto_data.csv as accessed from CryptoCompare.

## Results
There are three key outputs from crypto_clusterings.ipynb: a scatterplot depicting TotalCoinSupply by TotalCoinsMined, a table of cryptocurrencies, and a 3D-Scatter Plot with 4 clusters.

## Process
To reach these final outputs: data was loaded via Pandas; data was filtered on currencies that trade, have a working algorithm, did not have any null values in columns, and had coins mined; text features were scaled with StandardScaler; principal component analysis was leveraged; and, an elbow curve was created to discover the best number of clusters for the model.
