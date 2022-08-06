# Introduction-to-TensorFlow-for-Artificial-Intelligence-Machine-Learning-and-Deep-Learning-Coursera
Introduction to TensorFlow for Artificial Intelligence, Machine Learning, and Deep Learning
1.Week  2 Quiz
Question 1
What is the resolution of o the 70,000 images from the Fashion MNIST dataset?
28x28 Greyscale

Why are there 10 output neurons in the Neural Network used as an example for the Computer Vision Problem?
There are 10 different labels

Exactly! There are 10 output neurons because we have 10 classes of clothing in the dataset. These should always match.
What does Relu do?

It only returns x if x is greater than zero

Correct
Correct! The rectifier or ReLU (Rectified Linear Unit) activation function returns x if x is greater than zero.

Why do you split data into training and test sets?

1 / 1 point

To test a network with previously unseen data
Nailed it! Splitting the data into training and test seat allows you to test the network with unseen data.

Question 5
True or False: The on_epoch_end function sends a logs object with lots of great information about the current state of training at the start of every epoch

1 / 1 point

False
Correct
Absolutely! The function activates at the end of every epoch

Why do you set the callbacks= parameter in your fit function?

So, on every epoch you can call back to a code function
Correct
That’s right! You can have it check the metrics and stop the training.



