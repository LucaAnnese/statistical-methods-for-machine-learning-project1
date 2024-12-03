## Introduction

The report describes my experimental project for the course in Statistical Methods for Machine
Learning. The chosen project requires implementing the Ridge Regression algorithm from scratch,
without the help of outer libraries, to predict the popularity of musical tracks from the music
application Spotify, using the data set available from [Kaggle.com](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset).

In particular, the project requires implementing the Ridge Regression algorithm and then test-
ing its performance on the data set both including categorical labels as well excluding them, thus
using only numerical features. Moreover, to validate the produced model, alias to compute the risk
estimates and find the best hyperparameter, 5-fold Cross Validation is performed in both cases.
When predicting with categorical features included, the project asks to choose the correct encoding
method.
