# Fashion-MNIST-analysis
Overview
This project involves analyzing and classifying a dataset containing 70,000 grayscale images of size 28x28 pixels, representing 10 different categories of fashion items. The challenge is divided into three levels:
Level 0: Data Loading and Initial Inspection
Level 1: Exploratory Data Analysis (EDA)
Level 2: Basic Classification Model using Logistic Regression

Dataset
The dataset contains images of fashion items labeled into 10 categories.
Each image is 28x28 pixels in grayscale.
The first column of the dataset contains labels, and the remaining columns contain pixel values.

Level 0: Data Loading and Initial Inspection
Steps:
Load the dataset using Pandas.
Check the shape of the dataset.
Display a few images using Matplotlib along with their labels.
Verify the grayscale format of a single image

Level 1: Exploratory Data Analysis (EDA)
Steps:
Visualize the class distribution.
Generate summary statistics for pixel values.

Level 2: Basic Classification Model
Steps:
Normalize pixel values.
Split dataset into training and test subsets.
Implement Logistic Regression for classification.
Train the model and evaluate accuracy and loss metrics.
Implement Explainable AI techniques to interpret model decisions.

Results
The Logistic Regression model provides a basic classification accuracy for fashion items.
The confusion matrix helps visualize misclassifications.
The feature importance heatmap highlights key pixel contributions.

Future Improvements
Use Convolutional Neural Networks (CNNs) for better accuracy.
Experiment with data augmentation techniques.
Implement additional Explainable AI methods like SHAP or LIME.

Conclusion
This project successfully demonstrates data loading, exploratory analysis, and a basic classification model for Fashion MNIST using Logistic Regression. Further improvements can be made using deep learning techniques.
