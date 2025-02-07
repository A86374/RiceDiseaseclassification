# RiceDiseaseclassification
A collage project
# Rice Disease Classification using Deep Learning

## 📌 Project Overview
This project aims to classify rice diseases using deep learning techniques. The model is trained to recognize three different types of rice diseases from images:
- **Leaf Blight**
- **Brown Spot**
- **Leaf Smut**

The dataset consists of rice leaf images categorized into these three classes. A Convolutional Neural Network (CNN) is used to train the model, which is implemented using **TensorFlow and Keras**.

---

## 📂 Dataset
The dataset is structured as follows:
```
Rice-Disease-Classification/
│── Dataset/
│   ├── Leaf Blight/
│   ├── Brown Spot/
│   ├── Leaf Smut/
```

- The images are preprocessed and resized to **224x224** pixels.
- Data augmentation techniques are applied to enhance model generalization.

---

## ⚙️ Model Architecture
The model consists of a **CNN-based deep learning architecture**:
- **Convolutional Layers (Conv2D)** for feature extraction
- **MaxPooling Layers (MaxPooling2D)** to reduce dimensionality
- **Dropout Layers** to prevent overfitting
- **Flatten Layer** to convert feature maps into a vector
- **Dense Layers** for classification

### **Training Parameters**:
- **Batch Size**: 8
- **Image Size**: 224x224
- **Loss Function**: Categorical Crossentropy
- **Optimizer**: Adam
- **Evaluation Metrics**: Accuracy

---

## 📊 Training Results
### **Training & Validation Accuracy**
![Training Accuracy](Graphs.png)

### **Training & Validation Loss**
![Training Loss](Graphs.png)

- The accuracy graph shows an increasing trend, indicating that the model is learning well.
- The loss graph decreases over epochs, confirming proper convergence.

---

## 🚀 How to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/Rice-Disease-Classification.git
   cd Rice-Disease-Classification
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the training script:
   ```sh
   python train.py
   ```
4. Evaluate the model:
   ```sh
   python evaluate.py
   ```

---

## 🔧 Future Improvements
- Implementing **transfer learning** for better accuracy
- Deploying the model as a **web application**
- Adding more rice disease categories for improved classification

---

## 📜 License
This project is open-source and available under the **MIT License**.

---

## 👨‍💻 Author
- **TATTA AC KIRAANN**  
  📧 Email: uk1976003@gmail.com  
  🌍 LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/your-profile/)  
  🏗 GitHub: [Your GitHub Profile](https://github.com/your-username/)

