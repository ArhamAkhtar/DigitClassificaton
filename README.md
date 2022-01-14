# DigitClassificaton
**Introduction:**

* The MNIST dataset is an acronym that stands for the Modified National Institute of Standards and Technology dataset.
* It is a dataset of 60,000 small square 28×28 pixel grayscale images of handwritten single digits between 0 and 9.

**Problem Statement:**
* Here our task is to make a model which identifies or predicts the handwritten digits by feeding attribute values to a model.

**Strategies used:**
* Dataset:
  - Each image of size 28x28
  - Total samples=70000
  - Train samples=60000
  - Test samples=10000
  -Output: 0-9

* Problem type:
  - Supervised Problem: The problem in which we are given a dataset which has target/dependent/labelled variable.Here we know for what we are building the model
  - Classification Problem: The problem where dataset contains categorical target variable.
  - Multi class classification problem: The problem where dataset contains categorical target, where categories are more than 2.
* Steps:
  - Normalized the dataset
  - Used Feed Forward Neural Network
        - The existence of one or more hidden layers enables the network to be computationally stronger
  - Hidden layer architecture-
    - 1 hidden layer
    - 128 units
    - Dense connection(each layer is connected to previous layer)
    - Relu activation layer
  - The probability that the current image belongs to which class is represented in each node
  - Adam is used because it chooses an adaptive learning rate
  - Sparse categorical cross entropy loss is used as we have 10 varying classes in the output.
* Evalution:
  - We have an array of size 10, the position with the highest probability is the required number. 






