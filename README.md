# handwritten-digit-recognition
This project focuses on building a neural network models using 
python libraries such as scikit-learn, NumPy, 
Keras/ Pytorch and matplotlib to recognisze hand written digits



**Dataset**

The [Optical recognition of handwritten digits dataset](https://scikit-learn.org/stable/datasets/toy_dataset.html#digits-dataset) 
has been used to build this project. This dataset consists of 8x8 grayscale images of hand-written digits sorted into 0-9 
classes. 




**Libraries**

1. Scikit-learn has been used to obtain
the dataset and split the data into training and test sets

2. NumPy has been used to perform matrix and vector operations

3. Keras has been used to construct and train a neural network

4. Matplotlib has been used to view images of the digits

**Steps**

1. First we split the dataset into training and test sets, then train a fully-connected neural network to recognize the digits.
2. Next, we change the architecture and parameters to see how they influence the test score.
3. Once we are satisfied with our model's performance, we dump the trained weights and biases from the model as NumPy arrays for each layer. 
4. Next, we implement forward propagation using NumPy.
5. Then, we compute the training and test accuracies produced by our code in step (2) and compare it to those reported for the model in step (1).
6. Finally, we verify our code’s predictions by plotting images for several results in each class.
