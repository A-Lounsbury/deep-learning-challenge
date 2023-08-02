# deep-learning-challenge
Module 21 for the Vanderbilt Data Analytics Bootcamp 2023

# Code from StackOverflow
In the cell
```
import keras_tuner as kt

# overwrite=True is very useful for testing
# https://stackoverflow.com/questions/62258704/what-does-infotensorfloworacle-triggered-exit-mean-with-keras-tuner
tuner = kt.Hyperband(
    create_model,
    objective="val_accuracy",
    overwrite=True,
    max_epochs=100,
    hyperband_iterations=2)
```
the code `overwrite=True` was found [here](https://stackoverflow.com/questions/62258704/what-does-infotensorfloworacle-triggered-exit-mean-with-keras-tuner). 