# 🧑‍💻 Age & Gender Prediction using Deep Learning  

This project predicts a person's **age** (regression) and **gender** (classification) from an image using a deep learning model built with TensorFlow and Keras. It utilizes **VGG16** as a pre-trained backbone and custom dense layers for multi-output predictions.

---

## 📌 Features  
✅ **Pretrained VGG16 Backbone** (transfer learning)  
✅ **Multi-output model** for predicting age and gender simultaneously  
✅ **Image preprocessing & augmentation** using `ImageDataGenerator`  
✅ **Supports large datasets** using `flow_from_dataframe()`  
✅ **Evaluates model performance on test data**  

---

## 📂 Dataset  
- The dataset should contain images with corresponding labels:  
  - `age`: Continuous value (e.g., `25`)  
  - `gender`: Binary label (`0 = Male`, `1 = Female`)  
- Data is stored in a **CSV file** with image paths and labels.  
- Example structure:  

