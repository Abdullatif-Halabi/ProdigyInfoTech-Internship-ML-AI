# ProdigyInfoTech-Internship-ML-AI
Work completed during a 4-week self-paced Machine Learning Internship at Prodigy InfoTech (July 2024).  Here, you'll find code and resources related to the 3 practical tasks independently selected and completed to achieve this goal.
Note : Don't forget to upload your Kaggle API token in any notebook before you run its cells


## Task 1: House Price Prediction with Feature Engineering
This task involved predicting house prices using a machine learning model. The dataset consisted of a significant number of features (79 columns) and data points (1460 rows). To address this complexity, I implemented feature engineering techniques such as handling missing values (e.g., mean imputation) and outlier detection to prepare the data for modeling. Additionally, I employed correlation analysis to identify redundant features and feature selection algorithms to focus on the most relevant ones for predicting house prices. A linear regression model was then employed to establish the relationship between the engineered features and house prices.




## Task 3: Cat vs. Dog Image Classification with Transfer Learning
This task focused on developing a deep learning model to classify images as cats or dogs. The dataset, sourced from Kaggle, comprised a large volume of images (25,000). Given the data size, a Convolutional Neural Network (CNN) was employed for its effectiveness in image recognition.

The approach involved two stages:

-Preprocessing and Data Augmentation: Image data preprocessing was performed using techniques like image resizing and normalization. Additionally, data augmentation techniques within the Keras ImageDataGenerator were utilized to artificially expand the dataset and improve model robustness.

-Transfer Learning with CNN and SVM: A pre-trained CNN model was employed for feature extraction. Transfer learning leveraged the pre-trained model's ability to recognize image patterns, saving training time and improving performance. The extracted features were then fed into a Support Vector Machine (SVM) for final classification of cats and dogs.
