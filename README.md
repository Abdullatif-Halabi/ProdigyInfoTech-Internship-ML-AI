# ProdigyInfoTech-Internship-ML-AI
Work completed during a 4-week self-paced Machine Learning Internship at Prodigy InfoTech (July 2024).  Here, you'll find code and resources related to the 3 practical tasks independently selected and completed to achieve this goal.
#### Note : Don't forget to upload your Kaggle API token in any notebook before you run its cells


## Task 1: House Price Prediction with Feature Engineering
This task involved predicting house prices using a machine learning model. The dataset consisted of a significant number of features (79 columns) and data points (1460 rows). To address this complexity, I implemented feature engineering techniques such as handling missing values (e.g., mean imputation) and outlier detection to prepare the data for modeling. Additionally, I employed correlation analysis to identify redundant features and feature selection algorithms to focus on the most relevant ones for predicting house prices. A linear regression model was then employed to establish the relationship between the engineered features and house prices.




## Task 2: Customer Segmentation using K-Means Clustering
This project focuses on understanding customer behavior within a retail environment through customer segmentation. Leveraging K-Means clustering and the elbow method, we've identified five distinct customer groups based on factors such as age, gender, income, and spending habits. By delving into these segments, we aim to provide actionable insights for targeted marketing strategies. The dataset employed includes customer demographics and assigned spending scores. Our analysis offers a clear picture of customer preferences, enabling businesses to tailor their offerings effectively.




## Task 3: Cat vs. Dog Image Classification with Transfer Learning
This task focused on developing a deep learning model to classify images as cats or dogs. The dataset, sourced from Kaggle, comprised a large volume of images (25,000). Given the data size, a Convolutional Neural Network (CNN) was employed for its effectiveness in image recognition.

The approach involved two stages:

-Preprocessing and Data Augmentation: Image data preprocessing was performed using techniques like image resizing and normalization. Additionally, data augmentation techniques within the Keras ImageDataGenerator were utilized to artificially expand the dataset and improve model robustness.

-Transfer Learning with CNN and SVM: A pre-trained CNN model was employed for feature extraction. Transfer learning leveraged the pre-trained model's ability to recognize image patterns, saving training time and improving performance. The extracted features were then fed into a Support Vector Machine (SVM) for final classification of cats and dogs.




## Task 5: Food Image Classification and Calorie Estimation
This project aims to develop a model capable of classifying food images and estimating their calorie content. Initially, the goal was to employ a YOLO segmentation model for precise food identification and quantification. However, due to computational constraints (limited GPU access), the project transitioned to a classification-based approach.

### This repository contains two primary notebooks:
Prodigy_Task5: Demonstrates the core model architecture and training process using a classification approach.

DataPreparation_for_YOLOseg: Outlines the data preprocessing and engineering steps required for a YOLO segmentation model, providing a foundation for future work.

### Limitations
The project was significantly impacted by limited GPU resources. As a result, the training dataset for the classification model was reduced, potentially affecting the model's accuracy. Additionally, the dataset used in 'DataPreparation_for_YOLOseg' is not ideal for production use and serves primarily as a demonstration of the process.

Future Work
Expand the dataset to improve model performance.
Implement a YOLO segmentation model with access to sufficient computational resources.
Investigate more advanced calorie estimation techniques.
