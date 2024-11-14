# Thesis-HAR-on-University-Campus
# Deep Learning for Human Activity Recognition on University Campus Data

This repository contains code, data, and documentation for a **Human Activity Recognition (HAR)** project designed for a university campus context. The project leverages deep learning techniques, specifically Convolutional Neural Networks (CNNs), to classify typical campus activities. The system aims to enhance safety, behavior analysis, and monitoring within an academic setting.

## Project Overview

The goal of this project is to develop an efficient HAR system using three deep learning models: **Custom CNN**, **VGG16**, and **MobileNetV2**. These models were applied to a **custom-created dataset** containing **2500 images** across **10 campus-related activity classes** such as calling, studying, sitting, and talking. **MobileNetV2** achieved the highest performance with an accuracy of **97%**, showcasing its efficiency for resource-constrained environments.

## Methodology

### 1. Custom Dataset Creation
This project utilizes a unique dataset created specifically for a university campus setting. The dataset includes **2500 high-resolution images** representing **10 distinct human activities**, such as calling, studying, sitting, and teaching. The images were captured using high-resolution cameras placed around the campus, ensuring a naturalistic and diverse representation of campus activities.

### 2. Model Selection and Implementation
Three models were employed for activity classification:
- **Custom CNN**: Designed specifically for this dataset, achieving **89% accuracy**.
- **VGG16**: A pre-trained model, known for its depth and pattern recognition, achieving **88% accuracy**.
- **MobileNetV2**: A lightweight and efficient model, achieving the highest accuracy of **97%**, ideal for real-time, low-resource applications.

### 3. Data Preparation and Preprocessing
- **Image Resizing**: All images were resized from **2400x2400** pixels to **224x224** pixels to match the input requirements of the models.
- **Data Augmentation**: Techniques such as rotation, flipping, and zooming were applied to artificially expand the dataset and improve model robustness.

### 4. Training and Evaluation
Each model was trained for **25 epochs**, with performance evaluated using metrics like **accuracy**, **precision**, **recall**, and **F1-score**. Cross-validation and confusion matrices were used to validate the models' robustness.

## Key Findings
- **MobileNetV2** outperformed other models, offering the best balance between accuracy and computational efficiency.
- The **custom dataset** and models demonstrated the potential of HAR in improving campus safety and behavioral monitoring.

## How to Run the Project (Google Colab)

1. **Open Google Colab**: Go to [Google Colab](https://colab.research.google.com/).
2. **Clone this Repository**: Use the following command to clone the repository and load the project files:
   ```bash
   !git clone <repository-link>
