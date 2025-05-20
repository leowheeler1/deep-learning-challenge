# Machine Learning Report

## Pre-Processing

First, the data was imported and cleaned, dropping columns that were not vital and grouping together uncommon occurences of feature variables. The data was then converted into binary variables for the model, and then saved as [processed_dat.csv](models&outputs/processed_dat.csv). This ensures that between the tuning and the model building, the same data could be utilized easily and in its processed form. The data was then split into test and train data, and the X data was scaled using `scikit-learn`'s `StandardScalar()`.

## `model.h5`

The first iteration of the model was made without any tuning, simply a best guess at parameters that might benefit the model. 
