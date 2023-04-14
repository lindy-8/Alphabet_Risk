# Alphabet Risk
This is a Google Colab note book application that observes historical data and feeds it into a nueral network that accurately predicts a ventures' outcome, may it  be successful or not. From the parameters introduced in this notebook, those are what we trained the network on and enables the network to assign values of 0 or 1, depending on th prediction. Through trial and scaling, the network became more accurate in better with optimization.
---

## Technologies & Libraries

This project utilizes python 3.7 with the following packages:

* [Pandas](https://github.com/pandas-dev/pandas) - For the command line interface, help page, and entrypoint.

* [Tensorflow](https://www.tensorflow.org/) - The fundamental package for scientific computing with Python.

* [Keras](https://github.com/keras-team/keras) - Keras is an API designed for human beings, not machines. Keras follows best practices for reducing cognitive load
    Dense, Sequential.

* [Sklean.metrics](https://github.com/scikit-learn/scikit-learn) - Simple and efficient tools for predictive data analysis  
    OncHotEncoder, StandardScaler, train_test_split.

* [GoogleColab](https://colab.research.google.com/) - Colab, or "Colaboratory", allows you to write and execute Python in your browser, with zero configuration required, access to GPUs free of charge, easy sharing.

---

## Pre installation Guide

*Note if you are running it on the cloud, versus locally, you will have to run all line of codes to properly use the application. 
Prior to running the application and code, please install the following dependencies:

```
import pandas as pd
import tensorflow as tf
from tensorflow.keras.layers import Dense
from tensorflow.keras.models import Sequential
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler,OneHotEncoder
``` 

---

## Contributors

DU Starter Code

Ben Lindauer

---

## License

MIT
