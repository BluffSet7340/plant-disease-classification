# STA401 Plant Disease Classfication Project

To meet the requirements of our coursework at the American University of Sharjah, we tasked ourselves with the classificaiton of differrent plant diseases for tomato leaves. We employed a variety of models, from traditional machine learning models to deep learning models. We then performed a comparative analysis between all the models using metrics such as accuracy, precision, f1-score, along with the confusion matrix. 

# Table of Contents

1. Dataset Preprocessing and Preparation
2. Models Used
3. Evaluating the Models
4. Authors
5. Disclaimer

# Dataset Preprocessing and Preparation

The dataset in question came from [Kaggle](https://www.kaggle.com/datasets/tushar5harma/plant-village-dataset-updated). The dataset consists of 9 plant species, from which we decided to focus on the Tomato plant species. The images for the tomato leaves has already been split into 3 folders - Train, Test, Val, with each folder having low imbalance for all classes.

Images are transformed, according to the model used to ensure compatibility, and DataLoaders are used to process data in batches for training and evaluation.

## Organizing the Tomato Plant Images

In our case, we gathered all the images for the tomato plant species and ran our models on those images. This was done via the def rename_and_merge_tomato(source_path, destination_path): function that outputted the resultant tomato images for the 3 splits into the output working folder. 

# Models Used

For training, we used the categorical crossentropy loss function and the Adam optimizer for the following models - 

1. Logistic Regression
2. Random Forest
3. SVM
4. Artificial Neural Network
5. ResNet
6. Covolutional Neural Network

# Evaluating the Models

Metrics such as accuracy, precision, and f1-scores were considered. For class-wise analysis, a confuson matrix was employed. 

# Authors

Halla
Saeed
Waiz
Rumisal

# Disclaimer

1. Kaggle Notebooks were utilized for this project
2. Since we're dealing with images, it's recommended to adjust the Session Options of the Kaggle Notebook by switching to GPU T4 x2 or GPU P100. 
3. ChatGPT was used to assist in writing and optimizing the codes allowing for efficient use of our time during the semester. 
