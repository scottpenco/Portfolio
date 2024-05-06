# Convolutional Neural Networks: Street View Housing Number Digit Recognition

![picture](https://assets-news.housing.com/news/wp-content/uploads/2020/07/07084351/House-number-numerology-Significance-of-house-number-6-FB-1200x700-compressed.jpg)

The SVHN dataset contains over 600,000 labeled digits cropped from street-level photos. It has been used in neural networks created by Google to improve map quality by automatically transcribing the address numbers from a patch of pixels. The transcribed number with a known street address helps pinpoint the location of the building it represents.

In this project 2 CNN were built. The first CNN returned a model that overfit on our training data, to rectify this a second model was built with drop-out. Implimenting drop-out layers into our neural network helped prevent our model from overfitting and improved validation accuracy. The improvement incfeased from model 1's .85 validation accuracy to model 2 performing with .91 validation accuracy. 
