# Deep-Learning Notebooks using TensorFlow.

These notebooks are used in Udacity\Google course :
* 1_notmnist.ipynb
* 2_fullyconnected.ipynb
* 3_regularization.ipynb
* 4_convolutions.ipynb
* 5_word2vec.ipynb
* 6_lstm.ipynb

<h2>Summary<h2>

*1_notmnist.ipynb*

Logistic regression (this one via scikit-learn) => 87% score on test dataset
<br><br>

*2_fullyconnected.ipynb*

Logistic regression => 83%
Logistic regression with SGD => 86%
Fully connected with 1 hidden layer and ReLU => 88%
<br><br>

*3_regularization.ipynb*

Adding L2 regularization to Logistic Regression => 88%
Adding L2 regularization to NN => 92%
Replacing L2 regul by dropout on NN => 87%
<br><br>

*4_convolutions.ipynb*

Conv > ReLU > Conv > ReLU > FullyConnected > ReLU > FullyConnected => 90%
Conv > MaxPool > ReLU > Conv > MaxPool > ReLU > FullyConnected > ReLU > FullyConnected => 89%
Conv > ReLU > MaxPool > Conv > ReLU > MaxPool > FullyConnected > ReLU > FullyConnected => 91%
Conv > ReLU > MaxPool > Conv > ReLU > MaxPool > DropOut > FullyConnected > ReLU > DropOut > FullyConnected => 94.2%

---

Karpathy_Simple_RNN.ipynb is a minimal RNN using the input.txt dataset.

---

Simple_TF_1.ipynb is a trivial tensorflow classification example.
