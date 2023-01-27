---
title: Mental Workload Estimation
summary: Mental workload (MWL) refers to brain activities, which are the number of resources in the human brain. 
    
tags:
  - EEG
date: 2022-09-01
external_link: ''
---

<p align='justify'>
  The human brain is continuously active while the human is working or resting. Human mental activity is a daily process. If the human brain works excessively, called overload, human health will be affected. Recently, mental health can be predicted early, which is to avoid serious health consequences and improve quality of life. Therefore, mental status estimation has received the attention of many different researchers due to its benefits. There are many kinds of signals used to assess mental state, but the electroencephalogram contains a lot of information about the brain and is widely used by researchers. In this paper, we classify mental workload into three states (low, middle, and high) and estimate continuum levels of mental workload. Our method combines information of multiple space dimensions to get the best results for mental estimation. Temporal Convolutional Networks is applied for the time domain approach. For the frequency domain, we have proposed a new architecture based on combining residual blocks, called the Multi-Dimensional Residual Block. The combination of these two domains gives a significant result compared to the results of individual estimates of each domain. Our results achieved 74.98\% with the three-class classification, which is higher than the results from the data provided, with 69.00\%, respectively. Our method found that such an approach gives good results in estimating continuous levels. We got the corresponding $CCC$ result of 0.629.
  
  # System overview: Combined time and frequency domains for mental workload estimation.
  
  ![model](residual_model.png)
  
  # Overview of converting EEG signals to a 3D representation.
  
  ![psd](psd.png)
  # Multi-Dimensional Residual Block.
  
  ![mdrb](residual_block.png)
  
  # Demo
  <img src="demo.gif" width="90%" height="100%"/>
</p>

