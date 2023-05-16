# IMDB Review Sentiment Analysis using LSTM (RNN)

This project utilizes LSTM networks to perform sentiment analysis on the IMDB movie review dataset, aiming to predict the sentiment (positive or negative) based on the text content. The dataset consist of 50,000 movie reviews.

The code loads the IMDB dataset using Keras and preprocesses it by selecting the top 10,000 frequently used words.

## Conclusion

As a result, the LSTM based model achieved impressive results, showcasing its ability to predict sentiment with a high degree of accuracy. By training for 5 epochs, the model attained a validation accuracy of 90.58% and effectively learned the underlying patterns in the data.

Overall, this LSTM based model proves to be a robust solution for sentiment analysis task on movie reviews, highlighting its potential for application in various natural language processing projects.

## Model Performance

Evaluating the model on the test set yielded an accuracy of 90.02% and a loss of 0.2435. These results indicate that model can accurately classify movie reviews as positive or negative. 

For instance, when predicting the sentiment of a sample test review, the model correctly identified a negative sentiment with a prediction score of 0.0424 (Closer to 0 means negative sentiment, closer to 1 means positive sentiment).

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
