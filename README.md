# Fetal Brain Ultrasound Image Classification


## Overview

This project utilizes Convolutional Neural Networks (CNN) and its variations to classify fetal brain ultrasound images as normal or abnormal. The goal is to provide a reliable tool for identifying potential abnormalities during prenatal imaging. The project also incorporates eXplainable Artificial Intelligence (XAI) techniques, including LIME and Grad-CAM, for improved model interpretability.

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Models](#models)
- [eXplainable AI (XAI)](#explainable-ai-xai)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Key Features

- **Deep-Learning Classification:** Utilizes Convolutional Neural Networks (CNN) and variations for accurate classification of fetal brain ultrasound images.
- **Model Explainability:** Incorporates eXplainable Artificial Intelligence (XAI) techniques, including LIME and Grad-CAM, for better interpretability of model predictions.
- **User-Friendly Interface:** Provides a user-friendly web interface for easy interaction with the model.
- **Adaptive Imaging Protocols:** Guides adaptive imaging protocols based on model insights, optimizing image acquisition for better results.

## Models

### CNN (Convolutional Neural Network)

The CNN architecture is employed as the primary deep-learning model for image classification. CNNs are well-suited for image-based tasks, and their hierarchical feature learning enables accurate detection of abnormalities in fetal brain ultrasound images.

### CNN Variations

#### 1. **Modified CNN Architecture**

A customized CNN architecture with specific modifications tailored to enhance performance in fetal brain ultrasound image classification.

#### 2. **Transfer Learning with Pre-trained CNN Models**

Utilizing pre-trained CNN models (e.g., VGG16, ResNet) and fine-tuning them on the fetal brain ultrasound dataset for improved efficiency and accuracy.

## eXplainable AI (XAI)

### LIME (Local Interpretable Model-agnostic Explanations)

LIME is employed for model interpretability by generating locally faithful explanations for individual predictions. It perturbs input data and observes the impact on model predictions, providing insights into the decision boundaries.

### Grad-CAM (Gradient-weighted Class Activation Mapping)

Grad-CAM is utilized to visualize the regions of fetal brain ultrasound images that are crucial for classification decisions. It highlights important areas, enhancing transparency and understanding of the model's focus.

### Theory

#### Convolutional Neural Networks (CNN)

CNNs are a class of deep neural networks specifically designed for image-based tasks. They consist of convolutional layers that learn hierarchical features from input images, making them highly effective for image classification tasks.

#### LIME (Local Interpretable Model-agnostic Explanations)

LIME is an XAI technique that explains the predictions of machine learning models. It works by generating perturbed samples of the input data, observing the model's behavior on these samples, and fitting a local interpretable model to approximate the black-box model.

#### Grad-CAM (Gradient-weighted Class Activation Mapping)

Grad-CAM produces visual explanations by leveraging the gradients of the target class with respect to the model's feature maps. It highlights the regions in an image that contribute most to the decision-making process.

## Installation

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/your-username/fetal-brain-classification.git
    cd fetal-brain-classification
    ```

2. **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Download Pre-trained Models:**
    - [Link to Pre-trained Models]

## Usage

1. **Run the Application:**
    ```bash
    python app.py
    ```
2. **Visit [http://localhost:5000](http://localhost:5000) in your web browser.**
    - Follow the on-screen instructions for image upload and classification.


## Contributing

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/new-feature`.
3. Commit your changes: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature/new-feature`.
5. Submit a pull request.


---

Feel free to explore the project, contribute, and provide feedback! 🚀
