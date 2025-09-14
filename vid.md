# TASK 21: Watch & Reflect – Intro to Machine Learning

# Aim

To Understand foundational ML concepts and data preparation techniques by watching two beginner-friendly videos and writing an article.

## Video-1 :A Gentle Introduction to Machine Learning by *StatQuest*.

The way how statquest brings a weird style of explaining stuff is why they are so good at teaching.

In statquest's video we are first introduced to the topics of **Decision Trees** and **Linear Regression**

So what are decision trees?
They are the type of classification supervised ML algorithms which are used to determine a particular outcome using a set of cases, depending on each iteration to progress to the goal, kind of like how a flowchart managaes if-else statements.
Oddly we can also use decision trees for Regression.

In the video statquest's example of decision trees, he aims to predict and classify people by if a person likes statquest's content or not?
He uses silly songs,Machine Learning, Statistics as his classification questions to classify.
The algorithm goes in a sequential order at every step trying to confirm the output.

![](https://github.com/hrishikesh-rao/level0/blob/main/image_2025-09-10_231528822.png?raw=true)

![](https://github.com/hrishikesh-rao/level0/blob/main/image_2025-09-10_231707582.png?raw=true)

Later we deal with linear regression, statquest's example of speed vs amount of yam consumed is an apt situation to talk about regression line

So in its essence what exactly is linear regression?

Maybe think of it as you are given a number of data points such that you cant fit a line through all of them, but you can find a best fit line, which has some small bit of extra distance from the given data point value to the line's value at that point.

So regression is all about reducing that error as far as possible, this can be used for prediction as it does do a pretty good job in predicting.

If your model fits the training data well, but does not perform well on testing data, then the best fit line isnt found.This condition is called the **Bias-Variance Tradeoff**.

Also you might be wondering why cant we just fit a squiggly curve which just fits through all the points.
This is kind of incorrect as at this point as the distance between predicted value and the actual data point value is far greater than the case with the line. Hence a squiggly line is not used.

At this point onwards we learn about what training and testing data are.
So training data maybe defined as the data which we feed the model whilst training.
Testing data is the data which we input to the model inorder to test its prediction capabilities.

Note that training data is not the same test data

Usually we split the dataset into two parts one is testing data and other is training data.
The % of splitting is arbitrary usually 75(train)-25(test)

So yes it is important we split the data.

![](https://github.com/hrishikesh-rao/level0/blob/main/image_2025-09-10_233758318.png?raw=true)
---

## Video-2: How is Data Prepared for Machine Learning? by AltexSoft

AltexSoft's video on how data is prepped befoee feeding to the model is a must watch for anyone who is trying to learn ML.

So what is meant by data prepping and why should we clean/refine data

Always note that when you obtain datasets from any source, there are high chances that it's going to contain all types of stuff in it, ranging from numeric data,boolean,text etc. Also not all entries are refined, you may find a lot of garbage data containing null characters, zeros and repeated strings. So it becomes an utmost importance to properly clean data and to drop such data before feeding it to the model.

*So how much training data is too much data??*

To be frank there is no restriction to set upon oneself to limit to let's say 'n' number of training data points.
It is arbitrary I would say as it depends on the model you train.

The email quick response suggestions, it took nearly 238 million data to develop that feature.

So number of data points used is directly proportional to the extent of features your model offers.

### Data Quality

Now lets say we have our required number of data points, are we sure that all of our data meets upto our expectations in terms of quality.
Heres a small example
Lets say you want to train a model to predict the price of turkeys during thanksgiving in USA, and the dataset your working with is of Canada's.
Now in Canada pumpkin pie is made more during thanksgiving and not turkey. On the other hand Turkey is preferred in USA.

It is kind of obvious that sales of turkey in USA > sales of turkey in Canada.
This is why the quality of dataset, More specifically the working range of datasets matter a lot.

Now lets assume we have data of quality,

### Labels

We still need to assign some identifiers by which the model can understand what is actually going on?

So in a dataset,the measurable characteristics which define the data are called features.
Now lets consider a datasets of apples.

Apples are usually distinguished by their shape,size,colour,texture.

So when enough data about such parameters are fed to model, if we input the features of a grape,it will be able to identify that it is not an apple

A label is the output or target value in a dataset that the model is trained to predict.

### **Data cleansing and reductions**

Not all data is good data, even though it is of high quality as we simply may not use it in our projecct, so it becomes necessary to reduce our sample space and work with data entries which we actually need.

Pandas, a framweork in Python has a lot of functions for data manipulation and cleaning.

Say we have a set of boolean values in the dataset, we can just convert them to binary(0/1) and proceed to work with it.

Also let's assume that there is a whole column of irrelevant data, it is always best to drop such data and proceed forward.
It is always best to drop irrelvant data as they increase the train time of the model as it requires a very large computational power to go forward.

### **Data Wrangling**

Transforming existing data to a form we need based on our project is called data wrangling.

There are two main parts to data wrangling
1. Formatting :Ensuring the dataset does come under a proper extension file(plain text file like .csv)

2. Normalization: It is a type of data preprocessing step where we rescale numerical values in a dataset so they fit within a specific range.This is importance as some models consider higher magnitude of data values to be given importance.


### **Feature Engineering**

In the given dataset you start making your own set of data by performing mathematical operations or concatenating two columns so that your sample space is extended.

This concludes.