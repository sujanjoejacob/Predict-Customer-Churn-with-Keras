# Predict Customer Churn with Keras

## Data Description: 
Observations: 7,043 | Variables: 21

![alt text](https://blogs.rstudio.com/tensorflow/posts/2018-01-11-keras-customer-churn/images/figure-html/unnamed-chunk-9-1.png)


## Preprocess Data
Split Into Train/Test Sets

## Exploration: 

### DISCRETIZE THE “TENURE” FEATURE
![alt text](https://blogs.rstudio.com/tensorflow/posts/2018-01-11-keras-customer-churn/images/figure-html/unnamed-chunk-9-1.png)

### TRANSFORM THE “TOTALCHARGES” FEATURE


### ONE-HOT ENCODING
![alt text](https://blogs.rstudio.com/tensorflow/posts/2018-01-11-keras-customer-churn/images/figure-html/unnamed-chunk-9-1.png)

### FEATURE SCALING
STEP 1: PREPROCESSING WITH RECIPES
STEP 2: BAKING WITH YOUR RECIPE
STEP 3: DON’T FORGET THE TARGET

### Building A Deep Learning Model

Model
___________________________________________________________________________________________________
Layer (type)                                Output Shape                            Param #        
===================================================================================================
dense_1 (Dense)                             (None, 16)                              576            
___________________________________________________________________________________________________
dropout_1 (Dropout)                         (None, 16)                              0              
___________________________________________________________________________________________________
dense_2 (Dense)                             (None, 16)                              272            
___________________________________________________________________________________________________
dropout_2 (Dropout)                         (None, 16)                              0              
___________________________________________________________________________________________________
dense_3 (Dense)                             (None, 1)                               17             
===================================================================================================
Total params: 865
Trainable params: 865
Non-trainable params: 0

## Making Predictions

## Inspect Performance With Yardstick

## CONFUSION TABLE
## ACCURACY
## AUC
## PRECISION AND RECALL
## F1 SCORE
## Explain The Model With LIME
## FEATURE IMPORTANCE VISUALIZATION
