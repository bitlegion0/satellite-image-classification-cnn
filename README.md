# 🌍 Satellite Image Classification using CNN

## 📌 Overview
This project implements a Convolutional Neural Network (CNN) to classify satellite images into four categories:

- 🌊 Water  
- 🌿 Green Area  
- 🏜 Desert  
- ☁ Cloudy  

The goal of this project is to demonstrate how deep learning can be applied to satellite imagery for environmental monitoring and land classification.

---

## 🧠 Model Architecture
The model is built using a Sequential CNN architecture:

- Conv2D layers for feature extraction  
- MaxPooling layers for dimensionality reduction  
- Fully Connected Dense layers  
- Softmax activation for multi-class classification  

---

## ⚙️ Tech Stack
- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## 📁 Dataset

⚠️ **Note:** The dataset is not included in this repository due to size limitations.

### 🔗 Dataset Options:
You can use any satellite image dataset from:

- Kaggle (recommended)
- Google Dataset Search
- Or your own collected dataset

### 📂 Expected Folder Structure:
data/
├── water/
├── green_area/
├── desert/
├── cloudy/


Each folder should contain images corresponding to its class.

---

## 🚀 How to Run

### 1. Clone the repository

### 2. Install dependencies
### 3. Add dataset
Download the dataset and place it inside the project folder:
project/
│── data/
│ ├── water/
│ ├── green_area/
│ ├── desert/
│ ├── cloudy/

### 4. Run the notebook


Open `satellite.ipynb` and run all cells.

---

## 📊 Results

- Model achieves good classification performance on test data  
- Evaluated using:
  - Accuracy  
  - Confusion Matrix  
  - Classification Report  

---

## 🖼️ Sample Output

(Add screenshots of predictions here for better presentation)

---

## 🔮 Future Improvements

- 🔥 Use Transfer Learning (ResNet, MobileNet)  
- 📈 Hyperparameter tuning  
- 🌐 Deploy as a web application  
- 📊 Use larger and more diverse datasets  

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to fork this repository and improve the project.

---

## ⭐ Acknowledgment

This project was built as part of a deep learning practice to explore real-world applications of CNNs.

---

## 📬 Contact

If you liked this project, feel free to connect with me on LinkedIn!
