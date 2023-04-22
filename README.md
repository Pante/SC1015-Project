# SC1015 Project - Steam Games Analysis

This repository contains the Jupyter Notebooks and relevant datasets for this SC1015 mini project. Our mini project uses
the [Steam Games Dataset](https://www.kaggle.com/datasets/trolukovich/steam-games-complete-dataset).

## Motivation & Problem Statement

Pre-ordering and buying games early is risky. Consumers cannot predict how "good" the game will be. On steam, consumers
often use `users' reviews` as a proxy metric for how "good" a game is. However, this metric needs to be aggregated and is
often only available a few days after launch. To make pre-ordering and buying games early less risky, we want to predict
how "good" a game is based on `users' reviews` as a proxy.

To do so, we formulate the following question:
* Can we predict how well received is a game (users' reviews are "mostly positive") based on its attributes?

## Models Used

* Linear Regression
* Decision Tree
* Logistic Regression
* Random Forest Regression

## Conclusion

TODO

## Learning Points

* [One-hot encoding](https://en.wikipedia.org/wiki/One-hot) to encode columns that contain a list of values.
* [Pickle](https://docs.python.org/3/library/pickle.html) file format for serializing/deserializing prepared data efficiently.
* Logistic Regression and Random Forest Regression machine learning models
* Principal component analysis (PCA) for dimensionality reduction of data
* Ensemble learning to improve predictive performance of our models
* Resampling of dataset, including the original ratio, oversampling & balanced resampling

## Contributors

* [Isaac Tan (Peanutpiggy)](https://github.com/Peanutpiggy) - 
* [Matthew Heng (matt0781)](https://github.com/matt0781) - 
* [Matthias Ngeo (Pante)](https://github.com/Pante) - Crafting problem statement, data preparation & summarizing findings

## References
* https://machinelearningmastery.com/why-one-hot-encode-data-in-machine-learning/
* https://docs.python.org/3/library/pickle.html
* https://towardsdatascience.com/logistic-regression-detailed-overview-46c4da4303bc
* https://towardsdatascience.com/random-forest-regression-5f605132d19d
* https://www.sartorius.com/en/knowledge/science-snippets/what-is-principal-component-analysis-pca-and-how-it-is-used-507186
* https://machinelearningmastery.com/tour-of-ensemble-learning-algorithms/
* https://www.kaggle.com/code/rafjaa/resampling-strategies-for-imbalanced-datasets/notebook