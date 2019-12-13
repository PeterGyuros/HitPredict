# HitPredict

Dataset used for the project can found at [kaggle](https://www.kaggle.com/zaheenhamidani/ultimate-spotify-tracks-db), however you can find the dataset in this repository as well, by the name 'SpotifyFeatures.csv'.

To rerun the whole proccess run all cells in the preproccessing.ipynb notebook, that will also contain visualisation of the dataset, and some comments and notes regarding the decisions we made about which features and rows we want to use and which not.

However this repository contains the cleaned csv so the training and hyper parameter optimalization can be run without executing the preprocessing steps. The train_and_hyperopt.ipynb contains the code of a basic neural network that we used as a benchmark. Note that hyperopting takes a lot of time so we used the best model and evaluated it against the test.csv that contains rows that were not used when training the model.
