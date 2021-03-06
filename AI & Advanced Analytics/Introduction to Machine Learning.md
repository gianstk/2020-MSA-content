# Introduction to Machine Learning 
## Basic Concepts 
Autonomous and adaptive. Who would have ever imagined that those two adjectives would describe computers? However, now, especially through the advent of Machine Learning, Artificial Intelligence is more than ever close to be able to understand, analyse or even predict the workings of our world.  
OK those are broad statements and you might have heard about this a thousand times. In this bootcamp, you will really get into what is Machine Learning, understand how it works, and even get a sense of how to build and improve such algorithms. 
### What exactly is Machine Learning?
Let’s say you want to know the price of a 75m2 apartment in Sydney. You already know that a 50m2 apartment is worth $500,000 and that a 100m2 apartment is worth $1,000,000 by looking at some ads on the net. You can easily extract the price of 1m2 in Sydney and conclude that your budget must be around $750,000. 
This example illustrates the principle of linear regression which is the basis of Machine Learning concept. By using a set of data, the computer learns about the environment. It extrapolates and comes out with a model that fits the pattern and is robust enough to predict valid outputs. This is what is called Supervised Learning. 
There are other types of Machine Learning: 
1. _Unsupervised Learning_: the algorithm isn’t given instructions about the characteristics of the data i.e. it has to find out by itself what makes an apartment worth its price. 
2. _Reinforcement Learning_: the algorithm isn’t given any inputs or outputs but has to measure the impacts of its actions on a certain environment through a reward system 

We will focus today on the Supervised Learning. 

## Artificial Intelligence? Machine Learning? Deep Learning?  
- **Artificial Intelligence (AI)** is a broad topic intending to provide machines with human skills. 
- **Machine Learning (ML)** is a tool to reach the ultimate goals of AI, using statistical models and algorithms. 
- **Deep Learning (DL)** is a way of effectively operate ML based on the natural model of neuronal networks. 

## And why learn ML? 
Machine Learning is all about finding ways to teach computers to extrapolate and find trends in a dataset to facilitate decision making, image recognition, or even translations… It is the basis of state-of-the-art technologies such as autonomous vehicles, but it is also implemented in anti-fraud algorithms or personalization interfaces such as Facebook timelines. 
Already essential to a lot of our technologies, Machine Learning is however still a research topic.	Indeed, there is a lot to improve to perfectly mimic our brain! So YES, it is and will definitely be a significant source of employment and a critical tool for all the industries in the future. 

## Testing a final ML model
The machine learning model that we use to make predictions on new data is called the final model. That is, given new examples of input data, you want to use the model to predict the expected output. This may be a classification (assign a label) or a regression (a real value). For example, whether the photo is a picture of a dog or a cat, or the estimated number of sales for tomorrow. The goal of the machine learning project is to arrive at a final model that performs the best, where “best” is defined by: 

**Data**: the historical data that you have available. 
**Time**: the time you have to spend on the project. 
**Procedure**: the data preparation steps, algorithm or algorithms, and the chosen algorithm configurations. 

In your project, you gather the data, spend the time you have, and discover the data preparation procedures, algorithm to use, and how to configure it. The final model is the pinnacle of this process, the end you seek in order to start actually making predictions. 

Now, the question is why do we use train and test sets? 

Creating a train and test split of your dataset is one method to quickly evaluate the performance of an algorithm on your problem. The training dataset is used to prepare a model, to train it. We pretend the test dataset is new data where the output values are withheld from the algorithm. We gather predictions from the trained model on the inputs from the test dataset and compare them to the withheld output values of the test set. Comparing the predictions and withheld outputs on the test dataset allows us to compute a performance measure for the model on the test dataset. This is an estimate of the skill of the algorithm trained on the problem when making predictions on unseen data. 

Whenever working on a data set to predict or classify a problem, we tend to find accuracy by implementing a design model on first train set, then on test set. If the accuracy is satisfactory, we tend to increase accuracy of data-sets prediction either by increasing or decreasing data feature or features selection or applying feature engineering in our machine learning model. But sometime our model maybe giving poor result. The poor performance of our model maybe because, the model is too simple to describe the target, or may be model is too complex to express the target. Hence come the idea of **overlifting** and **underlifting**.

![fitting.png](img/fitting.png)

By looking at the graph on the left side we can predict that the line does not cover all the points shown in the graph. Such model tend to cause underfitting of data .It also called High Bias. Where as the graph on right side, shows the predicted line covers all the points in graph. In such condition you can also think that it’s a good graph which cover all the points. But that’s not actually true, the predicted line into the graph covers all points which are noise and outlier. Such model are also responsible to predict poor result due to its complexity. It is also called High Variance. Now, Looking at the middle graph it shows a pretty good predicted line. It covers majority of the point in graph and also maintains the balance between bias and variance. 

In machine learning, we predict and classify our data in more generalized way. So in order to solve the problem of our model that is overfitting and underfitting we have to generalize our model. Statistical speaking how well our model fit to data set such that it gives proper accurate results as expected. 
