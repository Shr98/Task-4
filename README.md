# Task-4 Prediction using Decision Tree Algorithm
 Decision Tree is a supervised algorithm used in machine learning. It is using a binary tree graph (each node has two children) to assign for each data sample a target value. The target values are presented in the tree leaves. To reach to the leaf, the sample is propagated through nodes, starting at the root node. In each node a decision is made, to which descendant node it should go. A decision is made based on the selected sample’s feature. Decision Tree learning is a process of finding the optimal rules in each internal tree node according to the selected metric.

The decision trees can be divided, with respect to the target values, into:

*Classification trees* used to classify samples, assign to a limited set of values - classes. In scikit-learn it is DecisionTreeClassifier.
*Regression trees* used to assign samples into numerical values within the range. In scikit-learn it is DecisionTreeRegressor.
Decision trees are a popular tool in decision analysis. They can support decisions thanks to the visual representation of each decision.

There are 4 ways to visualize Decision Tree in Python:

1) print text representation of the tree with sklearn.tree.export_text method
2) plot with sklearn.tree.plot_tree method (matplotlib needed)
3) plot with sklearn.tree.export_graphviz method (graphviz needed)
4) plot with dtreeviz package (dtreeviz and graphviz needed)

In the following code I have used the plot_tree method to visualize the Decision Tree.
