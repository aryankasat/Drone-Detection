# Drone-Detection

## Exploratory Data Analysis

- Performed cleaning on the dataset by checking for the NULL values and filling the NULL places with (0+0j)
- Label Encoded the various classes available in the dataset
- Splitted the dataset into training and testing dataset where 80% is training dataset and 20% is testing dataset 

## Impulse Response 

Plotted the impulse reponse for one particular value in the entire dataset using the functions of the Matplot Library in python

## Machine Learning

Used 3 algorithms for the purpose of classfication, on which I have trained and tested the dataset

### Random Forest Classifier
    - F1_Score achieved - 49.57%
    - Accuracy achieved - 57.69%

### Support Vector Machine (SVM)
    - F1_score achieved - 24.62%
    - Accuracy achieved - 26.92%

### Gradient Boost Classifier
    - F1_score achieved - 31.88%
    - Accuracy achieved - 34.62%

As we can see that Random Forest Classifier has given the best accuracy and f1_score after being trained and tested on the given dataset, therefore we use Random Forest Classifier to further predict the values.
