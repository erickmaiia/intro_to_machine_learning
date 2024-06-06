# Introduction to Machine Learning

### Basic Data Exploration

Before training a Machine Learning model, it is essential to understand your data. Basic data exploration includes:

- **Data Visualization:** Graphs and plots to visualize distributions and relationships between variables.

- **Descriptive Statistics:** Mean, median, standard deviation, etc.

- **Data Cleaning:** Handling missing values, removing duplicates, and correcting inconsistencies.

### Model Validation

Validation is crucial to ensure that the model performs well on unseen data. Common techniques include:

- **Data Splitting:** Separating the data into training and testing sets.

- **Cross-Validation:** Dividing the data into multiple parts and training the model multiple times, using different parts as the test set each time.

#### Mean Absolute Error (MAE)

A common metric used to evaluate the accuracy of a regression model. It measures the average magnitude of the errors between the predicted values and the actual values, without considering their direction.

- **Advantages:** Simple to understand and interpret, and it provides a clear indication of the average error.

- **Disadvantages:** MAE does not penalize large errors more than small ones, unlike other metrics like Mean Squared Error (MSE).

### Underfitting & Overfitting

- **Underfitting:** Occurs when the model is too simple and fails to capture the complexity of the data. Results in poor performance on both training and test sets.

- **Overfitting:** Occurs when the model is too complex and fits too closely to the training data, capturing even the noise. Results in high performance on the training set but poor performance on the test set.

### Classifiers: Random Forests and Decision Trees

#### Decision Tree

- **Definition:** A model that makes decisions in a tree structure, where each node represents a question about an attribute.

- **Advantages:** Easy to understand and interpret, good for decision visualization.

- **Disadvantages:** Can easily overfit if not pruned properly.

#### Random Forest

- **Definition:** An ensemble of multiple decision trees, where each tree is trained on a random sample of the data.

- **Advantages:** Reduces the risk of overfitting compared to a single decision tree, robustness, and better generalization.

- **Disadvantages:** More complex and slower to train and predict compared to a single tree.