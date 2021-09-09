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
   
   Cost(Lost) Function: (h(x) - y) ** 2  y denote real value. This function also called ordinary 
 least square. Why we choose square error rather than absolute error or error to power 4?
 
   Our goal is that choose optimized θ to minimized square difference (error). And optimized θ 
 makes hypothesis or model work finally. 
 
 Refer to [CS229 - Linear Regression] (https://www.youtube.com/watch?v=4b4MUYve_U8&)
   
   
       
