# Evaluating-the-Potential-of-Vision-Language-Models-for-Medical-Image-Classification
This repository contains the code and resources for our research on evaluating the potential of vision-language models for medical image classification, as described in our conference paper titled "Evaluating the Potential of Vision-Language Models for Medical Image Classification."

# Overview
The primary goal of this project is to explore the effectiveness of different machine learning models, including Vision Transformers (ViTs), Convolutional Neural Networks (CNNs), and a tiny vision-language model called Moondream, in the classification of 2D biomedical images. The repository includes Jupyter notebooks that detail the following:

Data Preprocessing: The 2D biomedical images are preprocessed to ensure compatibility with the models. This includes tasks like normalization, resizing, and augmentation.

Model Training: The preprocessed data is split into training, validation, and test sets. These are then fed into the ViT-Base-Patch16-224, ResNet50, and Moondream models for training and evaluation.

Evaluation: Each model's performance is assessed by classifying the images into one of five categories (Class 0 to Class 4). The results from these classifications are compared to determine the strengths and weaknesses of each model.

# Usage
1. Clone the repository: git clone https://github.com/yourusername/medical-image-classification.git
cd medical-image-classification

2. Install the required dependencies: pip install -r requirements.txt
3. Run the notebooks
4. Access the Moondream API: The tiny vision-language model, Moondream, is utilized via its API available at Moondream2. Ensure you have internet access when running the related notebooks.
# References
V. Khatri, "Moondream2 Vision-Language Model," 2024. [Online]. Available: https://huggingface.co/spaces/vikhyatk/moondream2.

