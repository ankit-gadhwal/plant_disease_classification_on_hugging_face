# Plant Disease Classification on Hugging Face

This repository contains a **single-file implementation** of a plant disease classification system using a **Vision Transformer (ViT)** model.  
The project classifies plant leaf images into **healthy, powdery, and rusty** categories and is deployed on **Hugging Face** with an interactive interface.

## Overview

- Implemented an end-to-end plant disease classification pipeline in a single Python file  
- Used a pretrained Vision Transformer model: `google/vit-base-patch16-224-in21k`  
- Dataset sourced from Kaggle and uploaded to Hugging Face  
- Achieved **100% test accuracy** on the prepared test dataset  
- Integrated **Gradio** for interactive evaluation and testing  

## File Structure

```text
.
├── plant_disease_classification_on_hugging_face.ipynb
└── README.md
