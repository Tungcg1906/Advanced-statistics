# R_Project_Bayesian_Network

A Bayesian belief-network structure is a directed acyclic graph in which nodes represent domain variables
and arcs between nodes represent probabilistic dependencies [1]. Given a database of records, it is interesting to construct a probabilistic network which can provide insights into probabilistic dependencies
existing among the variables in the database. Such network can be further used to classify future behaviour of the modelled system [1]. Although researchers have made substantial advances in developing
the theory and application of belief networks, the actual construction of these networks often remains a
difficult, time consuming task. An efficient method for determining the relative probabilities of different
belief-network structures, given a database of cases and a set of explicit assumptions is described in [1]
and [2].

The K2 algorithm [2] can be used to learn the topology of a Bayes network. 

In this project, we will immplement 2 main tasks:

1. Create the K2 algorithm for Bayesian network, after that, test the performance of the K2 algorithm with different networks (Ruiz, Asia, Child)
2. Investigate if it is possible to code it inside the bnstruct R package. 
