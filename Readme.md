## Framing our problem

i. Our exact objective is to come up with a better way of predicting estimated prices of houses in california. Our estimates of the median house prices will help a real estate manager/developer solve their business problem. 

ii.In our analysis: we shall discover more about the data and visualize it to get insights, prepare it to machine learning algorithms, pick a model to train it based on our data, optimize the model and then present our solution.

### The current solutions

1. Current solutions are based on complex estimates that are hard to keep track of and vary across regions within a short time. Some of these estimate methods cannot be relied upon. 

2. We can therefore offer solutions based on a machine learning technique that can be used to predict other cases.

#### Our solution

Our solution will use a supervised machine learning model of which it will be a regression task with batch learning. 

Since we are dealing with labeled training example to predict the median house price, we shall be using a supervised machine learning with a regression method (multivariate since we have several features to make predictions with). And since there is no continous flow of data and the data can fit into memory, we shall be using a batch technique <a href="https://vitalflux.com/difference-between-online-batch-learning/">Batch and online learning.</a>. 