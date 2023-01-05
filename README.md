# Neural-Network-Homework
The main task in this challenge is to analyze risk of investing in start up for a venture capital firm.

### Organization
The relavent python notebooks is titled `venture_funding_with_deep_learning.ipynb`

### Code and Dependencies
This code is to be run on `Python 3.7.13`

The following Python Libraries were also imported and used:

`import pandas as pd`
`from path import Path`
`import tensorflow as tf`
`from tensorflow.keras.layers import Dense`
`from tensorflow.keras.models import Sequential`
`from sklearn.model_selection import train_test_split`
`from sklearn.preprocessing import StandardScaler,OneHotEncoder`

## Objectives
- Prepare the Data for Use on a Neural Network Model
- Compile and Evaluate a Binary Classification Model Using a Neural Network
- Optimize the Neural Network Model


## Results and Data Story
The original neural network had two hidden layers, one with 58 nodes and another wit 29. With this models, we acheived an accuracy score of 0.7307 with a loss of 0.5604. 

We attempted to improve on this by creating two alternative models. The first alternative models by adding an additinal hidden layer. The second alternative model attempted to improve by adding a drop out layer. Neither of the alternative models improved up on score of the original.