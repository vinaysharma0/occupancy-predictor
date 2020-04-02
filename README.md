# occupancy-predictor

This model describes the occupancy with the parameters like temperature, humidity, light and CO2, which describes whether the place would be occupied or not,
it means these are the factors on which occupancy depends (It is either 0 or 1).

0 : Not occupied,
1 : Occupied


There are 3 datasets from which 1 is for training as usual and 2 are for testing.

I tested model on both the testing datasets and the results were pretty good.

I have added pretrained model with 15 epochs if you want to train it for more epochs you can do it yourself but try to train it on GPU otherwise it will take time , consider using Google Colab.


MODEL USED :
           
           LSTMs => loss: 0.0308 - accuracy: 0.9882 - val_loss: 0.0362 - val_accuracy: 0.9883
           

ACCURACY : 

           1st dataset ----->  92.94% (having size of 2665 inputs)

           2nd dataset ----->  95.89% (having size of 9752 inputs)
