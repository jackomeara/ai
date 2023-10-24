# House Price Prediction

This project aims to predict the selling price of houses listed on [www.daft.ie](www.daft.ie).

## Dataset
The dataset used is from kaggle, [daft.ie house price data](https://www.kaggle.com/datasets/eavannan/daftie-house-price-data/).
This contains various information about each listing, including:

- address
- date published
- listed price
- no. of bedrooms
- no. of bathrooms
- property size (yards)
- advised minimum value price
- BER rating
- coordinates (long, lat)
- seller details

The dataset has around 4,000 listings, all from 2022.

## Results
Initial results using just no. of bedrooms, no. of bathrooms and property size were poor as expected, with a expected error of ~ €150,000.

This will look to be improved by including BER rating and amv price.

