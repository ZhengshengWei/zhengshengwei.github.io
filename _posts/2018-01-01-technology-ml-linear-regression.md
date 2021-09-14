---
layout: post
title: "[ML] Linear Regression"
description: "machine learning"
category: technology
tags: []
modify: 2016-01-01 00:00:00
---
   When people want to predict a real value (eg. house's price) as target, linear regression can 
 solve this.
   Generally, (learning) algorithms receive training examples and output hypothesis (called model later). 
 Hypothesis receive input data that people want to get prediction value by and output prediction value which people want to predict. 
 Here linear regression is a hypothesis or model we finally want to to get. once own that, we can predict value we need.
 
   Hypothesis: H(x) = θ + θx. θ denote parameter, x denote feature or attribute. How can we get 
   θ? by using cost function.
   
   Cost(Lost) Function: J(θ) = (h(x) - y) ** 2  y denote real value. This function also called ordinary 
 least square. Why we choose square error rather than absolute error or error to power 4?
 
   Our goal is that choose optimized θ to minimized square difference (error). And optimized θ 
 makes hypothesis or model work finally. 
 
   How to choose optimal θ?
   We have two ways to calculate θ. 
   one is solve the value of θ directly by taking gradient of J(θ) and set it equal to 0. Because the minimum and maximum value of a function is at the 
 point, which is solved by setting gradient of function equal to 0.  
   the other one is find the value of θ by gradient decent mean, which is a widely used algorithm 
in machine learning(Logistic Regression, Neural Networks etc.). Normal equation of it is 
θ = θ - α * (hθ(x) - y) * x.
   
   How many patterns of gradient decent?
   1. Batch gradient decent
   2. Stochastic gradient decent
   3. Smooth Stochastic gradient decent
 
   At last, let 's look at the problem proposed before. Why we choose square error rather than 
absolute error or error to power 4?
 
 Refer to [CS229 - Linear Regression](https://www.youtube.com/watch?v=4b4MUYve_U8&)
   
   
       
