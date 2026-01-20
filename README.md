# Skin-Cancer-Classification-Final-Project
Skin Cancer classification with CNN model
(up to date code is in skin_cancer_classif.ipynb)

- Developed a multi-class CNN skin cancer classifier achieving 87% training accuracy on 2,357 images across 9 cancer types, implementing a 3-layer convolutional architecture (16→32→64 filters) with ReLU activation, max pooling, and fully connected layers using PyTorch

- Engineered data preprocessing and augmentation pipeline including random horizontal/vertical flips and resized cropping (180×180 pixels) to reduce overfitting, achieving 53% validation accuracy with Adam optimizer (lr=0.001) and cross-entropy loss

-Implemented Grad-CAM visualization technique to generate class activation heatmaps on convolutional layer 3, enabling interpretable identification of cancerous regions and model decision validation for correctly/incorrectly classified lesions
