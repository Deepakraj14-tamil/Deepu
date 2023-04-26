# Deepu


# Breast Cancer Detection using CNN

This project is focused on detecting breast cancer using Convolutional Neural Networks (CNNs). The goal is to develop a model that can accurately classify breast cancer as either malignant or benign. The model has achieved an accuracy of 98% on the test set, but the precision, recall, and F1 score are not satisfactory, which are 10.29%, 2.17%, and 3.50%, respectively.

## Dataset
The Breast Cancer Wisconsin (Diagnostic) Dataset was used in this project, which is available on the UCI Machine Learning Repository. It contains 569 instances of breast cancer with 30 features per instance. The features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.

## Preprocessing
The dataset was preprocessed by dropping the 'id' and 'Unnamed: 32' columns, and converting the 'diagnosis' column to binary labels. The data was split into training and testing sets with a 80:20 ratio. An ImageDataGenerator was used to perform data augmentation on the training set.

## Model Architecture
The CNN model consists of a single convolutional layer with 32 filters and a kernel size of 2, followed by batch normalization, max pooling, and a flatten layer. This is followed by a single dense layer with a sigmoid activation function for binary classification.

## Training and Evaluation
The model was compiled using binary cross-entropy loss and the Adam optimizer with a learning rate of 0.001. The model was trained for 100 epochs with early stopping and a learning rate decay callback. The model achieved an accuracy of 98% on the test set, but the precision, recall, and F1 score are not satisfactory, which are 10.29%, 2.17%, and 3.50%, respectively. These results suggest that the model needs further optimization to improve its performance.

## Conclusion
This project demonstrates the use of CNNs for breast cancer detection using the Breast Cancer Wisconsin (Diagnostic) dataset. The model achieved a high accuracy, but the precision, recall, and F1 score were not satisfactory. Further optimization is required to improve the model's performance.


Project By **Deepika ilavazhagan**!!
