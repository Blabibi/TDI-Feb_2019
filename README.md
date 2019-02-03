# TDI-Feb_2019
Traffic signs classification using Bayesian Convolutional Neural Networks.
Goal: This project aims at developing a Traffic signs classifier using Bayesian Convolutional Neural Networks (BCNN). Convolutional Neural Networks (CNN) is a class of deep neural networks which is mainly used for images recognition and classifications. Training a CNN requires calculating both weights and filters which are estimated as a so called “single best” solution. While, the BCNN assumes weights and filters as random variables with probability distributions, providing richer information than the classical CNN approach. This approach renders an ensemble of models obtained from the posterior distribution that can be used to explore parameter uncertainty. Moreover, BCNN models a large class of stochastic functions with heteroscedastic and multi-modal noise. However, appropriate selection of the number of nodes and layers to avoid over- and under-fitting is not straight forward. The common approach is to compare the correlation between training, validation and test data sets to determine optimum number of nodes and layers in the net. Here, it is suggested to use DREAM GAME strategy to select appropriate model [1]. This approach employs a robust estimator of the model evidence which acts as the normalizing constant in the denominator of Bayes’ theorem. The evidence provides a single quantitative measure of relative support for each model. The steps for classifying Traffic Sings are as follows:
•	Collect image data.
•	Explore, summarize and visualize the data sets and perform pre-processing.
•	Split data sets into training, validation, and test set using random selection to avoid biasing the results for BCNN.
•	Select several model architectures (different nodes and layers).
•	Extract main features from images.
•	Train BCNN using the main Features.
•	Examine the training procedure using the test data set.
•	Select the best model using DREAM GAME strategy
•	Summarize the results with a written report

