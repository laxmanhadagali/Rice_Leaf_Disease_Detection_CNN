#  Rice Leaf Disease Detection using CNN

##  Project Overview
This project focuses on detecting and classifying rice leaf diseases using a Convolutional Neural Network (CNN).  
Early identification of plant diseases helps farmers reduce crop loss and improve agricultural productivity.

The project compares CNN performance **with and without data augmentation** to analyze overfitting and model generalization.

---

##  Objectives
- Classify rice leaf images into multiple disease categories
- Build a CNN-based image classification model
- Compare model performance:
  - Without Data Augmentation
  - With Data Augmentation + Early Stopping
- Reduce overfitting and improve generalization

---

##  Dataset Description
The dataset consists of rice leaf images organized into class-wise folders:

Rice_Leaf_Dataset/
│── Bacterial_Leaf_Blight/
│── Brown_Spot/
│── Leaf_Smut/
│── Healthy/


Each folder contains RGB images of rice leaves affected by specific diseases.

---

##  Technologies & Tools Used
- Python  
- TensorFlow & Keras  
- Convolutional Neural Networks (CNN)  
- ImageDataGenerator  
- NumPy  
- Matplotlib  
- Jupyter Notebook  

---

##  Project Workflow
1. Dataset Loading & Visualization  
2. Image Preprocessing and Rescaling  
3. Train–Validation Split  
4. CNN Model Building  
5. Model Training without Data Augmentation  
6. Model Training with Data Augmentation and Early Stopping  
7. Model Evaluation  
8. Model Comparison Report  
9. Challenges Faced  
10. Conclusion  

---

##  CNN Architecture
- Convolutional Layers (Conv2D)
- MaxPooling Layers
- Flatten Layer
- Dense Layers
- Dropout Layer
- Softmax Output Layer

---

##  Model Performance Summary

| Model | Training Accuracy | Validation Accuracy | Overfitting | Generalization |
|------|------------------|--------------------|------------|---------------|
| CNN without Data Augmentation | ~99% | ~87% | High | Poor |
| CNN with Data Augmentation + Early Stopping | ~72% | ~65% | Reduced | Better |

---

##  Challenges Faced
- Limited dataset size
- Overfitting in CNN without augmentation
- Fluctuating validation accuracy
- Need for proper regularization techniques

---

##  Conclusion
- CNN successfully classified rice leaf diseases
- Data augmentation reduced overfitting
- Early stopping improved model stability
- The project demonstrates deep learning applications in agriculture

---

##  Future Enhancements
- Apply transfer learning models (VGG16, ResNet, MobileNet)
- Increase dataset size
- Deploy as a web or mobile application
- Add real-time image prediction

---

##  How to Run the Project
Install required libraries:
```bash
pip install tensorflow numpy matplotlib

