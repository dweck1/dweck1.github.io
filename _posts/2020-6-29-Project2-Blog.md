---
layout: post
title: Project 2 Blog
---

Information on this project can be found [here.](https://dweck1.github.io/ST558-Project2/)  

Project 2 was focused on creating analyses to predict the number of shares a Mashable article will receive. The data, [found here](https://archive.ics.uci.edu/ml/datasets/Online+News+Popularity), came from the UC Irvine Machine Learning Repository. After a little bit of cleaning, the dataset ended up having 45 predictive features. The task was to use one linear method and one non-linear method to predict the shares. I used the `caret` package in R to train a linear regression via stepwise selection and a random forest. After the analysis was done, I automated R Markdown to run the analysis and make the predictions separately for each day of the week, resulting in 7 different different analyses.  
  
Looking back on this project, one thing I would do differently is change this into a classification problem. Instead of predicting the exact number of shares (or log shares), I would make it a binary classification problem where I predict whether the article will receive greater than 1000 shares or not. 
  
The most difficult part of the project for me was the automation. I had an inkling this would be the hardest part for me so I actually went ahead and figured out the automation first. I tested out creating different basic reports for different days of the week. Once I figured this out, I performed the analysis and prediction for Monday, then ran the automation to do this for each day of the week.  
  
As for take-aways from this project, my biggest take-away is how easy it is to train models using the `caret` package. It is a very convenient package for training models with different tuning parameters. Additionally, I was reading through the `caret` documentation and saw how many different models can be used with this package. I can now see how this rivals sklearn. Another take-away is that `caret` makes it very easy to preprocess data as well.   
  
 All in all, it was a fun project. It was nice to get more experience using `caret`. I will probably end up using this more in the future. 
