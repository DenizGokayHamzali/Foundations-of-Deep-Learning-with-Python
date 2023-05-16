# Image Classification using Convolutional Neural Network (CNN)

This project demonstrates the use of Convolutional Neural Networks (CNN) to classify images from the CIFAR-10 dataset. The CIFAR-10 dataset consist of 60000 images in 10 different classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

The CNN architecture used in this project consists of three convolutional layers followed by max-pooling layers, and two fully connected layers. The final layer uses a softmax activation function to output class probabilities.

## Conclusion

The trained model indicated its ability to classify images from the CIFAR-10 dataset with moderate accuracy. 

Overall, this project demonstrates the effectiveness of CNNs in image classification task and provides a starting point for further research and development in this area.

## Model Performance

The model achieved an accuracy of 71.15% on the test data, indicating its ability to correctly classify images into their respective classes.

To validate the model's performance further, we tested it on a sample image, which resulted in a probability score of 0.9893 for class 8. This indicates a high confidence level in the model's prediction for that particular image.

While the achieved accuracy is promising, there is still room for improvement. Fine-tuning the model's architecture, adjusting hyperparameters, increasing the training duration, or exploring advanced tehniques like transfer learning could potentially lead to better performance.

In brief, the model's performance demonstrates its ability to classify CIFAR-10 images, but further optimizations can unlock even better results.

### Built With
- [Python](https://www.python.org/)

## Requirements
To run this project, you will need Python 3 installed, as well as the following libraries:

- [TensorFlow](https://www.tensorflow.org/)
- [Numpy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)

## Installation
Clone the repo.

git clone https://github.com/DenizGokayHamzali/Foundations-of-Deep-Learning-with-Python.git

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Contact

Deniz Gökay Hamzalı

<denizgokayhamzali@gmail.com>
