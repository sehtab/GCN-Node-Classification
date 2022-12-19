# GCN-Node-Classification


https://colab.research.google.com/drive/1y9cl3B_gHUm_mzWmVumUnpe88RAI4IIY?usp=sharing 

# Objective:

The objective of this ICP is to GCN Node Classification.

# Approaches

At first, necessary libraries are imported. Sample data are implemented to make graphical network and after that the graph network 
is analyzed with Multi Layer Perceptron, CNN and GNN.

# Datasets

For this ICP, datasets are Karate dateset and MLP dataset.

# Results:

Results are generated with several libraries and accuracy is compared with several algorithm like MLP, CNN and GCN. Dropout rate and hidden layer are varied. 
Dropout rate is varied from 0.5 to 0.6 and hidden layer. Here are are the results:

                                                   MLP(Test_acc)   MLP(val_acc)    CNN(test_acc) CNN(val_acc)   GCN(test_acc)   GCN(val_acc)
           (Dropout=0.6, Hidden layer= 8)              49.6%          24.5%          47.7%        49%                77.2%       75%
           (Dropout = 0.5, Hidden layer=16)             59%           29.6%          48.2%        49.2%              76.9%       74.8%
      ---------------------------------------------------------------------------------------------------------------------------------------------------
                                                         Test_acc         Val_acc
                     GATConv                               75.6%           74%

# Challenges

For this icp, GATConv is not working..

# Planned Work

At first, necessarry library is installed and Graphical network is created. Then the network is analyzed with MLP, CNN and GCN. Hidden layer and dropout is varied and 
accuracy is compared for testset and validation set. 
