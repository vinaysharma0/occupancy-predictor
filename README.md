# occupancy-predictor

This model describes the occupancy with the parameters like temperature, humidity, light and CO2, which describes whether the place would be occupied or not,
it means these are the factors on which occupancy depends (It is either 0 or 1).

0 : Not occupied,
1 : Occupied


There are 3 datasets from which 1 is for training as usual and 2 are for testing.

I tested model on both the testing datasets and the results were pretty good.

I didn't save the model because it would not take any time even if you train it by yourself , it would hardly take 10 seconds.


MODEL USED :
           
           LSTMs => loss: 0.0353 - accuracy: 0.9880 - val_loss: 0.0287 - val_accuracy: 0.9902
           

ACCURACY : 

           1st dataset ----->  98.83% (having size of 2665 inputs)

           2nd dataset ----->  98.01% (having size of 9752 inputs)
