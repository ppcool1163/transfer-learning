# transfer-learning
I have used a Inception model (Made by google at ImageNet competition 2015) as a pre-trained model for transfer learning and added 1 flattening layer and a Dense Hidden layer with the Output layer.

# Image Augmentation
I have used built in tensorflow function called ImageDataGenerator to apply different kind of Augmentation to the training Data. We can also use ImageDataGenerator to label the training and testing data. ImageDataGenerator labels the dataset according to the name of the directory they are placed in. Here is an example on how the ImageDataGenerator labels the data according to the directory they are placed in:

<img src="https://expoundai.files.wordpress.com/2019/04/directorystructure.png?w=640"> 

