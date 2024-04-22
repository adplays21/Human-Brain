# Human-Brain
Human Brain Detection on Fashion MNIST Dataset with TensorFlow
---

## Fashion MNIST Classification with TensorFlow

### Overview
This repository contains code for training a deep learning model to classify fashion items using the Fashion MNIST dataset. Fashion MNIST is a dataset of Zalando's article images, consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. The goal is to train a model that can accurately classify these images into their respective categories.

### Features
- **Model Architecture**: The classification model is built using TensorFlow's Sequential API, consisting of a flatten layer and a dense layer.
- **Data Preprocessing**: The images are preprocessed by flattening them into a 1D array and normalizing pixel values to range between 0 and 1.
- **Training and Evaluation**: The model is trained using the Adam optimizer and Sparse Categorical Crossentropy loss function. Training progress and evaluation metrics such as accuracy are logged.
- **Visualization**: Jupyter notebooks are provided for data exploration, model training, and visualization of results.


The classes are:
Label	  Description
0	     T-shirt/top
1    	  Trouser
2	     Pullover
3	     Dress
4	     Coat
5	     Sandal
6	     Shirt
7	     Sneaker
8	     Bag
9	     Ankle boot


1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
2. Run the code in the `Human Brain` directory for data exploration, model training, and visualization.

### Dataset
The Fashion MNIST dataset used in this project can be accessed through TensorFlow's Keras API. It is a drop-in replacement for the original MNIST dataset and is commonly used for benchmarking machine learning algorithms.

### References
- [Fashion MNIST dataset on TensorFlow](https://www.tensorflow.org/api_docs/python/tf/keras/datasets/fashion_mnist)
- [NumPy documentation](https://numpy.org/doc/stable/index.html)

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Contributors
- Adan Bari

### Contact
For questions or feedback, please contact me at adanbari444@gmail.com.

--- 
