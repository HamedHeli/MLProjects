![alt text](Scikit_learn_logo.png)

# Machine Learning Projects
Here, I am describing the Machine Learning (ML) projects that I have done. The projects have been performed inspired by the courses that I took or my personal intersts. 

:large_blue_diamond: [Predicting Diamond Price (Linear Regression)](https://github.com/HamedHeli/MLProjects/blob/0ce53fae568dc294c96499e4c3b85a37941e1438/Linear%20Regression/Diamond.ipynb): 
      
   In this project, I make a linear model for predicting the diamond's price based on its carate, clarity, color, and cut. Including the data with more than 50,000 rows, I trained the model by using 0.5% of the population (training population) and then test the model using the rest to verify the model's accuracy. The model shows >80% accurracy (in terms of R-squared). 

:computer_mouse:[Predicting Advertising Clicks (Logistic Regression)](https://github.com/HamedHeli/MLProjects/blob/6dc829c39f345fb71c509e6f101739c499058641/Logistic%20Regression/Advertising.ipynb): 

In this project, I make a logistic model for predicting whether or not a particular internet user clicked on an advertisement based off the features of that user. The user's features include age, average income of their living area, the time they spend on internet, and the time they spent on the site. I trained the model by using 40% of the population and evaluate the model perfromance by calculating confusion matrix.


:dark_sunglasses: [Classifying Anonymized Dataset (KNN Classification)](https://github.com/HamedHeli/MLProjects/blob/6d9ea3fd51c759f83d40a6ba02f18971aad0aaaf/KNN%20Classification/K%20Nearest%20Neighbors.ipynb):

I have been given a classified data set from a company. They've hidden the feature column names but have given you the data and the target classes. I try to use KNN to create a model that directly predicts a class for a new data point based off of the features.


:moneybag: [Predicting Loan Paid Back (Decision Tree and Random Forest Classification)](https://github.com/HamedHeli/MLProjects/blob/6d9ea3fd51c759f83d40a6ba02f18971aad0aaaf/Decision%20Tree%20and%20Random%20Forest%20Classification/Ensemble%20Decision%20Trees%20(Random%20Forest).ipynb):

In this project, I will be exploring publicly available data from [LendingClub.com](https://www.lendingclub.com/). Lending Club connects people who need money (borrowers) with people who have money (investors). Hopefully, as an investor you would want to invest in people who showed a profile of having a high probability of paying you back. I will try to create a model that will help predict this.

:hibiscus: [Clustering Iris Flower Data Set (Support Vector Machines with Grid Search)](https://github.com/HamedHeli/MLProjects/blob/194e670773d380c3a4528d87a1aa6fc9bee3b91f/Support%20Vector%20Machines/Support%20Vector%20Machines.ipynb):

For this project, I am using the famous [Iris flower data set](http://en.wikipedia.org/wiki/Iris_flower_data_set) and try to cluster them.
The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced by Sir Ronald Fisher in the 1936 as an example of discriminant analysis. 
The data set consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor), so 150 total samples. Four features were measured from each sample: the length and the width of the sepals and petals, in centimeters. Here, I try to cluster them (pretend that I do not have the labels) by using SVM method while the parameters are chosen by applying Grid Search. 

:school: [Clustering Universtities into Private and Public (K-Means Clustering with Principal Component Analysis)](https://github.com/HamedHeli/MLProjects/blob/194e670773d380c3a4528d87a1aa6fc9bee3b91f/K%20Means%20Clistering/K%20Means%20Clustering.ipynb):

For this project I will attempt to use KMeans Clustering to cluster Universities into to two groups, Private and Public. It should be noted that I actually have the labels for this data set, but I will not use them for the KMeans clustering algorithm, since that is an unsupervised learning algorithm. Since the number of data features are high, I use Principal Component Analysis (PCA) to reduce the dimensions that apply the algorithm only on the feature that matters.  

:+1: [Classifying Yelp Reviews (Natural Processing Languag Pipelines with Random Forest and Naive Bayesian Classification Method)](https://github.com/HamedHeli/MLProjects/blob/DataAnalysis/NLP/NLP%20Project.ipynb):

In this NLP project I will be attempting to classify Yelp Reviews into 1 star or 5 star categories based off the text content in the reviews. I will use the Yelp Review Data Set from Kaggle where each observation in this dataset is a review of a particular business by a particular user. I make pipelines with different text processors and classification method and compare the reults by printing confusion matrix. 
