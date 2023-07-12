
# Real Time Face Mask Detector using Tensorflow ,Keras and OpenCv

* Collected images from kaggle  (*link given below*).
* Manual Data cleaning for bteer accuracy.

* Converted images to array and splited the data in training and testing using sklearn library.
* Architecture of CNN model made using Tensorflow,Keras.

    * 2 convolutional layers with ‘relu’ activation function and kernel size of 3X3  followed by a Max Pooling layer.
    * 1 fully connected deep hidden layers with ‘relu’ activation function.
    * 95% testing accuracy
    * Softmax activation function for the output layer.
    * Loss function: sparse categorical crossentropy
    * Optimizer : Adam
    * 95% training accuracy
* Real time detection using OpenCv-Python.



## 🔗 Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/)

**kagle data set:** https://www.kaggle.com/datasets/omkargurav/face-mask-dataset


## 🛠 Skills
Machine learning, Deep learning,OpenCV,Jupyter Notebook

## Lessons Learned

* Always scale the images between 0 and 1 for best accuracy.
* Use softmax activation function followed by sparse categorical crossentropy loss function as far as possible in the output layer.
* Try with different architectures of the model.
