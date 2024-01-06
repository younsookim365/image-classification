# Image Classification
Image classification with Tensorflow conducted in Python using Jupyter Notebook.

## Chosen Data Set and Its Suitability for Image Classification
The chosen dataset is suitable for image classification due to its well-defined categories of "Public Buildings" and "Apartments." It exhibits diversity in modern architectural styles, presenting a challenge for the model to learn intricate patterns. With over 100,000 images, the dataset provides substantial data for effective generalization in deep learning models. The folder structure aligns with popular frameworks, simplifying data loading, and the dataset reflects real-world scenarios where image classification is relevant, such as urban planning. Balancing efforts prevent bias, and the use of a pre-trained model (VGG16) enhances performance through transfer learning. The practical applications of classifying building images in sectors like urban planning make the dataset valuable. Lastly, the dataset's organization promotes experiment reproducibility and transparency.

## Analysis Objectives
The analysis aims to classify images into "Public Buildings" and "Apartments." It involves exploring and understanding the dataset, preprocessing (resizing, normalization), and applying data augmentation. A pre-trained CNN with attention mechanism is used for better focus on relevant image regions. Transfer learning fine-tunes specific layers for the classification task. The model architecture includes Flatten, Dense (ReLU activation), Dropout for regularization, and a final Dense layer (softmax activation). It is compiled, trained, and evaluated using metrics like accuracy and F1 score. Optional steps include fine-tuning and deployment. Attention to data quality, model architecture, and training parameters is emphasized for a robust model.

## Reference to data set source:
Paulat, T., 2022. 🔥 100.000 Architectural Photographies. [Online] 
Available at: https://www.kaggle.com/datasets/tompaulat/modern-architecture-100k-small-images/data
[Accessed 15 November 2023].
