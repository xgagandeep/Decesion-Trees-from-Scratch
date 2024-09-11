

# Decision Trees from Scratch

**Repository:** [xgagandeep/Decision-Trees-from-Scratch](https://github.com/xgagandeep/Decision-Trees-from-Scratch)  
**Date:** 2020  
**Language:** Python  
**Libraries:** NumPy, pandas, scikit-learn

## Overview

This project implements a decision tree algorithm from scratch in Python. It uses basic principles of decision trees to classify data based on certain features. The project also includes a comparison with scikit-learn's `DecisionTreeClassifier` and `RandomForestClassifier`.

## Features

- **Data Preparation**: Loads and preprocesses data from a CSV file.
- **Entropy Calculation**: Implements entropy calculation to measure the impurity of the dataset.
- **Information Gain**: Computes information gain to determine the best feature to split on.
- **Decision Tree Training**: Trains a decision tree classifier from scratch.
- **Prediction**: Predicts classes for new data based on the trained decision tree.
- **Comparison**: Compares the custom decision tree implementation with scikit-learn's built-in classifiers.

## How It Works

1. **Data Loading**: Loads data from a CSV file and preprocesses it by encoding categorical features and handling missing values.
2. **Entropy Calculation**: Defines a function to calculate entropy for a given feature.
3. **Splitting Data**: Implements a function to split the dataset based on a feature and its value.
4. **Training**: Implements the decision tree algorithm, including training and node splitting.
5. **Prediction**: Defines a function to predict the class of new data based on the decision tree.
6. **Comparison**: Uses scikit-learn's decision tree and random forest classifiers for comparison.

## Files

- `Decision Trees.ipynb`: Jupyter Notebook containing the implementation of the decision tree algorithm from scratch and comparisons with scikit-learn classifiers.

## How to Use

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

4. Run the cells in the notebook to see the decision tree algorithm in action.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
