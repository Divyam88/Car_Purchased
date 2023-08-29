# Car_Purchased

# About Dataset
Link: https://www.kaggle.com/datasets/gabrielsantello/cars-purchase-decision-dataset

**Columns:**
User ID,
Gender,
Age,
Annual Salary,
Purchase Decision (No = 0; Yes = 1)

# About the project
The project uses decision tree to predict. Two decision tree is created with gini and entropy criterion. 
The prediction will help in understanding the trends and pattern in which people buy car.
Graphviz is a package used for drawing decision tree graph. [Gini.png](https://github.com/Divyam88/Car_Purchased/blob/main/gini.png)
and [entropy.png](https://github.com/Divyam88/Car_Purchased/blob/main/entropy.png) contains the images 
which visualizes the decision tree using graphviz. 

# Model in use
Decision tree is a supervised learning which is widely used for classification and regression. The model tends to ask
a series of if/else questions in a hierarchal order. A tree like-structure is created which consist of a root node , branches and leaf node.
The goal of decision tree is to create a pure subset and to do so root node is splits into branch nodes and then to leaf node.

**Leaf node**
Leaf nodes are terminal nodes which contains the result. In a classification tree, each leaf node represents a class label,
while in a regression tree, it represents a numerical value

**Purning**
After the tree is built, you can prune it to remove branches that do not significantly contribute to improving the model's performance. 
Pruning helps prevent overfitting.
There are two types of purning:
1) Pre-Purning
2) Post-Purning

**Entropy**
Entropy is a fundamental concept used to measure the impurity or uncertainity in the given dataset. Information gain computes the 
difference between entropy before split and average entropy after split of the dataset based on given attribute values.

**Information Gain = Entropy(Parent_node) - Entropy(Child_node)**

**Entropy, H(t) = -Σp(i|t) log[p(i|t)]**

**Gini index**
Gini index is a measurement of impurity used in decision tree algorithm.
It helps to decide hwo to split the data into subsets during the training process.

**Gini(D) = 1- Σ(pi)^2**



