---
title: classification
date: 2020-01-16 19:28:29
tags:
---
## maximum likelihood
<!--more-->
![image.png](https://upload-images.jianshu.io/upload_images/13964980-0f5de1525198ba13.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![image.png](https://upload-images.jianshu.io/upload_images/13964980-a2fd7f23e8699529.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

```math
P(C1|x） =  P(x|C1)P(C1)/(P(x|C1)P(C1)+P(x|C2)P(C2))
```
if there are 7 features:  
μ1,μ2: 7-dim vector  
∑1，∑2： 7*7 matrices
 
 ## modifying model    
**using the same ∑**   
too many parameters cause overfitting
 ![image.png](https://upload-images.jianshu.io/upload_images/13964980-b8a0cf426f1e690c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  
 
![image.png](https://upload-images.jianshu.io/upload_images/13964980-09eba346d31fcb3c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

**∑是原来∑1和∑2的加权平均**  
the boundary is linear

## three steps
- function set
- goodness of a function
- find the best function

## probability distribution
if you are assuming all the dimensions are independent, then you are using Naive Bayes Classifier(朴素贝叶斯分类器)
## posterior probability
**sigmoid function**
![image.png](https://upload-images.jianshu.io/upload_images/13964980-5734f2842655ba2e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![image.png](https://upload-images.jianshu.io/upload_images/13964980-ee4b472708ede19d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

