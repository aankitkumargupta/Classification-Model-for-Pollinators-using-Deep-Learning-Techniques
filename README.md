This project is a hands-on exploration of building a robust image classifier using deep learning techniques.
The dataset comprises 403 images categorized into two classes: ants and bees. Leveraging the power of Google Colab, we've implemented the entire workflow from data preprocessing to model evaluation.

Key Features:
Data Preprocessing:
The initial dataset underwent rescaling to a standardized size, preparing it for deep learning training.
Model Architecture:
A Convolutional Neural Network (CNN) with three Conv2D layers was designed to extract hierarchical features from the images.
Performance Evaluation:
Initial model performance was assessed, providing insights into its baseline classification capabilities.
Data Augmentation and Dropout:
Data augmentation techniques was employed during training to enhance the model's ability to generalize. Dropout layers were strategically introduced to mitigate overfitting.
Improved Model Performance:
Post-augmentation and dropout, the model's performance experienced a notable boost, demonstrating its adaptability and resilience.
Test with External Image:
The model's real-world applicability was validated by testing it with an external image sourced from the internet. The results showcased the model's proficiency in classifying unseen data.
