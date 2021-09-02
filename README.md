1. ANN Model for MNIST DATA classification: 
Created an Artificial neural network for classification of mnist dataset using Keras. ANN model is really helpful in terms of multiclass classification with higher accuracy.  As the data has the images, so in data preprocessing we have to change its shape and then normalized the channel b/w 0 to 1. For model creation, we have to specify the input layer, hidden layer, and output layer. For that process, we also can use hyper-tuning. To calculate the performance of the model, I've used a classification and confusion matrix.

2.CNN- Car image with transfer learning:
Created a CNN model for car image classification using transfer learning. Transfer learning is the process where we use the pre-trained model for 1000 categories like VGG or ResNet. But I have not used a complete model because there was no use for that. I had to remove the layers other than we need and fit our data. This process is really effective in terms of accuracy and performance.

3. Fake news classifier:
Created a fake news classifier using Natural language processing and LSTM. NLP helped to extract the features from data and transform the data into vectors using embedding. The purpose behind using LSTM is because RNN doesn't have to ability to remember the previous data but LSTM has. That's why I've used LSTM for the model. We also can use bidirectional lastm.

4. Imbalanced data classification:
In the classification process, the balance of target data is really important. When the data is imbalanced then the model gets biased for a higher percentage class. To solve this issue I've used neural networks with some parameters like kernel = glorot_uniform. To calculate the performance I've used the ROC_AUC score.
