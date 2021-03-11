# Share-price-predicting

In this project we are going to predict the stock price by analyzing the historical price trends.

To start with these first we are going to import the required libraries.

We are going to analyze the companies which are in BSE SENSEX list. so to get the list we are using request and beautifulsoup libraries to scrap the list from the wikipedia.

Than we are creating a function to get the historical data from yahoo with pandas datareader.

it is advisable to store the data in local memory or on cloud because it will take a while to get the data of all the companies from yahoo and you do not need to spend that much of time all the time.

so we are storing it in a directory in local memory.

we are using asian paints company's data here to predict the price.

You need to use sklearn library and different classifiers of it to train and test the data.

we are using votingclassifier to vote out the classifier that gives the best result among the given, linear regression is not a classifier so we may need to analyze with that separetly.

We are going to use the best classifier form all of the above to predict the price which is linear regression.

we are plooting a graph to visualize the accuracy and predicting the prices.

Finally we are determining the overall performance of the company with respect to market and showing the return in the graph.
