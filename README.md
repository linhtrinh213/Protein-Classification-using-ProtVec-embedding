# Description
In this assignment*, protein sequences are broken into overlapping 3-mers, which are then mapped to their corresponding ProtVec embeddings (https://arxiv.org/abs/1503.05140). These embeddings were used to train various machine learning classifiers, including Random Forest, SVM, and a simple neural network (a fully connected model with two hidden layers of 128 and 64 neurons using ReLU activation). All models achieved good accuracy, with the neural network performing particularly well (97%).

Two methods for generating ProtVec embeddings — summing and averaging 3-mer embeddings — were compared, showing no significant difference in model performance.


# Data 
The dataset is sourced from the original ProtVec publication: http://dx.doi.org/10.7910/DVN/JMFHTN

*This assignment was completed as part of the DeepLife course: https://deeplife4eu.github.io/program.