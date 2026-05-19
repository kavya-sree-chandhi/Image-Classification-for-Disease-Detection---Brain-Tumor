# 🧠 Brain Tumor Detection using Deep Learning

A deep learning-based medical imaging project that classifies MRI brain scans to detect the presence of brain tumors. This project leverages Convolutional Neural Networks (CNNs) and transfer learning models such as VGG16 and ResNet50 to achieve high classification accuracy and support early diagnosis.

---

## 📌 Project Overview

Brain tumors are among the most critical neurological disorders, where early and accurate diagnosis can significantly improve treatment outcomes. Manual interpretation of MRI scans is time-consuming and dependent on radiologists' expertise.

This project automates brain tumor detection using deep learning techniques to classify MRI images into:

- **Tumor**
- **No Tumor**

The solution uses advanced image preprocessing, CNN architectures, and transfer learning to build a robust and accurate classification model.

---

## 🎯 Objectives

- Develop an automated brain tumor detection system using MRI images.
- Compare performance of custom CNN and transfer learning models.
- Improve diagnostic accuracy and reduce manual effort.
- Visualize model performance using metrics and plots.

---

## 🧰 Tech Stack

### Programming Language
- Python

### Libraries & Frameworks
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- OpenCV
- Scikit-learn

### Development Environment
- Google Colab / Jupyter Notebook

---

## 📂 Dataset

The dataset contains MRI images categorized into two classes:

- `yes/` → Brain tumor present
- `no/` → No brain tumor

### Image Preprocessing
- Resizing images to a fixed dimension
- Normalization
- Data augmentation:
  - Rotation
  - Zoom
  - Horizontal flipping
  - Shearing

---

## 🏗️ Model Architectures

### 🔹 Custom CNN
A sequential CNN model with:
- Convolution layers
- MaxPooling layers
- Dropout layers
- Dense layers
- Sigmoid activation for binary classification

### 🔹 VGG16 Transfer Learning
- Pretrained on ImageNet
- Top layers replaced with custom classification head
- Fine-tuned for MRI classification

### 🔹 ResNet50 Transfer Learning
- Residual network architecture
- Strong feature extraction capabilities
- Fine-tuned for optimal performance

---

## 📊 Results

| Model | Accuracy |
|------|------:|
| Custom CNN | 95%+ |
| VGG16 | 97%+ |
| ResNet50 | **98%+** |

### Performance Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC Curve

---

## 📈 Visualizations

The notebook includes:
- Sample MRI image display
- Training vs Validation Accuracy
- Training vs Validation Loss
- Confusion Matrix
- Classification Report

---

## 🚀 How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/kavya-sree-chandhi/Image-Classification-for-Disease-Detection---Brain-Tumor.git
cd Image-Classification-for-Disease-Detection---Brain-Tumor
```

### 2. Install Dependencies
```bash
pip install tensorflow keras numpy pandas matplotlib seaborn scikit-learn opencv-python
```

### 3.Open the Notebook

Launch Jupyter Notebook or Google Colab and run:
```bash
Image_Classification_for_Disease_Detection_Brain_Tumor.ipynb
```

## 🧪 Project Workflow

1. Load and explore the MRI image dataset.
2. Perform image preprocessing, including resizing and normalization.
3. Apply data augmentation techniques to improve model generalization.
4. Split the dataset into training and validation sets.
5. Build and train deep learning models, including a custom CNN, VGG16, and ResNet50.
6. Evaluate model performance using accuracy, precision, recall, F1-score, and confusion matrix.
7. Visualize training history, predictions, and performance metrics.

---

## 📌 Sample Use Cases

- Clinical decision support for assisting radiologists in tumor detection.
- Medical research and experimentation with deep learning techniques.
- Educational demonstrations for machine learning and healthcare analytics.
- AI-powered healthcare applications for automated diagnostic support.

---

## 🔮 Future Enhancements

- Extend to multi-class tumor classification (Glioma, Meningioma, Pituitary).
- Implement tumor segmentation using U-Net.
- Deploy the model as a web application using Streamlit or Flask.
- Add Explainable AI techniques such as Grad-CAM for model interpretability.
- Integrate with hospital PACS systems for real-world clinical workflows.

## 👩‍💻 Author

**Kavya Sree Chandhi**  
Software Engineer | Python | AWS | SQL | Generative AI

- 📧 Email: chandhikavyasree@gmail.com
- 🔗 LinkedIn: https://www.linkedin.com/in/chandhi-kavya-sree/
- 🐙 GitHub: https://github.com/kavya-sree-chandhi
- 🌐 Portfolio: https://kavya-sree-chandhi.github.io

---

## 📜 License

This project is intended for academic, research, and educational purposes only.

Feel free to use, modify, and build upon this work with proper attribution.

---

