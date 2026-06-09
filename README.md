# Image-Classification-using-ResNet
This project uses ResNet50 to predict 10 different objects from the CIFAR-10 dataset. The model can predict an image to be one of the following:
plane, car, bird, cat, deer, dog, frog, horse, ship, truck.

Information:
You can change the dataset used in the second section, after that they dataset needs to be splitted in training data and validation data 
Then the ResNet50 model is imported and a new model is created in wich there were added additional layers for uppscaling the images prior to the ResNet50 model, after the model is loaded the next layers make the prediction.
The model is then trained and after each epoch the model is saved if it obtained better results then the previous one.
A function is used to procces the image befor it is given for prediction to the model. 

Instruction:
Run the last cell and load an image of one of the above classes, the reshaped image is displayed and the prediction of the model. 
