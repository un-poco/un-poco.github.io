---
title: activation function
date: 2020-01-16 19:31:00
tags:
---
## sigmoid   

      a = g(z) = 1/(1 + e^(-z))  
```math
g'(z) = a(1-a)
```
<!--more-->
## tanh

```math
g'(z) = 1 - a^2
```

## ReLU &Leaky ReLU
### ReLU

```math
g'(z) = 0(z < 0)    

g'(z) = 1(z > 0)
```
### Leaky ReLU

```math
g'(z) = 0.01(z < 0)  

g'(z) = 1   (z > 0)
```

