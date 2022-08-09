# 150Days_ML
![image](https://user-images.githubusercontent.com/75212387/176733601-f4cd4cd0-d550-4a13-9940-75c868904469.png)



## Days1 of 150Days

**Topic:**
- **Clustering**
- **Types of Clustering**
- **K-Means Clustering (implementation using sklearn)**

[K-Means Clustering Notebook](https://www.kaggle.com/code/poojapramanik/k-means-cluster)


## Days2 of 150Days
**Topic:**
- **Regression**
- **Logistic Regression**
- **Difference between Linear Regression and Logistic Regression**
- **Logistic Regression( implementation using sklearn)**

 [Logistic Regression Notebook](https://www.kaggle.com/poojapramanik/logistic-regression)

![image](https://user-images.githubusercontent.com/75212387/178862939-55e20bee-8a0b-4d14-b384-3d3bc876d31e.png)
![image](https://user-images.githubusercontent.com/75212387/178863146-323c490c-b38f-4bae-bd1d-5627012270ae.png)

![image](https://user-images.githubusercontent.com/75212387/178863747-f6376747-e931-4bb6-a544-580cf88959f0.png)

![image](https://user-images.githubusercontent.com/75212387/178864642-eb0cbb8c-f897-4163-95bd-e30c434f38f1.png)

There is a threshold value 0.5. So if the value point will be >= 0.5 than the outcome must be 0 or if the value point will be <= 0.5 than the outcome must be 1 **For example:- if my value point is at 0.8 than in this case this Logistic Regression Model will predict the outcome as 1**

![image](https://user-images.githubusercontent.com/75212387/178866648-4ac5a3dc-f9aa-433d-a513-7b762bd63968.png)


## Days3 of 150Days

**Topic:**
- **Linear Regression**
- **Simple Linear Regression**
- **Simple Linear Regression( implementation using sklearn)**

What is Linear Regression?

Linear regression is about learning the relationship between the dependent and independent variables from a pile of historical data.

linear regression is about fitting data to minimize the sum of residual between each point and the predicted value. As shown in the figure below, the red line is the model we solved, the blue point is the original data, and the distance between the point and the red line is the residual. Our goal is to minimize the sum of residuals.

![image](https://user-images.githubusercontent.com/75212387/181803786-1b7b3b64-28be-4fbe-bf21-e7312166aa79.png)


[Simple Linear Regression Notebook](https://www.kaggle.com/code/poojapramanik/simple-linear-regression)


## Days4 of 150Days

**Topic:**
- **Multiple Linear Regression**
- **Type of Linear Regression**
- **Multiple Linear Regression( implementation using sklearn)**

[Multiple Linear Regression Notebook](https://www.kaggle.com/code/poojapramanik/linear-regression)

![image](https://user-images.githubusercontent.com/75212387/179143399-f3f40fb5-d0ef-4b58-b77f-43b81ca1ce73.png)
**What is R square**
![image](https://user-images.githubusercontent.com/75212387/179143884-662a96e2-f337-4501-bb89-a2c25add708a.png)

![image](https://user-images.githubusercontent.com/75212387/179143771-061b7dcd-2a34-46e9-a8f5-2596fa692286.png)


## Days5 of 150Days

**Topic:**
- **KNN Classifiaction**
- **KNN Classification( implementation using sklearn)**

[KNN Classification Notebook](https://www.kaggle.com/code/poojapramanik/knn-classification)


## Days6 of 150Days

**Topic:**
- **Decision Tree**
- **Decision Tree( implementation using sklearn)**

[Decision Tree Notebook](https://www.kaggle.com/code/poojapramanik/decision-tree)

## Days7 of 150Days

**Topic**
- **Introduction to Keras**
- **Architecture of Keras**

Keras is an open source deep learning framework of python.
It is created by an artificial researcher at google named Francois Chollet.
Keras provides a complete framework to create any type of neural networks.

Keras runs on top of open source machine learning libraries like Tensorflow, Theano and CNTK(Cognitive Toolkit)
 i) Theano is  a python library for fast numerical computational task.
 ii) CNTK is a deep learning framework created by Microsoft.
 iii) Tensorflow is an open source machine learning library used for numerical computational task created by google.
    
    
Deep learning involves analyzing the input in layer by layer manner, where each layer progressively extracts higher level 
information about the input.

For example :- 
Let us take a simple scenario of analyzing an image. Let us assume that your input image is divided up into a rectangular 
grid of pixels. Now, the first layer abstracts the pixels. The second layer understands the edges in the image. The Next 
layer constructs nodes from the edges. Then, the next would find branches from the nodes. Finally, the output layer will 
detect the full object. Here, the feature extraction process goes from the output of one layer into the input of the next 
subsequent layer.

**There are 3 main category of Keras Architecture**

**1) Model**
**2) Layers**
**3) Core Modules**

Using Keras model, Keras Layer, and Keras modules, any ANN algorithm (CNN, RNN, etc.,) can be represented in a simple and efficient manner.

**Keras Models are of 2 types**
1) Sequential Model 2) Functional API

## Days8 of 150Days

**Topic**
- **Introduction to ANN(Artificial Neural Network)**

![image](https://user-images.githubusercontent.com/75212387/182507105-1622bece-d9db-47cf-9986-86d0905237fa.png)


As the human brain is made up of more than 90 billion tiny cells called “Neurons”. Neurons are inter-connected through nerve 
fiber called “axons” and “Dendrites”. The main role of axon is to transmit information from one neuron to another to which 
it is connected.

Similarly, the main role of dendrites is to receive the information being transmitted by the axons of another neuron to 
which it is connected. Each neuron processes a small information and then passes the result to another neuron and this 
process continues. This is the basic method used by our human brain to process huge about of information like speech, 
visual, etc., and extract useful information from it.

The first Artificial Neural Network (ANN) was invented by psychologist Frank Rosenblatt, in the year of 1958. 

How ANN works?
The input layer receives the input data and the data goes through one or more hidden layers sequentially and finally 
the output layer predict something useful about the input data. For example, the input may be an image and the output 
may be the thing identified in the image, say a “Cat”.

A single neuron (called as perceptron in ANN)

**There are 3 main topic associated with ANN**
1) Forward Propogation 2) Backprogation 3) Activation Functions

**Data flow in an ANN**
We are aware that an ANN architecture consists of 3 major components - The input layer, The hidden layers, and the output layers. 

The input layer, as the name gives out, receives and preprocesses the input, which is then sent out to the hidden layer. This is where most of the work is done. After making the computations, the results are then passed on to the output layer. This makes the first part of a single training iteration. **This is called Forward Propagation.** After the output layer receives the data, the generated results are then compared with the actual outputs, and the error is reduced based on the feedback that’s received. **This is known as Backpropagation.**

**Definition of activation function:-**

Activation function decides, whether a neuron should be activated or not by calculating weighted sum and further adding bias with it.

**Examples of Activation Function are:-**

**1) Sigmoid-**

![image](https://user-images.githubusercontent.com/75212387/182511915-98dcf8d0-1431-4db1-89df-dc924bda2aa6.png)

Sigmoid is most popular activation function used in binary classification problem statement or output layer of ANN. Sigmoid calculation will give output between 0 to 1. So if number calculated by Sigmoid activation function is near to 0 then next neuron in ANN will not be activated and if it is near to 1 then next neuron will be get activated.

**2)  RELU-**

![image](https://user-images.githubusercontent.com/75212387/182512831-c753df5e-cff5-45fb-80a8-382b95769761.png)

Stands for Rectified linear unit. It is the most widely used activation function. Chiefly implemented in hidden layers of Neural network.

Equation :- A(x) = max(0,x). It gives an output x if x is positive and 0 otherwise.

![image](https://user-images.githubusercontent.com/75212387/182521987-3268467f-7cf8-4f63-834d-ed4932359ba3.png)

![image](https://user-images.githubusercontent.com/75212387/182522002-58bb5762-829a-4d1b-a5af-d30e81c0d7ff.png)

![image](https://user-images.githubusercontent.com/75212387/182522086-4968d32b-d5f7-4356-8f26-53bd9a77940c.png)


## Days9 of 150Days

**Topic**
- **Introduction to CNN(Convolutional Neural Network)**


![image](https://user-images.githubusercontent.com/75212387/178396361-4be51041-4541-4189-a634-455ed7ab4a81.png)




**What is Feature Selection?**

In Machine Learning, Feature selection means Attribute Selection for use in model construction. **Importance of Feature Selection** 1) To reduce the training time 2) To avoid the curse of dimensionality.

**There are many ways to do feature selection** 

**1)Remove feature with low variance** It means that this feature has only one value and all instances share the same value on this feature. In other words, this feature does not have any information and contributes nothing to the prediction of the target. Similarly, those features with low variance have little information about the target, we could remove them without reducing the performance of the model.

![image](https://user-images.githubusercontent.com/75212387/181802092-830a1ad0-aab0-40c2-87d5-e79f60314658.png)

## Days10 of 150Days

**Topic**
- **Overfitting**
- **Underfitting**

Overfitted model gives high accuracy on the training set (sample data) but fails to achieve good accuracy on the test set.

Before understanding overfitting, we need to know some basic terms, which are:

Noise :- Irrelevant data

Bais :- It is a prediction error. means difference between actual and predicted value.

Variance :- perform well in training dataset but fails to perform well on test data.

Generalization: It shows how well a model is trained to predict unseen data.

NOTE :- An overfitted model is said to have low bias and high variance.

Example :- Y has a good memory, hence memorized the whole book. Student Y will only be able to solve questions if they appear exactly the same as given in the book.
Suppose the model learns the training dataset, like the Y student. They perform very well on the seen dataset but perform badly on unseen data or unknown instances. In such cases, the model is said to be Overfitting.

**Ways to prevent the Overfitting**

- Early Stopping

- Train with more data

- Feature Selection

- Cross Validation

- Regularization

- Ensemble Method

[Resources to learn how to prevent Overfitting](https://www.javatpoint.com/overfitting-in-machine-learning)

**Underfitting**

In underfitting,the model is not able to learn enough from the training data and hence it reduces the accuracy and produces the unreliable data.

An underfitted model has high bias and low variance.

**How to avoid underfitting**:
- By increasing the training time of the model.
- By increasing the number of features.
