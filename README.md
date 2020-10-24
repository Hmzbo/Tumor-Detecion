# Tumor detection problem using a feed-forward neural network implemented from numpy scratch

In this project, we're going to implement a Feed-Forward Neural Network (FFN) also called a Multi-Layer Perceptron neural network (MLP) and use it in a brain tumor classification problem. For the MLP implementation we're mainly going to use the Numpy library, which is well known for fast multidimensional array and linear algebra calculations.

The results obtained by the trained MLP model will then be compared to the ones obtained by an Xgboost model which is one of the best machine learning algorithms for classification and regression tasks in terms of accuracy, speed, and memory consumption.

**Note:** The MLP model will be trained using the unstructured data (Images), while then xgboost model will be train on the structured data (Tabular data).

The data that we're going to use is provided by [Jakesh Bohaju](https://www.kaggle.com/jakeshbohaju) on [Kaggle](https://www.kaggle.com/jakeshbohaju/brain-tumor).

This is a brain tumor feature dataset including five first-order features and eight texture features with the target level (in the column Class).

1. First Order Features
    - Mean
    - Variance
    - Standard Deviation
    - Skewness
    - Kurtosis


2. Second Order Features
    - Contrast
    - Energy
    - ASM (Angular second moment)
    - Entropy
    - Homogeneity
    - Dissimilarity
    - Correlation
    - Coarseness

**Image** column defines image name and **Class** column defines either the image has tumor or not (1 = Tumor, 0 = Non-Tumor)
