# Disease Identification through Deep Learning Classification  

## 📌 Objective  
The goal of this project is to identify plant diseases using deep learning classification models. Two datasets—Plant Village (RGB) and a Thermal Images dataset—are used for model training, validation, and testing. The performance of multiple deep learning architectures is evaluated for disease classification.

---

## 📂 Dataset Information  

1. **Plant Village (RGB) Dataset**  
   - Source: [PlantVillage Dataset GitHub](https://github.com/spMohanty/PlantVillage-Dataset)  
   - Consists of **38 classes** of diseased and healthy plant images captured in RGB format.  

2. **Thermal Images Dataset**  
   - Source: [Kaggle Thermal Images Dataset](https://www.kaggle.com/sujaradha/thermal-images-diseased-healthy-leaves-paddy)  
   - Captures plant disease characteristics using thermal imaging.  

---

## 🧠 Deep Learning Models Used  
The following models are evaluated for disease classification:  

✅ **UNet**  
✅ **ResNet**  
✅ **SegNet**  
✅ **GoogleNet**  
✅ **VGG**  
✅ **AlexNet**  
✅ **Inception V3**  
✅ **R-CNN**  
✅ **YOLOv11**  
✅ **ViT (Vision Transformer)**  
✅ **EfficientNetV2**  

---

## ⚡ Experiments  

### 🔬 **Experiment 1: Disease Classification Accuracy Analysis**  
- **Dataset Splitting:**  
  - 60% Training  
  - 20% Validation  
  - 20% Testing  
- **Task:**  
  - Train multiple deep learning models on the datasets.  
  - Evaluate classification accuracy on the test set.  
  - Generate performance plots:
    - Training and validation accuracy for each model.  
    - Precision-Recall (PR) curves for each model on the test set.  

### 🖼️ **Experiment 2: Data Augmentation for Thermal Images**  
- **Issue:**  
  - The thermal dataset contains fewer images and is imbalanced across classes.  
- **Solution:**  
  - Use augmentation techniques (e.g., flipping, rotation, scaling, color jittering) to increase dataset size.  
  - Improve classification efficiency by training models on the augmented dataset.  
