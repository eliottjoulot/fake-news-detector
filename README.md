# Fake news challenge

[Kaggle](https://www.kaggle.com/c/fake-news){: .btn .btn--info}

In this task, we will have to build a ML model that gives a confidence score between 1 and 0 to an article (is this article reliable or not). The requirements are:

- train a model on the Kaggle fake news dataset https://www.kaggle.com/c/fake-news/data .
- provide the metrics to assess our model on the testing set (accuracy etc)
- build a final function give_score(link) that takes a link of an article as an input and outputs the confidence score. 
- compare 3 different ML technics.

<br>

**Required libraries to run this notebook:**

*Included in Anaconda distribution:*
- numpy
- pandas
- scikit learn
- requests
- bs4

*Not included in Anaconda distribution:*
- [newspaper](https://github.com/codelucas/newspaper) *( $\rightarrow$ pip3 install newspaper3k)*

<br>