# Ad-Click-Prediction
Digital advertising is a very huge business which is worth more than 50 million dollars. Because of targeted advertising the revenue that the advertisers earn is increasing. A lot of analysis has been done in the previous years, from ad-click prognosis to ad serving. There are a lot of advertisement formats such as search engines, video advertisements, textual and contextual advertisements etc on which ad-click prognosis has been done. As there is a huge growth in online activities, advertisers have been using different procedures and methods to display relevant advertisements which suits the viewer’s interest. With the growing advertising network, the data which should be analyzed for ad-click prediction is very large. With the rapid increase of advertising network, click prediction needs huge data analysis. The advertisement prediction is one of the most lucrative stories in the domain of machine learning. Also, the advance in ad serving machinery have brought a real time bidding answer where ads are short listed based on the attributes of the publishers and the viewers. 

## Problem Statement
As online advertising is a very huge business, it is important to practice targeted advertising. Advertising to random users would result in wasting resources and can lead to a negative impact on the product. So, we should apply certain methods to analyze the user behavior and target advertisements which suits the viewer’s interest. We have to predict if a customer will click on an ad based on certain features present in the dataset.

## Objectives
The objective of the project is to predict if a customer will click on an ad based on certain features present in the dataset. We are going to use different algorithms to implement CTR prediction and check which method gives us the maximum model accuracy. 

In short, we are trying to analyze the following points
1.	Is it possible to predict if a customer will click on an ad which is displayed?
2.	Understand which algorithm has the highest Accuracy score and AUC_ROC curve
3.	Analyze the important features in the dataset which helped us in achieving the highest accuracy
4.	Analyze the speed performance of the algorithms and confusion matrix

## Methodology
The methods include data exploration, data cleansing, attribute extraction, analyzing various techniques for ad-click prognosis and finding the most suitable model.

#### Data exploration:
Exploring the data through different plots gives you deeper understanding of data and choosing the suitable Machine Learning Model. We used count plots and heat maps for obtaining visual insights.

#### Data Cleansing:
We used heatmaps for finding columns having null values. By understanding the interdependency among various fields, we replaced the null values with most approximate digits.

#### Attribute extraction:
By performing trend analysis of various fields in the dataset with respect to ad-clicking helped us gain insights about important features to be considered for the prediction. The analysis also gave a perspective of various columns that are interdependent. After analyzing all the fields, we developed a feature matrix that contains fields most suitable for the ad-click prediction.

#### Analyzing Various Techniques for ad-click prognosis:
We will study the CTR dataset using various algorithms. Compared various classification algorithms and selected some suitable algorithms that include Logistic, Gaussian Naïve Bayes, Gradient Boosting Machine, Decision Tree, Random Forest. Because the proportion of the positive and the negative samples is extremely uneven, we proposed the Synthetic Minority Oversampling Technique.

#### Finding the Most suitable model:
Evaluating various algorithms for aspects like fast learning speed, accurate estimation results with easily setting the weights, high precision. Based on these advantages, we concluded the most suitable algorithm for prediction.


