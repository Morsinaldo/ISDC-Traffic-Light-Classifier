# Overview

In this project, computer vision techniques was used to build a classifier for images of traffic lights! In this repository, there is a dataset of traffic light images in which one of three lights is illuminated: red, yellow, or green. The goal in the project [notebook](./Traffic_Light_Classifier.ipynb) is to construct a classification model step-by-step. The completed classification code should accept an RGB image as input and produce a predicted label for that image.

![](./images/all_lights.png)

In the [notebook](./Traffic_Light_Classifier.ipynb), the following steps have been completed for classifying traffic light images into three categories: red, yellow, or green.

1. **Loading and Visualizing Data**: The data has been loaded, and the images of traffic lights have been visualized to familiarize with the dataset.

2. **Pre-processing**: Both input images and output labels have been standardized. All input data is of the same type and size, while output labels are numerical. This standardization ensures uniform analysis procedures across all input images and provides expected output labels for new image classifications.

3. **Feature Extraction**: Features have been extracted from each image to facilitate distinction and classification. Various feature extraction techniques have been explored, aiming for 1D vectors or single values that convey relevant information about the images' colors, shapes, or patterns.

4. **Classification and Error Visualization**: A function has been implemented to classify traffic light images based on the extracted features. This function takes an image as input and produces a label. Additionally, code has been provided to classify a test set of data, compare predicted labels with true labels, and visualize classification errors.

5. **Model Evaluation**: The classifier achieves over 90% accuracy and ensures no misclassification of red lights as green. Iterative improvements may be necessary to enhance classifier accuracy, potentially by adjusting existing features or incorporating new ones. Striving for near 100% accuracy is encouraged.

The implementation aims to fulfill the project requirements and provide a robust classification solution for traffic light images.

## Project Files

- **Traffic_Light_Classifier.ipynb**: The notebook provides template code to guide you through the project. However, additional code implementation is required to successfully complete the tasks. Sections marked with '(IMPLEMENTATION)' in the header indicate where implementation is necessary. Additionally, there are questions labeled '(QUESTION)' to prompt your thoughts as you progress through the project.
- **helpers.py**: This file contains helper functions responsible for loading data.
- **test_functions.py**: It contains test functions allowing you to assess your code's correctness as you proceed. While you don't need to modify these files, you have the option to add to them if required. It's recommended to examine the test functions to understand how they evaluate your code.

## Project Rubric

You should submit your project once you meet the following criteria:

- Achieve greater than 90% accuracy.
- Ensure red lights are never misclassified as green.

## References

[Introduction to Self-Driving Cars NanoDegree](https://learn.udacity.com/nanodegrees/nd113)