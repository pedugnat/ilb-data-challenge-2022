# ilb-data-challenge-2022
Very quick sketch of the code used for Institut Louis Bachelier Data Chalenge 2022. 

## Content of this repo
This repo contains the following notebooks

### `exploration.ipynb`
The notebook I used for EDA, visualizing the target variable, missing values, showing a few plots.

### `modeling-lgbm.ipynb`
Main notebook, used to generate a prediction. It gathers feature engineering part and modeling part. It also loads external data and images related features.

### `images_embedding.ipynb`
Generates images embedding using three backbones: ResNet, EfficientNet and Inception.

### `image_prediction_train.ipynb`
Uses images embeddings to make a prediction on the houses price. This prediction is then used in the model to increase overall performance. 

