# diabetesNeuralNetwork
A neural network using Keras that classifies risk for diabetes based on health data.

# Dataset description
Number of times pregnant

Plasma glucose concentration a 2 hours in an oral glucose tolerance test

Diastolic blood pressure (mm Hg)

Triceps skin fold thickness (mm)

2-Hour serum insulin (mu U/ml)

Body mass index (weight in kg/(height in m)^2)

Diabetes pedigree function

Age (years)

Class variable (0 or 1)

# Sample Run
from keras.models import load_model import numpy as np

model = load_model('weights.h5') input = np.array([[1,93,70,31,0,30.4,0.315,23]]) print(model.predict(input))
