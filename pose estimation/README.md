# Hand Sign Recognition 

This project involves building a computer vision-based system for recognizing hand signs using pose estimation techniques. The problem is framed as a classification 
task, where the goal is to identify hand signs based on their pose landmarks. The project uses Mediapipe for hand landmark detection and Roboflow for sourcing the 
image dataset.

## Project Overview

The primary objective of this project is to develop a model that classifies hand signs into distinct categories using pose estimation data. This involves extracting 
hand landmarks, saving the data for analysis, and applying machine learning algorithms to perform classification.

##  Dataset Details
Source: [Roboflow Hand Signs Dataset]()

## Steps in the Project

Used Mediapipe’s Hands module to detect and extract hand landmarks.

Saved extracted landmarks as coordinate points in a CSV file for further processing.

### Machine Learning Algorithms:

Applied different machine learning classifiers to the extracted landmark data.

MLP Classifier: Trained a Multi-Layer Perceptron (MLP) with GridSearch for hyperparameter tuning, achieving an accuracy of 70%.

Random Forest Classifier: Trained a Random Forest model, achieving an accuracy of 56%.
