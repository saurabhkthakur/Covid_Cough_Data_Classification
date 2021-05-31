# Covid_Cough_Data_Classification

The COVID-19 pandemic is extremely detrimental to society and we need to all work together to overcome it.

## Problem
**Classify covid, symptomatic, healthy patient from patient's cough data**


## Approach

We created Multi headed CNN network to read and interpret the sequence of data at three different resolutions.
The interpretation from all three heads are then connected within the model and interpreted by Dense layer before prediction.

dataset is highly imbalanced to tackle this problem we used **smote** oversampling for minority class with **categorical focal_loss

## Result
We are getting 0.913 f1 score.
