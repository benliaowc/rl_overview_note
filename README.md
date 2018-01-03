# Note: "Deep Reinforcement Learning: An Overview"


## Introduction

This is a note of [Deep Reinforcement Learning: An Overview, Yuxi Li](https://arxiv.org/pdf/1701.07274.pdf).

This note only lists the most important concepts in this paper. Most of the idea may not be eliborated. Only key words are mentioned in the note.

To understand more about the details of reinforcement learning, please scrutinize the paper.

## Note

### Machine Learning

#### Category

* Supervised learning

  * Classification 
  
  * Regression

* Unsupervised learning: representation learning 

  * Clustering 
  
  * Density estimation

* Reinforcement learning

#### Elements

* Dataset

  * Non-overlapping training, validation and testing subsets

* Cost/Loss function

  * Category

    * Training error measures the error on the training data
	
    * Generalization error, or test error, measures the error on new input data
	
  * Measurement
  
    The following measurements are equivalent.
  
    * Maximum likelihood estimation (MLE)
	
	* Minimize KL divergence
	
	* Minimize the cross-entropy
	
	* negative log-likelihodd (NLL)

* Optimization procedure

  * Gradient descent 
  * Stochastic gradient descent

* Model

### Deep Learning

#### Algorithms

* Linear regression

* Logistic regression

* Support vector machine (SVM)

* Decision tree

* Boosting

#### Elements

* Input layer

* Output layer

* Hidden layers

#### Activation Function

* Logistic

* tanh

* Rectified linear unit (ReLU)

#### Networks

* Multilayer perceptron (MLP)

* Convolutional neural network (CNN)

* Recurrent neural network (RNN)

  * Long short term memory network (LSTM)
  
  * Gated recurrent unit (GRU)

#### Others

 * Gradient backpropagation: used for training all deep neural networks
 
 * Dropout
 
 * Batch normalization: normalize each training mini-batch to accelerate training by reducing internal coveriate shift



### Reinforcement Learning

#### Problem Setup

 * State: ![state](pic/01.gif)

 * Policy: ![policy](pic/02.gif)
 
 * Reward: 
 
   ![discounted reward](pic/03.gif)

#### Value Function

 The following decomposition uses [Bellman equation](https://en.wikipedia.org/wiki/Bellman_equation).

 * State value
 
   ![state value](pic/04.gif)
 
 * Optimal state value: 
 
   ![optimal state value](pic/05.gif)
   
   ![optimal state value](pic/06.gif)
 
 * Action value
 
   ![action value](pic/07.gif)
   
 * Optimal action value
 
   ![optimal action value](pic/08.gif)
   
   
 










