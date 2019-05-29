# Image_classification

The dataset contains some noisy images of the two classes (square and circle). Problem is to classify the images using any classification models. The file attached (dataset.mat) contains both train and test sets, where 200 image samples were provided for training and 100 image samples for testing. Each image is represented in an array using 24 x 24-pixel values. I used two classification models, one is k-NN and other is CNN to classify the images. The accuracy scores on the models were as follows.

For k-NN classifier::

![For k-NN classifier:](https://github.com/Harshasai1/Image_classification/blob/master/Knn.PNG)

Train accuracy is high when the K-value is 1 and low when K-value is 10. Test accuracy is high when K-value is 1 and low when K-value is 9. 


For CNN classifier:

![For CNN classifier:](https://github.com/Harshasai1/Image_classification/blob/master/Cnn.PNG)

Train and the test accuracies of the trained CNN model were presented in the above table. The model performed with 95% accuracy on the test set. 



