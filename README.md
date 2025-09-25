# Classification_EuroSAT
Classifying land use from EuroSAT satellite images using ResNet-50 and CNNs

# 🌍 Land Use & Land Cover Classification with CNN (EuroSAT)

## 📌 Project Overview
This project applies a **ResNet-style Convolutional Neural Network** to classify satellite images from the **EuroSAT dataset** into 10 land-use and land-cover categories.  
The goal is to support **environmental monitoring, agriculture, and urban planning** through automated satellite image classification.

---

## 🗂 Dataset
- **EuroSAT (RGB)** — 27,000+ images, size **64×64**, 10 classes:
  - AnnualCrop, Forest, HerbaceousVegetation, Highway, Industrial, Pasture, PermanentCrop, Residential, River, SeaLake
- Source: [EuroSAT Dataset](https://github.com/phelber/eurosat)

data/
  EuroSAT_RGB/
    AnnualCrop/
    Forest/
    ...
    SeaLake/
