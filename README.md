# Evaluating-the-Potential-of-Vision-Language-Models-for-Medical-Image-Classification
This repository contains the code and resources for our research on evaluating the potential of vision-language models for medical image classification.

# Overview
This paper investigates the potential of Vision-Language models for medical image classification, explicitly using the RetinaMNIST dataset from the well-known MedMNIST database. We conducted a comparative study on three models: Vision Transformer (ViT-Base-Patch16-224), ResNet-50, and Moondream2. The primary goal was to assess how well these models classified medical images into distinct categories. The ViT model had the highest accuracy (55%), with a precision of 51%, an F1 score of 51%, and a recall of 55%. The ResNet-50 model, a deep learning convolutional neural network, achieved 43.50% accuracy, while the Vision-Language model Moondream2 had a lower accuracy of 12.5%. These findings highlight the varying capabilities of different models in medical image classification, with Vision Transformers showing particularly promising results. This study contributes to the growing research on integrating Vision-Language models in medical imaging applications. 
The repository includes Jupyter notebooks that detail the following:

Data Preprocessing: The 2D biomedical images are preprocessed to ensure compatibility with the models. This includes tasks like normalization, resizing, and augmentation.

Model Training: The preprocessed data is split into training, validation, and test sets. These are then fed into the ViT-Base-Patch16-224, ResNet50, and Moondream models for training and evaluation.

Evaluation: Each model's performance is assessed by classifying the images into one of five categories (Class 0 to Class 4). The results from these classifications are compared to determine the strengths and weaknesses of each model.

# Usage
1. Clone the repository: git clone https://github.com/yourusername/medical-image-classification.git
cd medical-image-classification

2. Install the required dependencies: pip install -r requirements.txt
3. Run the notebooks
4. Access the Moondream API: The tiny vision-language model, Moondream, is utilized via its API available at Moondream2. Ensure you have internet access when running the related notebooks.

Data availability:
No datasets are generated during the current study. The datasets analyzed during this work can be found at: https://medmnist.com/.

# References
V. Khatri, "Moondream2 Vision-Language Model," 2024. [Online]. Available: https://huggingface.co/spaces/vikhyatk/moondream2.

