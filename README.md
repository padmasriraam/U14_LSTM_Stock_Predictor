# Unit 14 - LSTM Stock Predictor

## I have completed the below tasks:

1. Prepare the data for training and testing
2. Build and train custom LSTM RNNs
3. Evaluate the performance of each model

## View the homework assignment from the below notebook link :
https://github.com/padmasriraam/U14_LSTM_Stock_Predictor/blob/main/src/lstm_stock_predictor_closing.ipynb
https://github.com/padmasriraam/U14_LSTM_Stock_Predictor/blob/main/src/lstm_stock_predictor_fng.ipynb

## Evaluated performance of each model

### FNG Model - Real vs Predicted

<img width="633" alt="image" src="https://user-images.githubusercontent.com/50818927/176411760-7bcfba20-8a31-42c7-a7ab-11fbb6c6ea30.png">

#### Record number of model evaluation : 

<img width="608" alt="image" src="https://user-images.githubusercontent.com/50818927/176412197-59c9b497-e336-4b18-b327-8d026ba83308.png">


### Closing price model - Real Vs Predicted 

<img width="635" alt="image" src="https://user-images.githubusercontent.com/50818927/176411981-73491786-9f50-4ac5-bc4e-ffdae0c29234.png">

#### Record number of model evaluation : 

<img width="599" alt="image" src="https://user-images.githubusercontent.com/50818927/176412104-a953bfcc-53c1-4430-8a8e-93247990daff.png">

## Answering the questions after evaluation of each model and comparing the performance.

1. **Which model has a lower loss?**
The Closing price model has the lower loss "0.006564" with window size 10 and 30 mumber of units. The FNG model loss was greater than that of the closing price model.

2. **Which model tracks the actual values better over time?**
The closing price model tracks the actual values better over time. The plot for the real vs predicted values shows evidence that closing price model is better to compare FNG.

3. **Which window size works best for the model?**
The window size 10 works best for the closing price model as it produced the lowest loss of 0.006564 when the number of units 30 with 30 epochs and batch size 3 used.

##


## GIT commit from local repository

<img width="481" alt="image" src="https://user-images.githubusercontent.com/50818927/176413096-26ec7b58-3397-4591-91df-f92c2d07f8b2.png">

