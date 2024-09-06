# Sunspot Predictor
(This project has been done as a programing assignment for course "Sequence, Time Series and Prediction" on Coursera.org website)
## Project Overview

The Sunspot Predictor project aims to build a predictive model for forecasting sunspot activity using historical data. Sunspots are dark spots on the Sun's surface that are associated with solar magnetic activity. Accurate prediction of sunspot numbers can provide insights into solar cycles, which have implications for space weather, satellite communications, and even climate change.
This project utilizes a deep learning approach with Long Short-Term Memory (LSTM) networks to model and predict sunspot activity. The model is trained on historical sunspot data and evaluated on its forecasting performance. The key steps include data preprocessing, model training, and evaluation.


## Files

- **Sunspot-Predictor.ipynb**: This Jupyter notebook contains the main code for building and training the deep learning model. It includes data loading, model definition, training, and forecasting.

- **data-preprocessing.ipynb**: This Jupyter notebook handles the data preprocessing steps required for the model. It covers data loading, cleaning, and preparation before feeding it into the model.

- **readme.md**: This file provides an overview of the project, instructions, and information about the repository.

## Project Description

The goal of this project is to develop a model that can predict future sunspot activity based on historical sunspot data. Sunspots are areas of intense magnetic activity on the Sun's surface, and their number can vary over time. Accurate prediction of sunspot activity can be valuable for understanding solar cycles and their impact on space weather.

### Model Architecture

The model consists of:
- A 1D Convolutional layer to extract features from time-series data.
- Two LSTM layers to capture temporal dependencies.
- Dense layers for final forecasting.
- A Lambda layer to scale the output.

### Data

The dataset used for this project is the daily minimum temperature dataset. The preprocessing steps include normalization, windowing, and splitting the data into training and validation sets.
