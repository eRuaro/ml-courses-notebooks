## Methodologies

1. High Bias -> Underfitting, high performance on dev data, subpar performance on training data
2. High Variance -> Overfitting, high performance on training data, subpar performance on dev data
3. High Variance & High Bias -> Worst
4. Low Bias & Low Variance -> Best

## Basic Recipe for Machine Learning 

After training your initial model, check the performance of the model.
1. Model has high bias?
   - Create bigger network
   - Train for longer
   - Try different NN architectures
2. Model has high variance?
   - Need more data
   - Try regularization
   - Try different NN architectures

## Regularization

Regularization helps in reducing overfitting.

Regularization Methods:
1. Dropout
2. Data Augmentation
3. Early Stopping (Callbacks)

## Speeding up training

You can speed up NN training by normalizing the input data (training data)