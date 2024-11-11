# Image Classification with Nomic Embed Vision v1.5

This repository provides a simple example of using the Nomic Embed Vision v1.5 model to classify a query image as either a cat or a dog. The model's vision embeddings help compute feature vectors, which are then compared to determine the closest match within known categories.

## Overview

Vision embedding models, like Nomic Embed Vision v1.5, encode images into high-dimensional feature vectors, capturing patterns and characteristics that allow for similarity-based classification. By comparing feature vectors of known images (cats and dogs) to those of a query image, we can effectively classify it without explicit training.

## Nomic Embed Vision v1.5

Nomic Embed Vision v1.5 is a state-of-the-art vision embedding model from Nomic AI, designed to create embeddings that can represent images in a shared latent space. This model aligns with Nomic's text embedding models, allowing it to support multimodal tasks. For this application, however, we use only its vision embeddings.

Learn more on [Hugging Face](https://huggingface.co/nomic-ai/nomic-embed-vision-v1.5).

## Repository Contents

- **`image_classification.py`**: Main script demonstrating image classification using Nomic Embed Vision v1.5.
- **`requirements.txt`**: List of required Python packages.

*Note: Sample images are not included in this repository. Users should provide their own images for testing.*

## Setup Instructions

**Clone the Repository**:

   ```bash
   git clone [https://github.com/yourusername/image-classification.git](https://github.com/AbhayBhandarkar/NomicCatDogClassifier.git)
   cd NomicCatDogClassifier

