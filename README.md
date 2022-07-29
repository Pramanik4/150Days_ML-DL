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
- **Simple Linear Regression**
- **Simple Linear Regression( implementation using sklearn)**

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

## Days9 of 150Days

**Topic**
- **Introduction to CNN(Convolutional Neural Network)**


![image](https://user-images.githubusercontent.com/75212387/178396361-4be51041-4541-4189-a634-455ed7ab4a81.png)




**What is Feature Selection?**

In Machine Learning, Feature selection means Attribute Selection for use in model construction. **Importance of Feature Selection** 1) To reduce the training time 2) To avoid the curse of dimensionality.**There are many ways to do feature selection** 

**1)Remove feature with low variance** It means that this feature has only one value and all instances share the same value on this feature. In other words, this feature does not have any information and contributes nothing to the prediction of the target. Similarly, those features with low variance have little information about the target, we could remove them without reducing the performance of the model.
