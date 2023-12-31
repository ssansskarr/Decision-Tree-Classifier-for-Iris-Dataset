# Decision-Tree-Classifier-for-Iris-Dataset
This repository implements a decision tree classifier for the Iris dataset. It consists of two parts:

1. Printing the Decision Tree Steps: In this part, the code prints the steps of the decision tree construction process, including information about the splitting decisions and class counts at each node.

2. Decision Tree Implementation: The code builds an actual decision tree for the Iris dataset and then prints the tree structure.

## Project Structure

The project is organized as follows:
- `decision_tree.ipynb`: Contains the implementation of the DecisionTree class and other necessary functions for training the decision tree.
- `Logic.md`: Contains the logic and my approach to the problem, has explation of every function that I made in the implementation.
- `iris.csv`: The dataset file in CSV format.
- `README.md`: This file.

## Results

Running the example script will print the steps for constructing the decision tree for the Iris dataset. Each step includes information about the level, class counts, current entropy, and splitting decision.

The decision tree will be built based on the information gain measure, and the final tree structure will be displayed.
