# Age-Gender-Prediction
This code is an attempt to implement a model as proposed by the paper "Age and Gender Prediction From Face Images Using Attentional Convolutional Network" https://arxiv.org/abs/2010.03791, which is a multi-task learning framework to jointly predict the age and gender of individuals from their face images. The idea is to develop an ensemble of Attentional CNN model and a Resnet model(Residual network). 

I took inspiration from multiple sources as cited below:

- Attention CNN model https://bit.ly/3KLDuG0

- Resnet-34 Model code is taken from the book: "Hands-on Machine Learning with Scikit-Learn, Keras & TensorFlow" by Aurélien Géron at page 478. Also referred https://datasciencemystic.com/custom-resnet-34-model-for-image-classification/ for understanding and customizing resnet models

- To understand and experiment using simple CNN models https://www.analyticsvidhya.com/blog/2021/07/age-and-gender-detection-using-deep-learning/

Data-set:
For this project I have used the UTK image data-set cropped version

https://susanqq.github.io/UTKFace/
