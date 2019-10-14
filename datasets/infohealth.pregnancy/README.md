# KER - Knowledge Embedding Representation

## Dataset

Infohealth Pregnancy

* LRN: used along the process of training the symbolic embedding representation models
* VLD: used along the process of learning the symbolic embedding representation as a validation set
* TUN: used along the process of learning the symbolic embedding representation to select the best replica (usually each model was trained with 5-10 distinct replicas, each replica initialized with distinct random values for each entity/relation embedding vectors and matrices)
* TST: used along the process of learning the symbolic embedding representation as a test set to report final accuracy

## Objective

Predict whether a pregnant patient has risk of abortion

* only de-identified demographic and clinical conditions are exposed in this dataset
