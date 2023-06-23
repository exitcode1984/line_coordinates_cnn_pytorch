# Line coordinates detection
(using Pytorch CNN)

In this version I used Convolutional Neural Network implemented with the help of Pytorch.

I tried to add some necesary comments for better understanding.

Program stages:

1. Lines generator algorithm.
- generate N coordinates
- create a function to draw the images
- create a function to save the images into a dataset folder
2. Divide the data into train and test set
3. Custom DataLoader
4. Create a neural network
5. Train the NN
6. Test the NN
7. Visualize Train and Test losses
8. Visualize predictions
