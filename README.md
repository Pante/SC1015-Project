# SC1015 Project - Steam Games Analysis

This repository contains the Jupyter Notebooks and relevant datasets for this SC1015 mini project. Our mini project uses
the [Steam Games Dataset](https://www.kaggle.com/datasets/trolukovich/steam-games-complete-dataset).

## Motivation & Problem Statement

Pre-ordering a game is risky. Consumers cannot predict how "good" a game will be. On Steam, the `users' reviews` score
is often used as proxy metric for that. However, this metric is only available a few days after a game is launched.
Developers often offer exclusive in-game content and discounts to incentivize pre-ordering. Hence, purchasing game after
it is launched will mean eschewing the content and discounts. To allow consumers to reap the pre-ordering benefits, we
want to minimize the risk by recommending whether to buy a game or not.

To do so, we formulate the following question:
* Are we able to predict if a game is good or bad based on its attributes?
* Which machine learning model would be the best at predicting it?

## Models Used

* Logistic Regression
* Decision Tree
* Random Forest Regression

## Conclusion
* There is no correlation between price and how well received is a game.
* Massively multiplayer (MMOs) games tend to receive lower scores than other genres.
* Sekai Project and SCS Software tend to produce more well received games compared to other publishers.
* Resampling imbalanced data drastically improved performance in most cases.
* Logistical Regression isn't the best at handling non-linear correlations.

## Learning Points

* [One-hot encoding](https://www.geeksforgeeks.org/ml-one-hot-encoding-of-datasets-in-python/) to encode columns that contain a list of values or objects.
* [Pickle](https://docs.python.org/3/library/pickle.html) file format for serializing/deserializing prepared data efficiently.
* Principal component analysis (PCA) for dimensionality reduction of data (before using K-means for data clustering).
* Data clustering methods such as K-means clustering.
* Resampling of dataset, including the original ratio, oversampling & balanced resampling.
* Logistic Regression and Random Forest Regression machine learning models.
* Ensemble learning to improve predictive performance of our models.
* Recall as a main metrics instead of Accuracy to judge our models. 
* Cross validation & hyper-tuning of models.
* Concepts about Precision, Recall, and F1 Score.

## Contributors

* [Isaac Tan (Peanutpiggy)](https://github.com/Peanutpiggy) - Machine Learning, writing script, making slides for presentation, and do the presentation 
* [Matthew Heng (matt0781)](https://github.com/matt0781) - Data Visualization, Data Resampling, and Machine Learning
* [Matthias Ngeo (Pante)](https://github.com/Pante) - Crafting problem statement, data preparation, proofreading & summarizing findings

## References
* https://machinelearningmastery.com/why-one-hot-encode-data-in-machine-learning/
* https://docs.python.org/3/library/pickle.html
* https://towardsdatascience.com/logistic-regression-detailed-overview-46c4da4303bc
* https://towardsdatascience.com/random-forest-regression-5f605132d19d
* https://www.sartorius.com/en/knowledge/science-snippets/what-is-principal-component-analysis-pca-and-how-it-is-used-507186
* https://machinelearningmastery.com/tour-of-ensemble-learning-algorithms/
* https://www.kaggle.com/code/rafjaa/resampling-strategies-for-imbalanced-datasets/notebook
* https://github.com/nicklimmm/movie-analysis/blob/main/README.md
* Exercise 6: Walk-Through Notebook, SC1015 Introduction to Data Science and Artificial Intelligence, Nanyang Technological University, Singapore 2023. 
