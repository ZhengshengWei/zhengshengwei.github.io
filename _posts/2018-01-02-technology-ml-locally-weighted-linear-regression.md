---
layout: post
title: "[ML] Locally weighted Linear Regression"
description: "machine learning"
category: technology
tags: []
modify: 2016-01-02 00:00:00
---
   When encounter non-linear relationship problem, linear regression does not work. So locally 
 weighted linear regression is coming out and could solve it.
 
   What is locally weighted linear regression?
   Locally weighted linear regression is non-parametric model. It doesn't learn a fixed set of 
 parameters as is done in ordinary linear regression. Rather computing the parameters 
 individually for each query point (input point).
   The different between locally weighted linear regression and linear regression is that locally weighted 
linear regression's cost function has one more parameter than ordinary linear regression. The 
extra parameter called weight. Cost function is as follow:
   J(θ) = w * (h(x) - y) ** 2
   
   What is the meaning of weight in locally weighted linear regression? And how could we get the 
weight?
   todo: .....
   
   Why we use least square error in cost function to fit linear regression model? 
   There always exists variance in fitting model. Variance is consistent with Gaussian error 
 distribution. When expand Gaussian error formula, we'll finally get the result that least square
 error is part of Gaussian error formula. When least square error is becoming small gradually, 
 the variance will be reduced to small meanwhile. And we'll get more precious model with small 
 variance. So we'll choose least square error in linear regression. 
     
 
 Refer to [CS229 - Locally Weighted Linear Regression](https://www.youtube.com/watch?v=het9HFqo1TQ&t=1245s)
 [https://www.cs.cmu.edu/afs/cs/project/jair/pub/volume4/cohn96a-html/node7.html](https://www.cs.cmu.edu/afs/cs/project/jair/pub/volume4/cohn96a-html/node7.html)
 [https://www.geeksforgeeks.org/ml-locally-weighted-linear-regression/](https://www.geeksforgeeks.org/ml-locally-weighted-linear-regression/)
   
   
       
