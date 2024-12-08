# PatternRecognition_Assignment
This project is developed by Data Alchemists to train a custom model on the Defungi dataset, sourced from the UCI Machine Learning Repository. In addition to our custom model, we have also employed ResNet50 and VGG16 pre-trained models, fine-tuning them for our specific classification task.
Project Overview
Our team focused on building and training a customized deep learning model to classify fungal species in the Defungi dataset. The dataset contains images of various fungal species and is used to explore the use of machine learning models in identifying plant diseases.

In addition to our custom-built model, we leveraged the power of pre-trained models such as ResNet50 and VGG16. We modified the final classification layers of these models, adapting them for our classification problem, while keeping the pre-trained convolutional layers frozen to extract high-level features.


Key Components:



Custom Model: Designed to work specifically for the classification task, with modifications to the architecture based on the dataset's nature.
ResNet50: A pre-trained model using the ResNet50 architecture, which has been fine-tuned by replacing the final classification layers for our task.
VGG16: Another pre-trained model using the VGG16 architecture, similarly fine-tuned to classify images from the Defungi dataset.


Workflow:
Data Preprocessing: The dataset images were resized and normalized to match the input requirements of both the custom and pre-trained models.
Model Training: Models were trained using data augmentation techniques to improve generalization. The custom model, ResNet50, and VGG16 were all trained using the dataset, and their performance was compared.

Fine-Tuning: Both ResNet50 and VGG16 were fine-tuned by changing the classifier part of the model while freezing the earlier convolutional layers to retain pre-trained knowledge.


Evaluation:
Performance was evaluated using metrics such as accuracy, confusion matrix, and classification report, comparing the models' effectiveness in classifying fungal species.
