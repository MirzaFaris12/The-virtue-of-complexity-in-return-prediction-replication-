This repo is replicating the following paper:

Kelly, Bryan T. and Malamud, Semyon and Zhou, Kangying, The Virtue of Complexity in Return Prediction, December 2021, Swiss Finance Institute Research Paper No. 21-90. Available at SSRN: https://ssrn.com/abstract=3984925 or http://dx.doi.org/10.2139/ssrn.3984925.

Contrary to conventional wisdom in finance, return prediction R2 and optimal portfolio Sharpe ratio generally increase with model parameterization, even when minimal regularization is used. We theoretically characterize the behavior of return prediction models in the high complexity regime, i.e. when the number of parameters exceeds the number of observations. Empirically, we document this "virtue of complexity" in US equity market prediction. High complexity models deliver economically large and statistically significant out-of-sample portfolio gains relative to simpler models, due in large part to their remarkable ability to predict recessions.

The dataset referenced in the paper is available at Amit Goyal's webpage and from his paper A Comprehensive Look at the Empirical Performance of Equity Premium Prediction (with Ivo Welch), July 2008, Review of Financial Studies 21(4) 1455‒1508.

experiment.ipynb: This notebook serves as a testing ground for the initial setup and validation of the model. It's where the dataset was replicated and a preliminary check was conducted to ensure that everything was functioning as expected. In other words, it's a single run-through of the model, used for quick prototyping and troubleshooting.
