# GlassClassification



# Introduction
This dataset is downloaded from Kaggle website. This is a small dataset inlvolving 7 variables related to glass properties. The dataset has been cleaned for variables having zero values. The variables include:
 - RI: Refractive Index
 - Na: Sodium
 - Mg: Magnesium
 - Al : Aluminium
 - Si: Silicon
 - K : Potassium
 - Ca: Calcium 
 - Type: 1- Building windows float processed, 2- Building windows non float processed, 3- Vechicle windows float processed, 4- Vechicles windows non float processed, 5- Containers, 6- tableware, 7- headlamps
 
 
 # Working
 I have applied Decision Tree and Random Forrest Algorithms to predict the outcome of the classification of glass. 
 1. Cleaned the data for the varibales consisting of missing or zero values. 
 2. Imported various libraries Numpy, Pandas,  Matlpotlib, Seaborn
 3. Read the data from csv file 
 4. Scaled and fitted the data for normalization
 5. Imported the preprocessing for testing and training the dataset
 6. Applied Decision Tree Algorithm to predict the outcome
 7. Mapped with confusion matrix for accuracy of the predicted outcome
 8. Predicted the outcome with Random Forrest Algorithm with greater accuracy than Decision Tree Algorithm.
