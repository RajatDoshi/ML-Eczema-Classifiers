# Machine Learning Projects
## 

## Created a Convolutional Neural Network for Eczema Classifer
I trained my own CNN to classify between six types of eczema. I collected over 3000 images for this project and then programmatically annotated each image with a numerical classification that correlates to what type of eczema it is. This dataset was broken into three portion: one for training, one for testing, and one for validation. In my CNN, there were nine layers in the network: seven hidden layers, an input layer, and output layer. I used an 'adam' optimizer from keras, and then did ten epochs with 20 steps per epoch when training the CNN to determine the weights and biases. Finally, I tested my model that I fit with my data on the validation set. While the accuracy was low (due to lack of high-quality data), I learned the ins and outs of using Keras to build a CNN. 

## Created a Recurrent Neural Network for Eczema Classifer
I used the ResNet-50 deep-learning model to train an RNN to classify 6 types of eczema. ResNet-50 is a CNN, has 50 layers in its network, and can classify over a 1000 images from the ImageNet. By using transfer learning, I improved the accuracy in comparison to training my own CNN, which didn't have enough high-quality images in the dataset to accurate train the model. 

## Created a Convolutional Neural Network for Pneumonia Detection
I trained a CNN to detect whether a patient has pneumonia given an x-ray scan of their chest. For this project, I leveraged a high-quality data set and played around with the layers in my Nueral Network to train a more accurate model. Because of these changes, I was able to achieve a higher validation set detection accuracy; in fact, the accuracy know is over ~80% which is a significant improvement and also demonstrates the importance of good datasets. 
