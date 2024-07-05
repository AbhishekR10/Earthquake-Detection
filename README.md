# Earthquake-Detection
This repository contains Python scripts for earthquake detection, data preprocessing, visualization, and machine learning model training.

Data Preprocessing and Visualization:

The repository begins by loading earthquake data from a CSV file (database.csv) using pandas. It preprocesses the data by converting the date and time columns into Unix timestamps for standardized input to machine learning models. Invalid date-time combinations are handled gracefully. The resulting dataset (final_data) is then used for further analysis.Visualization of earthquake locations is facilitated using Cartopy, a mapping library. Longitude and latitude coordinates from the dataset are plotted on a world map, highlighting seismic activity with markers. Additional map features such as coastlines, land masses, oceans, and country borders enhance the visualization.

Machine Learning Model Training:
The repository includes scripts for training machine learning models on earthquake data to predict seismic parameters:

Neural Network Model: A neural network model is built using Keras to predict earthquake magnitude and depth. The model architecture consists of three dense layers with configurable neurons, activation functions, optimizer, and loss function.

Random Forest Classifier: Another script showcases the use of a Random Forest Classifier from scikit-learn to classify seismic events based on features like earthquake magnitude, depth, and location. GridSearchCV is employed for hyperparameter tuning, optimizing model performance.

Dependencies:
Ensure the following Python libraries are installed to run the scripts:

Numpy
Pandas
Matplotlib
Cartopy
Scikit-learn
Keras
