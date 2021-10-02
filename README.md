# *Module 13 Challenge*
## Deep Neural Network for Predicting Successful Funding Applicants

**Welcome to my Module 13 Challenge repository. Here, you can check out the binary classification model I created using a deep neural network to predict whether Alphabet Soup funding aaplicant will be successful. Find out more in the follwing sections!**

---

## Background
For this project, I was to act as a risk management associate at Alphabet Soup, a venture capital firm. Alphabet Soup’s business team receives many funding applications from startups every day. This team has asked me to help them create a model that predicts whether applicants will be successful if funded by Alphabet Soup.

The business team has given me a CSV file containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. The CSV file contains a variety of information about each business, including whether or not it ultimately became successful. Using techniques of machine learning and neural networks, I decided to use the features in the provided dataset to create a binary classifier model that will predict whether an applicant will become a successful business.

This challenge consists of three technical deliverables:
- Preprocess data for a neural network model.
- Use the model-ift-predict pattern to compiles and evaluate a binary classification model.
- Optimize the model.

---

## Technologies & Usage
This project leverages Python 3.7, TensorFlow and the Keras Library, SciKit-Learn, and the Pandas library with the following requirements and dependencies:
- import pandas as pd
- from pathlib import Path
- import tensorflow as tf
- from tensorflow.keras.layers import Dense
- from tensorflow.keras.models import Sequential
- from sklearn.model_selection import train_test_split
- from sklearn.preprocessing import StandardScaler,OneHotEncoder
