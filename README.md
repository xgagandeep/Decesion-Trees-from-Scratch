

# Decision Trees from Scratch

This repository provides an implementation of decision trees from scratch using Python. The implementation is designed to demonstrate the core concepts of decision trees, including entropy, information gain, and recursive tree building, without relying on specialized machine learning libraries.

## Project Overview

The notebook `Decision Trees.ipynb` implements a basic decision tree classifier from scratch. The key steps involved include:

1. **Data Preprocessing**: Cleaning and preparing the dataset for training. This includes handling missing values and encoding categorical variables.

2. **Entropy Calculation**: Computing the entropy of the dataset, which is a measure of impurity or disorder.

3. **Information Gain**: Calculating the information gain for each feature to determine the best feature to split on.

4. **Tree Construction**: Building the decision tree recursively based on the information gain and stopping criteria.

5. **Prediction**: Using the constructed decision tree to make predictions on new data.

6. **Evaluation**: Comparing the performance of the custom decision tree implementation with the Scikit-Learn DecisionTreeClassifier and RandomForestClassifier.

## Features

- **Custom Decision Tree**: A decision tree classifier implemented from scratch.
- **Data Preprocessing**: Includes handling missing values and encoding categorical features.
- **Entropy and Information Gain**: Functions to calculate entropy and information gain for decision tree splits.
- **Evaluation**: Comparison with Scikit-Learn's DecisionTreeClassifier and RandomForestClassifier.

## Getting Started

To run the notebook and explore the implementation, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/xgagandeep/Decision-Trees-from-Scratch.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Decision-Trees-from-Scratch
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Decision\ Trees.ipynb
   ```

4. Follow the instructions in the notebook to run the code and understand the decision tree implementation.

## Requirements

Ensure you have Python and the following libraries installed:
- NumPy
- pandas
- scikit-learn

You can install the required libraries using:
```bash
pip install numpy pandas scikit-learn
```

## Example

An example of how to use the decision tree implementation to train on a dataset and make predictions is provided in the notebook.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.


Feel free to modify or extend this README based on additional details or requirements!
