# Satellite Image Classification & Segmentation

## Project Summary
Goal: Automate land cover classification from high-resolution satellite images  
Dataset: [DeepGlobe 2018 Land Cover Classification](https://competitions.codalab.org/competitions/18468) (1146 images, 2448×2448, 7 land classes)  

Method:
  1. Binary classification of land types  
  2. Estimation of land cover fractions  
  3. Pixel-wise segmentation with U-Net  

---

## Skills Demonstrated
- ML & Deep Learning: CNNs, U-Net, MobileNetV2 (transfer learning)  
- Data Handling: Preprocessing large, high-resolution images with tiling and resizing  
- Model Training: Custom loss functions (weighted sparse categorical cross-entropy), threshold tuning, data augmentation 
- Evaluation: Accuracy, F1 score, and Intersection over Union (IoU) for segmentation  
- Tools & Libraries: Python, TensorFlow/Keras, NumPy, Pandas, Matplotlib, Google Colab  

---

## Results
- Achieved a mean IoU of 0.30 with class-specific scores up to 0.69
- Improved prediction balance on rare classes using F1-optimised thresholds and data augmentation 
- Demonstrated that transfer learning significantly reduces training time and improves performance on imbalanced datasets  

---

## Why This Project Matters 
This work highlights the potential of deep learning in real applications such as:  
- Urban planning - mapping land use and infrastructure growth  
- Agriculture – crop monitoring and land management  
- Environmental analysis – tracking deforestation and water resources  

---

## Repository Contents
- notebooks/22005915_Mini_Project_I_Code.ipynb – full implementation in Python/TensorFlow  
- README.md – project overview   

