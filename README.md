# MNIST recognition using NN and CNN
A group project to build 2 neural network models to detect digits with different hyperparamters and activation functions to improve the performance.<br>
Then the regural NN and Convolutional NN results are compared based on the loss function and their accuracy.
## Dataset discribtion
The mnist_train.csv file contains the 60,000 training examples and labels. <br>
The mnist_test.csv contains 10,000 test examples and labels. <br>
Each row consists of 785 values: the first value is the label (a number from 0 to 9) and the remaining 784 values are the pixel values (a number from 0 to 255).

## Data Preprocessing

* Check null values
* Check homogenous
* Check duplicates
* Standarization for train and test of x
* Handel outliers

## Neural network implementation 
<ol>
  <li>Model architecture</li>
  <li>Compilation</li>
  <li>Training the model</li>
  <li>Evaluation</li>
  <li>Saving the model</li>
</ol>

## Convolutional Neural Network implementation 
<ol>
  <li>Prepare data for the model </li>
  <li>Model architecture</li>
  <li>Compilation</li>
  <li>Training the model</li>
  <li>Evaluation</li>
  <li>Saving the model</li>
</ol>

## Compare between ANN & CNN
* accuracy plot
* loss function plot
* precision, recall and f-score values
