**Project Overview**

This project implements a custom decision tree classifier from scratch using Python in a Jupyter Notebook. The objective is to classify mushrooms as edible or poisonous based on their attributes. The Mushroom Data Set from the UCI Machine Learning Repository serves as the training and testing dataset.

**Key Features**

Custom Decision Tree Implementation: No prebuilt decision tree packages are used. The implementation follows the basic decision tree procedures discussed in lectures, focusing on manually calculating information gain and recursively building the tree.

Data Preprocessing: Handles missing data by ignoring instances or replacing missing values with the column mean, alongside other preprocessing steps.

Complexity Control: Incorporates a stopping_depth parameter in the training procedure to control tree complexity and prevent overfitting.
Testing & Evaluation: Implements a test procedure that takes new data and the trained model to return predictions. Additionally, proposes and implements an evaluation method assessing the overall procedure's effectiveness.

**Decision Tree Visualization**

The project includes functionality to print the decision tree, helping visualize the if-then-else rules generated by the model.

**Evaluation and Reflection**

Model Evaluation: Discusses the outputs at different stopping depths (2, 3, and 4) to explore the effect of tree depth on performance.
Reflection: Considers the implications of changing the splitting criterion and how it affects the structure and accuracy of the decision tree. Reflects on whether the evaluation method effectively indicates overfitting or underfitting.
