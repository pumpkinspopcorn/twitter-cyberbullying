# twitter-cyberbullying
This project aims to identify and analyze the cyberbullying tweets on Twitter and propose the best 
classification model out of various machine learning algorithms that can determine and classify a particular 
tweet on whether it belongs to cyberbullying or not. Furthermore, the classification model will also be able 
to determine the category/type of cyberbullying.  

## methodology
![image](https://github.com/user-attachments/assets/8ae1d28d-ba8b-455a-a597-52dab65c4e49)

## the dataset
There are a total of 47000 tweets in the dataset. The dataset is a balanced dataset containing 8000 tweets per type of cyberbullying which includes age, gender, ethnicity, religion and not cyberbullying.
It is to be noted that the tweets in the dataset contain offensive language which might trigger some people. The dataset is only used for research purposes, and it means nothing personal to any other person.

## libraries used
* numpy
* sklearn
* pandas
* seaborn
* matplotlib
* nltk
* demoji (pretty interesting)
* plotly

## machine learning models used and compared for accuracy check
* random forest classifier
* naive bayes multinomial
* gradient boosting
* ada boost
* xgb classifier
* neural networks (ann)
* logistic regression

## results
winner = random forest classifier with an accuracy of 93% !! yeay !!

![image](https://github.com/user-attachments/assets/d87698e8-8daf-4033-a1c4-f51d578e7779)


## deploying the model
By automating the steps involved in creating a machine learning model, a machine learning pipeline is created to run the Cyberbullying Detection Model. An example of the running model is given below.

### a general note before proceeding ahead 
I am strongly against the cyberbullying happenings in social media. The words down below in the figures contain some offensive comments made by users fand is used just to show the working of the model. I don’t support any of the comments as they were chosen just for the implementation from the Twitter app.

![image](https://github.com/user-attachments/assets/00f998c3-ba8e-41c1-a384-5ee66676eb16)

The tweet comment in the figure above gives an output “religion” which is a type of cyberbullying. If observed, some hatred words here were also seen in the top 10 cyberbullying categories while performing data visualization in the pre-processing steps proving the model runs successfully.
The future works can be extended to building a real time cyberbullying detector in a web platform which can easily and instantly detect cyberbullying and prevent it from happening.





