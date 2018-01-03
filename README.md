# Digit-Classification

## Data
Images of numbers convered to text for easier classification.  Each character represents a single "pixel" and an ixj image has i*j pixels.
Data is split into training and testing sets with associated labels.

## Multiclass Non-differentiable Perceptron 
Using a multiclass perceptron learning algorithm to learn the weights of each digit to correctly classify the testing data with above 80% accuracy.
* Weights are initialized using a normal distribution
* Bias is initialized at 1
* Epochs: 40
* Alpha: 0.5

## K Nearest Neighbors 
Using a k nearest neighbors learning algorithm correctly classify the testing data with above 80% accuracy based on similarity function.
* Similarity function: Euclidien distance
* K: 5
