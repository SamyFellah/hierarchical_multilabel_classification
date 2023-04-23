# Hierarchical Multi-Label Classification Model for Clothing Images
This GitHub repository contains a hierarchical multi-label classification model designed to classify clothing images by gender and a hierarchical category structure that includes master_category, sub_category, and article_type.

# Overview
The model is based on state-of-the-art deep learning techniques, specifically convolutional neural networks (CNNs) and a tree-based hierarchical multi-label classification approach. The model architecture consists of multiple CNNs that are used to extract image features, followed by multiple dense layers for predicting labels at each hierarchical level.

# Dataset
The model was trained and evaluated on a large-scale dataset of clothing images, which contains images of various types of clothing items, including tops, bottoms, dresses, shoes, and accessories. The dataset is labeled with gender information and a hierarchical category structure that includes master_category, sub_category, and article_type labels.
Link: "https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small"

# Usage
The repository includes all the code necessary to train and evaluate the model, as well as pre-trained models that can be used for inference. The code is implemented in Python using the TensorFlow deep learning framework.
