
# Oral Cancer Classification using Transfer Learning

This project focuses on classifying oral cancer images using transfer learning with the VGG16 model. The goal is to differentiate between "cancer" and "non-cancer" images effectively by leveraging a pre-trained deep learning model.

## Project Overview
The notebook in this repository demonstrates the process of building and training a deep learning model to classify oral cancer images. The key steps involved are:

1. **Data Preparation**: Organizing the dataset into training and testing directories with appropriate labels.
2. **Data Augmentation**: Applying transformations to the training images to improve model generalization.
3. **Model Building**: Using the VGG16 architecture pre-trained on the ImageNet dataset and adding custom layers for our specific classification task.
4. **Model Training**: Training the model on the augmented dataset and validating its performance on the test set.
5. **Model Evaluation**: Assessing the accuracy and performance of the trained model.
6. **Model Saving**: Saving the trained model for future inference.
7. **Making Predictions**: Loading the saved model and making predictions on new, unseen images.

## Key Achievements
- **Transfer Learning**: Utilized the powerful VGG16 model pre-trained on ImageNet for feature extraction.
- **Data Augmentation**: Improved model robustness by applying various transformations to the training images.
- **High Accuracy**: Achieved significant accuracy in classifying cancerous and non-cancerous images.
- **Model Deployment**: Demonstrated how to save and reload the model for future use.

## How to Use
1. Clone the repository and upload the notebook to Google Colab.
2. Follow the instructions in the notebook to mount your Google Drive and set up the dataset.
3. Run the notebook cells to train the model and evaluate its performance.
4. Upload an image and use the trained model to classify it as "cancer" or "non-cancer".

## Dataset
The dataset should be organized into the following structure:
<ul>
<li><strong>data/</strong></li>
  <ul>
    <li><strong>train/</strong></li>
      <ul>
        <li><strong>cancer/</strong></li>
        <li><strong>non-cancer/</strong></li>
      </ul>
    <li><strong>test/</strong></li>
      <ul>
        <li><strong>cancer/</strong></li>
        <li><strong>non-cancer/</strong></li>
      </ul>
  </ul>
</ul>


## Requirements
- Python 3.x
- TensorFlow
- Keras
- Google Colab

## Acknowledgements
- This project utilizes the VGG16 model provided by Keras.
- Thanks to the creators of the dataset used for training and testing the model.
- Special thanks to Google Colab for providing the computing resources necessary for training deep learning models.

