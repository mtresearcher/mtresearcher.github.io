--
layout: post
title: Optimal Online Learning
--
Online learning is a machine learning task where a predictor iteratively
  1. receives an input and outputs a label,  
  2. receives the correct label from a human and if the two labels do not match, it learns from the mistake.
However, online learning in itself is a hard problem if the hyper parameters are not set correctly, 
the learning can overfit the training data or diverge.
The fitness of model also depends on the number of iterations of online learning.
Usually these parameters are set by hand leveraging hit and trial method.

In this work I plan to optimize these parameters and achieve robust and consistent results in different settings.
