
# Ball Type Classification Case Study

This folder contains a simple machine learning case study for classifying objects based on their weight and surface type as either a tennis ball or a cricket ball. This project is created for learning purposes and is suitable for beginners in machine learning.

## Dataset

The dataset used in this case study consists of 10 training samples with the following features:
- **Weight**: The weight of the object in grams.
- **Surface**: The type of surface of the object (1 for rough, 0 for smooth).

### Features and Labels

- **Features**:
- [[35, 1], [47, 1], [90, 0], [48, 0], [90, 0], [35, 1], [92, 0], [35, 1], [35, 1], [35, 1]]
- **Labels**:
- [1, 1, 2, 1, 2, 1, 2, 1, 1, 1]
### Implementation

The code uses a Decision Tree Classifier from the `scikit-learn` library to classify the objects.

### Classifier Function

The `Classifier` function takes two parameters: `weight` and `surface`. It encodes the features and labels, trains a decision tree model, and predicts
