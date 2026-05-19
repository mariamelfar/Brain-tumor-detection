# Brain Tumor Detection using Deep Learning 🧠
## 📊 Project Overview

Can deep learning help identify brain tumors from MRI scans with high accuracy? This project explores how computer vision and transfer learning can be used to classify brain MRI images into tumor and non-tumor categories.

Key questions explored:

* Can transfer learning improve medical image classification performance?
* How accurately can MRI scans be classified using deep learning?
* What preprocessing and augmentation techniques improve model generalization?
* Can the model be deployed interactively for real-time predictions?

---

## 🧠 Key Steps

### Data Import & Setup

* Loaded MRI brain scan dataset
* Organized image classes and labels
* Inspected dataset structure and image distribution

### Data Preprocessing

* Resized and normalized MRI images
* Applied image transformations and augmentation
* Split dataset into training, validation, and testing sets

### Exploratory Data Analysis (EDA)

* Visualized sample MRI scans
* Examined class distribution
* Investigated dataset balance and image characteristics

### Model Building

* Implemented transfer learning using pretrained ResNet18
* Modified the final classification layer
* Configured GPU training with PyTorch

### Training & Evaluation

* Trained the model using CrossEntropyLoss and Adam optimizer
* Applied early stopping to reduce overfitting
* Evaluated performance using:

  * Accuracy
  * Precision
  * Recall
  * F1-score
  * Confusion Matrix

### Deployment

* Built an interactive Gradio interface
* Enabled real-time MRI image prediction
* Displayed prediction probabilities for uploaded scans

---

## 🧩 Tools & Libraries

* Python 3.x
* PyTorch
* Torchvision
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Gradio
* Google Colab

---

## 📁 Files

* `Cancer_Detector.ipynb` — Full notebook containing preprocessing, EDA, training, evaluation, and deployment
* `brain_tumor_model.pth` — Saved trained model
* `label_map.json` — Class label mapping
* Dataset loaded through Google Colab

---

## 🚀 How to Run

1. Open the notebook in Google Colab or Jupyter Notebook
2. Upload the MRI dataset when prompted
3. Run all cells sequentially
4. Launch the Gradio interface for predictions

---

## 🧩 Results Summary

* Transfer learning significantly improved classification performance
* Data augmentation helped reduce overfitting
* The model successfully classified MRI scans with strong accuracy
* Gradio deployment allowed interactive real-time predictions

---

## 💡 Future Improvements

* Experiment with deeper CNN architectures
* Add tumor segmentation capabilities
* Improve dataset balancing
* Deploy as a full web application
* Optimize hyperparameters for higher accuracy

---

## 👩‍💻 Author

Mariam Elfar
Mechatronics Engineering Student | AI & Robotics Enthusiast | Researcher

Exploring the intersection of deep learning, medical imaging, and intelligent systems.
