# 🚜Prediction the Sale Price of Bulldozers using machine learning🚜


In this notebook, we're going through an example machine learning project with goal of predicting the sale price of bulldozers.

>The goal of the contest is to predict the sale price of a particular piece of heavy equiment at auction based on it's usage, equipment type, and configuaration.  The data is sourced from auction result postings and includes information on usage and equipment configurations.

>Fast Iron is creating a "blue book for bull dozers," for customers to value what their heavy equipment fleet is worth at auction.

## 1. Problem Defination
> How well can we predict the future sale price of a bulldozer, given its Characteristics and previous example of how much similar bulldozers have been solved for?

## 2. Data
>The data is downloaded from the kaggle [Bluebook for Bulldoxers](https://www.kaggle.com/c/bluebook-for-bulldozers) competition.

> There are three main datasets:
> * Train.csv is the training set, which contains data through the end of 2011.
>* Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
>* Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.


## 3. Evaluation 
>The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.

> For more on the evaluation of  this project [click here](https://www.kaggle.com/c/bluebook-for-bulldozers/overview/evaluation)

> **Note:** The goal for regresion evaluation metrics is to minimize the error. For example our goal for this project is to build a machine learning model which minimises RMLE(root mean squared log error)



## 4. Features

> Features are different parts of the data. During this step, you'll want to start finding out what you can about the data.

> One of the most common ways to do this, is to create a **data dictionary**.

> For this dataset, Kaggle provide a data dictionary which contains information about what each attribute of the dataset means. You can [download this file directly from the Kaggle competition page](https://www.kaggle.com/c/bluebook-for-bulldozers/download/Bnl6RAHA0enbg0UfAvGA%2Fversions%2FwBG4f35Q8mAbfkzwCeZn%2Ffiles%2FData%20Dictionary.xlsx) (account required) or view it on [Google Sheets](https://docs.google.com/spreadsheets/d/1frLAkiTS-kAOcfF8JgKNp8o8KWTh6xHKGrVxC1FAi1g/edit?usp=sharing).

> With all of this being known, let's get started! 

First, we'll import the dataset and start exploring. Since we know the evaluation metric we're trying to minimise, our first goal will be building a baseline model and seeing how it stacks up against the competition.

## 5. Finla Submission
> [Final Prediction](https://github.com/thisiskhan/bulldozer-price-prediction/blob/main/test_predictions.csv)

Made with ❤️ by [Raza Khan](htttps://razakhan.netlify.app)
