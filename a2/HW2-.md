# HW2:

## Written part:

###Word2vec:
- Word embedding vectors
- Softmax -> Probability 
- Objective function : -logP [Max outside probability for specified center W]

#### 1: -logP ?= Cross entropy loss:
> coz the true y is a one-hot vector with all entities are 0 except the 1 for the true class 
> 
> Loss for training data [center known + outside known] 


### Negative Sampling: 
- Assume that K negative samples (words) are drawn from the vocabulary. For simplicity of notation we shall refer to them as w1,w2,...,wK and their outside vectors as u1,...,uK. [sigmoid]
 