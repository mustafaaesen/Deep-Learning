# 🧠 Deep Learning Projects with TensorFlow & Keras

This repository contains a series of beginner-to-intermediate level deep learning projects implemented with TensorFlow and Keras. The goal of this collection is to provide hands-on experience in building, training, and evaluating artificial neural networks (ANNs) for real-world problems.

## 📁 Folder Structure

Deep Learning/
├── Project 1: MNIST Digit Recognition
│ ├── Deep_Learning_Intro&Project_1_MNIST_.ipynb
│ └── deep_learning_intro&project_1_mnist_.py
├── Project 2: Credit Approval Prediction
│ ├── Deep_Learning_Project_2_Get_a_Loan__.ipynb
│ └── deep_learning_project_2_get_a_loan__.py
├── Project 3: Social Media Ad Click Prediction
│ ├── Deep_Learning_Project_3_.ipynb
│ └── deep_learning_project_3_.py
├── Datasets
│ ├── Credit Dataset/
│ │ ├── application_record.csv
│ │ └── credit_record.csv
│ ├── Social_Network_Ads.csv
└── Trained Models
└── egitilmis_modeller.zip


---

## 📌 What You’ll Learn

- How to build and compile artificial neural networks with `Keras`
- Use of activation functions, optimizers, loss functions
- Data preprocessing, normalization, and handling class imbalance
- Visualizing model performance using metrics such as:
  - Accuracy
  - Confusion Matrix
  - Precision, Recall, F1-Score
- Saving trained models as `.h5` and packaging them for deployment

---

## 🔬 Project Descriptions

### 1️⃣ MNIST Digit Recognition
- Dataset: `tf.keras.datasets.mnist`
- Problem Type: Multi-class classification
- Input: 28x28 grayscale handwritten digit images
- Output: One of 10 digits (0–9)
- Techniques: Flattening, Dense layers, softmax activation

### 2️⃣ Credit Loan Eligibility
- Dataset: Custom (Kaggle) – `application_record.csv`, `credit_record.csv`
- Problem Type: Binary classification (Risky or Not Risky)
- Challenges:
  - Imbalanced dataset (more safe customers)
  - Data merging and feature engineering
- Solutions:
  - `class_weight` handling
  - Evaluation beyond accuracy (macro vs weighted F1-score)

### 3️⃣ Social Media Ad Click Prediction
- Dataset: `Social_Network_Ads.csv`
- Problem Type: Binary classification (Click or Not Click)
- Input Features: Gender, Age, EstimatedSalary
- Output: 0 (Not Click) or 1 (Click)
- Achieved Accuracy: ~92%
- Bonus: Custom input form to simulate predictions

---

## 💾 Trained Model Files

- `egitilmis_modeller.zip` includes:
  - `reklam_tahmin_modeli.h5`
  - `kredi_tahmin_modeli.h5`
- These can be reused in real-time inference systems such as Flask or Gradio apps.

---

## 🌐 Deployment-Ready

These models are saved in `.h5` format and can easily be deployed using:

- Flask API (backend)
- Streamlit or Gradio (UI demo)
- Flutter (for mobile integration – future plan)

---

## 📣 Author

This repository was developed as part of an AI internship to gain practical knowledge in deep learning fundamentals and model deployment workflows.

---

## 📌 Future Work

- 🛠️ Convert one of the models into a complete Flask web application
- 📱 Mobile deployment via Flutter (planned)
- ✍️ Documentation & tutorials on Medium (in progress)

---

Feel free to explore, clone, and contribute!  
⭐ If you find it useful, give the repo a star!

🚀 Usage
You can run each project in two different ways:

🔹 Option 1: Using Jupyter Notebook (.ipynb)
Recommended for learning, visualization, and step-by-step debugging.

bash
Kopyala
Düzenle

# Clone the repository
git clone https://github.com/mustafaaesen/deep-learning-projects.git
cd deep-learning-projects

# Open the notebook you want (for example, MNIST)
jupyter notebook Deep_Learning_Intro&Project_1_MNIST_.ipynb
