# Motivation and Overview

**Example** doctors to decide the dieases according to some symptoms and test
results.

In these kinds of problem that we need use reasoning to get conclusion or
decision based on known information.

**Probabilistic Graphical Model** is a framework to deal with this kind of
applications.

**Model** is a decalrative representation of our understanding of the world.
This means that the representation stands on its own. Which means we can see it
independent from algorithm.

- Same model can be used in the context of one algorithm that answer any one kind of question.
- We can separate out construct of model from the algorithms. We can construct
  from human expert or learning from statisical machine learning. 
  
**Uncertainty** 

- Partial knowledge of state of the world
- Noisy observations
- Penomenal not covered by our model 
- Inherent stochiasticity

**Probability Theory** 

- Declarative representation with clear semantics
- Powerful lreaning patterns
- Estatblished learning methods

**Complex System** 

Graph can allow us to represent very complex system that involve large amount of
variables. 

**Graphical Models** 

There are two main classes of graphical models. In graph representation, node
means random variables. 

- The first one is Bayesian network. Which represented by directed graph. 

![](../imgs/1/Bayes.png)

- The other representation is called Markov Network, which is represented by
  the undirected graph
  
![](../imgs/1/Markov.png)

## Graphical Representation

Graphical Representation offers us some benefits in such problem.

- Intuitive and compact data structure
- Efficient reasoning using general-purpose algorithms
- Sparse parameterization (Reduce the number of parameters)
  - feasible elicitation (from human knowledge)
  - learning from data 
    
## Overview

- Represntation
  - Directed and undirected
  - Temporal and plate models
- Inference
  - Exact and approximate
  - Decision making
- Learning 
  - Parameters and structure
  - With and with out complete data
