## Computer-Vision-Project

# Image-to-Sentence Generation Project

This project explores image captioning, which involves automatically generating descriptive sentences for images using deep learning models. The primary goal is to bridge the gap between computer vision and natural language processing (NLP) by developing a robust system that can generate human-like captions for a wide variety of images.

# Approaches:

# Baseline Model:

Utilizes a CNN-RNN architecture with VGG16 as the image feature extractor and LSTM as the sequence generator.
Evaluated on the Flickr8K and Flickr30K datasets using BLEU scores, achieving improved performance through extensive experimentation with feature extractors, model architectures, and hyperparameters.

# Main Approach:

Combines a Vision Transformer (ViT) for image feature extraction with an RNN decoder enhanced by self-attention mechanisms.
Focuses on leveraging the advantages of transformers in capturing complex visual features to improve the overall caption quality.

# Key Experiments and Findings:

Conducted various experiments with different pre-trained CNN and ViT models to identify the best-performing feature extraction method.
Improved the baseline model through hyperparameter tuning, demonstrating notable improvements in BLEU scores.
The main approach, while more complex, showed promising results, suggesting the potential for future enhancements with larger datasets.

# Future Work:

Further hyperparameter tuning, exploration of ensemble models, and implementation of data augmentation techniques to improve model performance.
Expanding the scope to larger datasets and fine-tuning pre-trained models for feature extraction.
The code, models, and extracted features are available in this repository.


# The baselines for this project were replicated form this link:
https://towardsdatascience.com/image-captioning-with-keras-teaching-computers-to-describe-pictures-c88a46a311b8

# To access the codes, datasets, evaluation and models, you can download the .zip file from my google drive:
https://drive.google.com/file/d/1Hv-U608bqZTtVKQvL_dVYj2C3blVmVbC/view?usp=sharing
