# TRODO Dataset Machine Learning Classification 

## Objective
The objective of this project is to provide hands-on experience in machine learning classification tasks using the TRODO dataset. The tasks include the classification of odometer types (analog or digital) and the extraction of mileage from images.

## Dataset Overview
The TRODO dataset comprises 2389 annotated odometer images from vehicles in the product delivery network of Marketyo. The dataset includes both analog and digital odometers, each with proper annotations for the odometer region and recognizable characters. Ground truth information regarding actual odometer types and mileages is provided for model evaluation.

## Tasks
This project is divided into two main tasks:

### Task 1: Odometer Type Classification (Analog or Digital)
1. **Dataset Exploration**
   - Explore the contents of the TRODO dataset, focusing on odometer images and annotations.
   - Visualize sample images with annotated odometer regions.

2. **Data Preprocessing**
   - Implement data preprocessing steps, including image resizing, normalization, and data augmentation if necessary.

3. **Model Selection**
   - Choose at least five different machine learning algorithms for odometer type classification.

4. **Dataset Splitting**
   - Split the dataset into training and testing sets.

5. **Model Training**
   - Train each selected algorithm on the training set.

6. **Model Evaluation**
   - Evaluate the trained models on the testing set using appropriate metrics (accuracy, precision, recall, F1 score).
   - Provide confusion matrices for detailed analysis.
   - Compare the performance of the different models.
   - Discuss the strengths and weaknesses of each model in the context of odometer type classification.

### Task 2: Mileage Extraction
1. **Data Preprocessing**
   - Implement data preprocessing steps as in Task 1.

2. **Model Selection**
   - Choose at least two different machine learning algorithms for mileage extraction.

3. **Data Conversion**
   - Convert annotations in Pascal VOC 1.1 format to a format suitable for mileage extraction model training if necessary.

4. **Dataset Splitting**
   - Split the dataset into training and testing sets.

5. **Model Training**
   - Train each selected algorithm on the training set for mileage extraction.

6. **Model Evaluation**
   - Evaluate the trained models on the testing set using appropriate metrics.
   - Provide a detailed analysis of the mileage extraction performance, considering both accuracy and precision.
   - Compare the performance of the different models.
   - Discuss the challenges and potential improvements in mileage extraction from images.

## Installation and Setup
To run this project, you need to have Python and the following libraries installed:
- numpy
- pandas
- matplotlib
- scikit-learn
- tensorflow/keras (or other deep learning frameworks as needed)
- OpenCV
- Pillow

You can install these dependencies using pip:
```sh
pip install numpy pandas matplotlib scikit-learn tensorflow opencv-python pillow
