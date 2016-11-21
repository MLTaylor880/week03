# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) PyMC Introduction
Week 8 | 2.1

## Introduction

> ***Note:*** This can be a pair programming activity or done independently.

So although the basic idea of Bayesian regressions is not much different from what you saw when doing linear regressions. There will be a major difference in how they are implemented in code. Whereas one simply pushed in columns of data and a target into a regression to get output, the actual "specification" of the model is a bit more involved in the Bayesian variety. Generally, you will have to specify priors, likelihoods etc., however, for our purposes, we will be making use of PyMC to help with a lot of that heavy lifting.

Getting back to our previous discussion, the difference between classical and Bayesian regression can be thought of as thus:

***"Classical regression is a special case of the Bayesian perspective whereby we have a non-informative prior."***

I'm sure you recall what *non-informative* refers to uniform priors (i.e. no prior information assumed to bias things one way or another).

We'll work together to complete this codealong!
