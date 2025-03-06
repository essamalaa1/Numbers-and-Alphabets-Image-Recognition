This project aims to develop a deep learning model to classify images of numbers and alphabets. The model is trained using a convolutional neural network (CNN) architecture, leveraging TensorFlow and Keras. The dataset consists of labeled images of digits (0-9) and letters (A-Z), which are processed and classified using a deep learning model.

### Project Steps:
## Importing Dependencies
Load necessary libraries, including TensorFlow, Keras, Matplotlib, Seaborn, and Sklearn for data preprocessing and evaluation.

## Dataset Preparation
Load images from the dataset directory using image_dataset_from_directory().
Perform dataset splitting into training, validation, and testing sets.
Visualize sample images using Matplotlib.

## Data Augmentation & Preprocessing
Apply transformations such as rotation, flipping, and zoom to improve model generalization.
Normalize pixel values to speed up convergence.

## Model Architecture
Use ResNet50 as the base model for feature extraction.
Add additional layers such as:
Global Average Pooling Layer
Fully Connected Dense Layer
Softmax Activation Layer for multi-class classification.

## Training the Model
Compile the model with Sparse Categorical Crossentropy as the loss function.
Use Adam optimizer and track accuracy and loss metrics.
Implement early stopping and checkpointing to save the best model.

## Model Evaluation
Generate predictions on the test set.
Compute and visualize the confusion matrix using Seaborn.
Print the classification report to analyze precision, recall, and F1-score.

## Results & Visualization
Plot training/validation accuracy and loss curves.
Display sample test images with predicted labels.

## Future Improvements
Experiment with different CNN architectures (e.g., MobileNet, EfficientNet).
Fine-tune the model for better accuracy.
Deploy the model for real-time recognition.
Classification Problem with 61 class to predict

![Alt text](https://github.com/essamalaa1/Numbers-and-Alphabets-Image-Recognition/blob/main/a35f0b2a-2ff9-43d1-9165-8cdc8b8ebe9c.png)
