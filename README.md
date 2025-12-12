# Tomato-Leaf-Diseases-Image-Classification-Using-Deep-Learning
---

## **Problem:** 
Plant disease identification for smallholder farmers using computer vision and deep learning. 

## **INPUT:**
- **Data:** Raw images of tomato leaves (resized to 150×150 pixels) 
- **Dataset Source:** 9,000 images extracted from the PlantVillage dataset
- **Classes:** 6 categories:
  - Bacterial Spot
  - Early Blight
  - Healthy leaves
  - Septorial Leaf Spot
  - Leaf Mold
  - Yellow Leaf Curl Virus
- **Image Format:** Two approaches tested:
   - full-color (3 channels) 
   - grayscale (1 channel)

## **OUTPUT:**
- **Model Architecture:** CNN-based deep learning model with 4 convolutional layers (with ReLU activation) followed by max pooling layers, and 2 dense layers with Softmax output [7](#0-6) 
- **Classification Results:** 
  - Full-Color Model: **99.84% accuracy** on held-out test set [8](#0-7) 
  - Grayscale Model: **95.54% accuracy** on held-out test set [8](#0-7) 
- **Disease Identification:** The model predicts one of 6 classes for each input image
- **Visualization:** Feature maps showing intermediate activations demonstrate that the full-color model learned to identify disease spots, while the grayscale model primarily learned leaf shape and background patterns [9](#0-8) 
- **Deployment Target:** Smartphone application for field use by farmers [10](#0-9) 

---

## **Notes:**
This repository demonstrates a completely different use case from your example (plant disease detection vs. test grading). The project uses state-of-the-art deep learning techniques to create a practical tool for agricultural disease management, particularly aimed at helping smallholder farmers who depend on healthy crops for survival. [11](#0-10)




