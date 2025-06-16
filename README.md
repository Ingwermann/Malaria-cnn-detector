# Malaria Cell Classification with CNN
This project implements a Convolutional Neural Network (CNN) to classify parasitized and uninfected red blood cells using microscopic images. The model is built with Keras and achieves **~99% accuracy** on the test set with data augmentation.

## Key Features
- Binary classification: `Parasitized` vs. `Uninfected`
- Model: Custom CNN (`cnn_aug_model`)
  - 4 convolutional blocks
  - ReLU activation
  - BatchNormalization and Dropout
- Data Augmentation: rotation, zoom, horizontal flip
- Optimizer: Adam
- Accuracy: **~99%**

## Project Structure
malaria-detector/
- models/cnn_aug_model.py
- notebooks/malaria_detector_training.ipynb
- requirements.txt
- .gitignore
- README.md

# Developer Info
Made by **Minyoung Hong**  
🔗 [LinkedIn](https://www.linkedin.com/in/minyoung-hong/)  
📬 minyoung.hong07@gmail.com