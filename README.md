# BT4222 Project
In this project, we used statistical tests to explore the different factors affecting Airbnb prices in New York City and Singapore. In addition, we built a price prediction model to suggest a price for hosts. This would help hosts to better price their listings, as well as help them identify areas to improve the quality of their listings.

## Description of Notebooks
1. Notebooks prefixed with "NYC" are used to clean, preprocess, and conduct EDA on New York City's Airbnb listings
2. Notebooks prefixed with "SG" are used to clean, preprocess, and conduct EDA on Singapore's Airbnb listings
3. Notebooks prefixed with "NY_SG" are used to preprocess and conduct EDA after combining the cleaned listings of each city
4. *Stats_Tests.ipynb* is a notebook containing the codes for testing our hypotheses
5. *Non_NN_Models.ipynb* contains the codes used to test out various models for price prediction. It excludes neural network models
6. *NYC_MLP.ipynb* and *SG_MLP.ipynb* contain codes to build our neural network models

## Usage Guide
We have placed all the necessary data files in this folder: https://drive.google.com/drive/folders/1ZLqx7Sp4b5_ds1rsDs6LuXhar2RLtM_f?usp=sharing. The main folder contains the raw data files, processed data files, and train, test, val files in csv format. The *model_results* subfolder contains pickle files of results from various models. The *pkls* subfolder contains the pickle files of train, val, and test data of different combinations of features which we tried.
<br> <br>
We provided these files for convenience because the notebooks would take some time to run due to the large size of our data. To reproduce the processed data which we used for EDA, modelling, and hypothesis testing, run the notebooks in this order for each city: *_DataCleaning.ipynb --> _Subway/MRT.ipynb --> _Preprocessing.ipynb*

## Contributors
Victor, Jacelin, Wei Sheng, Yi Ling, Evangeline
