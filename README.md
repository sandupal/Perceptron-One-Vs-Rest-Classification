# Perceptron-One-Vs-Rest-Classification

This problem is about classifying handwritten digits using the MNIST Database.
 http://yann.lecun.com/exdb/mnist/ To reduce  computation timee only the first 20,000 training images/labels 
 and only the first  2,000 testing images/labels have been used.
Each image is 28 X 28 pixels. An image can be viewed as a
 784-dimensional vector of pixel intensities. For each image, 1 appended to the beginning
 of each x-vector; this will act as an intercept term (for bias). Use the gradient descent
 algorithm for Perceptron derived in class, to classify given $x$ $R^{785}$ whether a digits label
 is k or if it is some other digit, i.e. $k \notin {0,....,9}$ . For instance, if classifying 2 ,
 then designate $y = 2$ as the positive class, and all other digits as the negative class.
 For each image, do this two-way classi cation for all 10 digits. Train 10 perceptrons
 that will collectively learn to classify the handwritten digits in the MNIST dataset. Each
 perceptron will have 785 inputs and one output.
